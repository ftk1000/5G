2020.03.29

## OFDMA/OFDMA/SC-FDMA

[2020: Iain: OFDM Waveforms](https://www.youtube.com/watch?v=F6B4Kyj2rLw)<br>

[2016: 2.3 - OFDM/ OFDMA IN 4G LTE - PART 1](https://www.youtube.com/watch?v=rKy5dOl3Et4)<br>

[]()<br>

## LTE



| ch BW    | usable BW (UBW)| UBW in SubCarriers | UBW in RBs   | Msmt Window Sz     | Wnd sz in raster Freqs  |
|:---:     |:---:           |:---:               |:---:         |:---:               | :---:                   |
|  1.4 MHz |1.08  MHz|   72       |   6   |  1.1 MHz|   11       |
|  3  MHz  | 2.7  MHz|   180      |  15   |  2.7 MHz|   27       |
|  5  MHz  | 4.5  MHz|   300      |  25   |  4.5 MHz|   45       |
|  10  MHz | 9  MHz  |   600      |  50   |  9.1 MHz|   91       |
|  15  MHz |13.5  MHz|   900      |  75   | 13.5 MHz|  135       |
|  20  MHz | 18   MHz|  1200      | 100   | 18.1 MHz|  181       |

    RB = (12 subcarriers=180 KHz) x (7 symbols = 1 Slot = 0.5 msec)   =   180 kHz x 0.5 msec
    RE = 1 subcarrier x 1 symbol = 15 kHz x (0.5/7=0.0714) ms
    RB = 84 REs

## Power Control

[sharetechnote: LTE Power Control](https://www.sharetechnote.com/html/PowerControl_LTE.html)<br>
[Blog: http://www.techtrained.com/lte-power-control/](http://www.techtrained.com/lte-power-control/)<br>

    Downlink Power Control
        In case of 4G DL, rather than varying power in the Downlink, full power is distributed uniformly over the whole bandwidth. 
        The same Power Spectral Density (PSD) is used on all DL channels. 
        For example, PDSCH, PHICH, PDCCH etc. PSD is the power of a signal divided by Bandwidth (PSD = Power / Bandwidth). 
        In case of PSD, it is normalized to one resource block. Note: There are certain channels in DL, where power is varied accordingly. 
    UL PC - In contrast to DL, in Uplink in LTE, Power control is used mainly for the following two reasons.
        limit intracell and intercell interference
        reduce UE power consumption
    Usually in UL PC is done in two ways: Conventional Power Control, and Fractional Power control.        
        
[2018:  Hassan Atique: LTE DL Power Allocation](https://www.youtube.com/watch?v=gwJU5TvMivk)<br>
[2017: Irfan Ali: LTE Radio Primer Part 7: DL Cell Reference Signals, RSRP & RSRQ](https://www.youtube.com/watch?v=XAtQq7zHvQ0)<br>

    4/84 REs are used for Reference Signal (==> RSRP)
        Cell Reference Singals (CRS) are carried in two symbols: 0 and 4 (or 1st and 5th) and
        CRS subcarriers are determined by Physycal Layer Cell Idenitty (PCI) of the cell (UE figures PCI from PSS and SSS)
        
    UE measures RSRP = avg power in watts received by a single Reference Signal (RS) RE
        RSRP measures only RS power and excludes all noise and interference: RSRP = {1/K}\Sum_{k=1}^K P_{rs,k}
        P_{rs,k} is the estimated RX power (in W) by the k-th RS RE
        
    Typically CRS (REs with RS) are TXed at much higher power than other REs
        max RSRP ~ max input to UE = -25 dBm = 0.0032 mW
            in 1.4 MHz BW w/ 6 RBs (72 REs) max RSRP = -44 dBm
        min RSRP  = -140 dBm (has 6 dBm margin over the min RX power @ UE)
        
    Knowledge of absolute RSRP allows the UE to calculate DL PL
    
    RRSI (Received Signal Strength Indicator) = measured only in OFDM symbols containing the RSs
        Example: in 1.4 MHz case (w/ 6 RBs), RSSI is measured and added over all 6 RBs for the 1st symbol (or the 5th symbol)
        
    RSRQ (Reference Signal Received Quality) = RSRP/(RSSI/N_{RB})
        RSRQ is important for scheduling for UE at cell edge and Hand-over decisions
        max RSRQ = -3 dB (one RS RE has 50% of the total power per symbol)
        min RSRQ = -19.5 dB (one RS RE has only 1% energy in RB)
    
    
    
[2017: Irfan Ali: LTE Radio Primer Part 8: DL Summary & References  -  OFDM in Multicolor](https://youtu.be/AdwWBls_VW0?t=50)<br>
[]()<br>



## 5G  

[5G Network Architecture White Paper v1.0 12-08-2018](http://www.gtigroup.org/d/file/Resources/rep/2018-02-22/06608ce6dbe32673ac1611359e11f794.pdf)

[5G K-Sim](http://5gopenplatform.org)

[5G K-SimLink](http://5gopenplatform.org/main/main.php?categoryid=06&menuid=01&groupid=00)

[5G tutorial from MathWorks](http://5gopenplatform.org/main/main.php?categoryid=06&menuid=01&groupid=00)



moz a loc service. [MAP](https://location.services.mozilla.com/map#2/35.0/9.0).  ----- [STATS](https://location.services.mozilla.com/stats)
------  [REGIONS](https://location.services.mozilla.com/stats/regions)<br>
[]()<br>
[]()<br>
[]()<br>
[]()<br>
[]()<br>
[]()<br>
[]()<br>
