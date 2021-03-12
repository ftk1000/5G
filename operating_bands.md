# Operating Bands

### LTE ts36.521-1 v 15.5.0 2019-07 [LTE; Evolved Universal Terrestrial Radio Access (E-UTRA); User Equipment (UE) conformance specification; Radio transmission and reception; Part 1: Conformance testing (3GPP TS 36.521-1 version 15.5.0 Release 15) - ETSI TS 136 521-1 V15.5.0 (2019-07)](https://www.etsi.org/deliver/etsi_ts/136500_136599/13652101/15.05.00_60/ts_13652101v150500p.pdf)

* 5 Frequency bands and channel arrangement p 133+
* 5.2 Operating bands p 133+
* Table 5.2-1: E-UTRA operating bands p 133+
   - E-UTRA Operating Bands: n1 - n76 
   - UL operating band (BS receive, UE transmit): F_{UL_{low}} – F_{UL_{high}}
   - DL operating band (BS transmit, UE receive): F_{DL_{low}} – F_{DL_{high}}
   - Duplex Mode
    
* 5.4.3 Channel raster  p.251+
      The channel raster is 100 kHz for all bands, which means that the carrier centre frequency must be an integer multiple of 100 kHz.
      
* 5.4.3A Channel raster for CA
      For carrier aggregation the channel raster is 100 kHz for all bands, which means that the carrier centre frequency must  
      be an integer multiple of 100 kHz.
      
* 5.4.3F Channel raster for UE category NB1 and NB2
      Channel raster for category NB1 and NB2 in-band, guard-band and standalone operation is 100 kHz.
      
* 5.4.4 Carrier frequency and EARFCN 
      The carrier frequency in the uplink and downlink is designated by the E-UTRA Absolute Radio Frequency Channel
      Number (EARFCN) in the range 0 - 65535. The relation between EARFCN and the carrier frequency in MHz for the
      downlink is given by the following equation, where FDL_low and NOffs-DL are given in Table 5.4.4-1 and NDL is the
      downlink EARFCN.
$$F_{DL} = F_{DL_{low}} + 0.1(N_{DL} – N_{Offs-DL})$$

      The relation between EARFCN and the carrier frequency in MHz for the uplink is given by the following equation
      where FUL_low and NOffs-UL are given in Table 5.4.4-1 and NUL is the uplink EARFCN.
$$F_{UL} = F_{UL_{low}} + 0.1(N_{UL} – N_{Offs-UL})$$

* [Table 5.4.4-1: E-UTRA channel numbers p 251+](https://www.etsi.org/deliver/etsi_ts/136500_136599/13652101/15.05.00_60/ts_13652101v150500p.pdf) 
  * bands n1-n76 (see python converstion code here)[]

* Section **5.4.4F Carrier frequency and EARFCN for category NB1 and NB2** p 254+
* 
    The carrier frequency of category NB1/NB2 in the downlink is designated by the E-UTRA Absolute Radio Frequency
    Channel Number (EARFCN) in the range 0 – 262143 and the Offset of category NB1/NB2 Channel Number to
    EARFCN in the range {-10,-9,-8,-7,-6,-5,-4,-3,-2,-1,-0.5,0,1,2,3,4,5,6,7,8,9}. The relation between EARFCN, Offset of
    category NB1/NB2 Channel Number to EARFCN and the carrier frequency in MHz for the downlink is given by the
    following equation, where FDL is the downlink carrier frequency of category NB1/NB2, FDL_low and NOffs-DL are given in
    table 5.2-1, NDL is the downlink EARFCN, MDL is the Offset of category NB1/NB2 Channel Number to downlink
    EARFCN.

$$F_{DL} = F{DL_{low}} + 0.1(N_{DL} – N_{Offs-DL}) + 0.0025*(2M_{DL}+1)$$

* See section  [5.2 OPERATING Bands p.134+ of ts36.521.01_v15.05](https://www.etsi.org/deliver/etsi_ts/136500_136599/13652101/15.05.00_60/ts_13652101v150500p.pdf)

===========================

![image](https://user-images.githubusercontent.com/8783973/110927120-dc01dd80-82ea-11eb-89cc-ba4deb33d6e4.png)

![]()
![]()
![]()


# Operating Bands NR FR1 (450 MHz -  6,000 MHz      Bands n1 - n86)
* See section  [5.2 OPERATING Bands p.27+ of ts38.521.01_v15.02](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852101/15.02.00_60/ts_13852101v150200p.pdf)
      Freq.Range      Freq Range in MHz          Bands
      - FR1:          450 MHz -  6,000 MHz      n1 - n86
      - FR2:       24,250 MHz - 52,600 MHz
      
![]()
![]()
![]()

* [5.3.2 Maximum transmission bandwidth configuration See p30+](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852101/15.02.00_60/ts_13852101v150200p.pdf)


# Operating Bands NR FR2 (FR2: 24,250 MHz - 52,600 MHz  Bands )
* [5G;NR; User Equipment (UE) conformance specification; Radio transmission and reception; Part 2: Range 2 standalone (3GPP TS 38.521-2 version 15.3.0 Release 15) ](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852102/15.03.00_60/ts_13852102v150300p.pdf)
* See section  [5.2 OPERATING Bands p.27+ of ts38.521.01_v15.02](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852102/15.03.00_60/ts_13852102v150300p.pdf)
      Freq.Range      Freq Range in MHz          Bands
      - FR1:          450 MHz -  6,000 MHz      n1 - n86
      - FR2:       24,250 MHz - 52,600 MHz



# [5G;NR; User Equipment (UE) conformance specification; Radio transmission and reception; Part 2: Range 2 standalone (3GPP TS 38.521-2 version 16.4.0 Release 16)](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852102/16.04.00_60/ts_13852102v160400p.pdf)
* [5 Operating bands and channel arrangement p23+](3GPP TS 38.521-2 version 16.4.0 Release 16)](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852102/16.04.00_60/ts_13852102v160400p.pdf)
      Freq.Range      Freq Range in MHz            Bands
      - FR1:          410 MHz -  7,125 MHz        n1 -  n86
      - FR2:       24,250 MHz - 52,600 MHz      n257 - n261
* [5.2 Operating Bands. Table 5.2-1 NR Oper banbds in FR2  p.24+](3GPP TS 38.521-2 version 16.4.0 Release 16)](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852102/16.04.00_60/ts_13852102v160400p.pdf)
  * Table 5.3A.4-1: CA bandwidth classes p.31      - NR CA bw classes: A-Q
  * 5.5A Configurations for CA p.35+
![]()
![]()
![]()

* [5.3.2 Maximum transmission bandwidth configuration See p30+](https://www.etsi.org/deliver/etsi_ts/138500_138599/13852101/15.02.00_60/ts_13852101v150200p.pdf)

