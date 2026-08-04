# Guilty Devboard Xrd

A dev board for my keyboard, because all the options kinda suck

- Same footprint as Xiao Plus
- As efficient as possible
- Fast battery charging (configurable ~50-700mA) and over(dis)charge protection
- Up to 5V 3A from USB, and 3.3V 1A (including MCU power draw)

![](/assets/pcb-front.png)

![](/assets/pcb-rear.png)

## Note: DRC errors

DRC shows ~50 clearance errors due to the Xiao Plus footprint having pads at and past the edge of the board. That's intentional, ignore those.

## Schematic

Use Kicanvas to see the [schematic](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Faskiiart%2Fguilty-devboard-idk%2Fblob%2Fmain%2FPCB%2Fguilty-devboard-idk.kicad_sch)

## Bill of Materials

|Name                          |Quantity needed|MOQ|Price |Quantity to order|Link                                                                                                           |Total    |
|------------------------------|---------------|---|------|-----------------|---------------------------------------------------------------------------------------------------------------|---------|
|Diodes                        |2              |20 |0.0257|20               |<https://www.lcsc.com/product-detail/C2912031.html>                                                              |0.514    |
|Ferrite bead                  |2              |50 |0.025 |50               |<https://www.lcsc.com/product-detail/C525479.html>                                                               |1.25     |
|MOSFETs                       |1              |10 |0.0434|10               |<https://www.lcsc.com/product-detail/C41355091.html>                                                             |0.434    |
|100nF cap                     |5              |50 |0.0018|50               |<https://www.lcsc.com/product-detail/C2903664.html>                                                              |0.09     |
|4.7uF cap                     |4              |10 |0.0733|10               |<https://www.lcsc.com/product-detail/C335103.html>                                                               |0.733    |
|1pF cap                       |1              |100|0.0024|100              |<https://www.lcsc.com/product-detail/C85894.html>                                                                |0.24     |
|2.2uF cap                     |2              |50 |0.0346|50               |<https://www.lcsc.com/product-detail/C335106.html>                                                               |1.73     |
|10uF cap                      |1              |20 |0.0368|20               |<https://www.lcsc.com/product-detail/C76991.html>                                                                |0.736    |
|1.5pF cap                     |1              |100|0.003 |100              |<https://www.lcsc.com/product-detail/C284990.html>                                                               |0.3      |
|22uF cap                      |2              |5  |0.1522|5                |<https://www.lcsc.com/product-detail/C7432764.html>                                                              |0.761    |
|470nF cap                     |1              |100|0.0057|100              |<https://www.lcsc.com/product-detail/C326573.html>                                                               |0.57     |
|1.2pF cap                     |1              |100|0.0016|100              |<https://www.lcsc.com/product-detail/C22374839.html>                                                             |0.16     |
|3.3nF inductor                |1              |100|0.0073|100              |<https://www.lcsc.com/product-detail/C98045.html>                                                                |0.73     |
|1.5uH inductor                |1              |50 |0.0111|50               |<https://www.lcsc.com/product-detail/C2885839.html>                                                              |0.555    |
|4.7nH inductor                |1              |100|0.0099|100              |<https://www.lcsc.com/product-detail/C86126.html>                                                                |0.99     |
|3.6nH inductor                |1              |20 |0.0322|20               |<https://www.lcsc.com/product-detail/C237447.html>                                                               |0.644    |
|4.7uH inductor                |1              |1  |0.2829|1                |<https://www.lcsc.com/product-detail/C7261423.html>                                                              |0.2829   |
|1nH inductor                  |1              |100|0.0029|100              |<https://www.lcsc.com/product-detail/C46607389.html>                                                             |0.29     |
|5.1k resistor                 |2              |100|0.0007|100              |<https://www.lcsc.com/product-detail/C473460.html>                                                               |0.07     |
|470k resistor                 |1              |100|0.0013|100              |<https://www.lcsc.com/product-detail/C54530578.html>                                                             |0.13     |
|30 ohm resistor               |2              |100|0.0008|100              |<https://www.lcsc.com/product-detail/C320826.html>                                                               |0.08     |
|2k resistor                   |1              |100|0.0021|100              |<https://www.lcsc.com/product-detail/C138107.html>                                                               |0.21     |
|1k resistor                   |1              |100|0.001 |100              |<https://www.lcsc.com/product-detail/C131396.html>                                                               |0.1      |
|806k resistor                 |1              |100|0.0009|100              |<https://www.lcsc.com/product-detail/C474840.html>                                                               |0.09     |
|2M resistor                   |1              |100|0.0006|100              |<https://www.lcsc.com/product-detail/C138106.html>                                                               |0.06     |
|10k resistor                  |1              |100|0.001 |100              |<https://www.lcsc.com/product-detail/C138117.html>                                                               |0.1      |
|220k resistor                 |1              |100|0.003 |100              |<https://www.lcsc.com/product-detail/C142020.html>                                                               |0.3      |
|68k resistor                  |1              |100|0.003 |100              |<https://www.lcsc.com/product-detail/C274345.html>                                                               |0.3      |
|2.2 ohm resistor              |1              |100|0.0037|100              |<https://www.lcsc.com/product-detail/C473517.html>                                                               |0.37     |
|200 ohm resistor              |1              |100|0.0011|100              |<https://www.lcsc.com/product-detail/C304517.html>                                                               |0.11     |
|SGM40567                      |1              |1  |0.53  |1                |<https://www.lcsc.com/product-detail/C5141336.html>                                                              |0.53     |
|FH9261-G3JH                   |1              |20 |0.0289|20               |<https://www.lcsc.com/product-detail/C19273258.html>                                                             |0.578    |
|BD83070GWL-E2                 |1              |1  |0.7198|1                |<https://www.lcsc.com/product-detail/C2071126.html>                                                              |0.7198   |
|32MHz crystal                 |1              |5  |1.0134|1                |<https://www.lcsc.com/product-detail/C5203637.html>                                                              |1.0134   |
|32.768kHz crystal             |1              |1  |3.0197|1                |<https://www.lcsc.com/product-detail/C2595065.html>                                                              |3.0197   |
|                              |               |   |      |                 |                                                                                                               |         |
|NRF54LM20A-QGAA-R             |1              |1  |6.7   |1                |<https://mou.sr/44t4RAm>                                                                                         |6.7      |
|Amphenol 124019772112A (USB-C)|1              |1  |2.41  |1                |<https://www.mouser.com/ProductDetail/Amphenol-Commercial-Products/124019772112A?qs=OlC7AqGiEDmvQ2B4jeqfyg%3D%3D>|2.41     |
|                              |               |   |      |                 |                                                                                                               |         |
|JLCPCB                        |               |   |      |                 |                                                                                                               |$15.10   |
|                              |               |   |      |                 |                                                                                                               |         |
|JLCPCB shipping               |               |   |      |                 |Roughly                                                                                                        |$9.79    |
|LCSC shipping                 |               |   |      |                 |                                                                                                               |7.25     |
|Mouser shipping               |               |   |      |                 |                                                                                                               |8.49     |
|Mouser estimated tariffs      |               |   |      |                 |                                                                                                               |0.24     |
|                              |               |   |      |                 |                                                                                                               |         |
|Subtotal                      |               |   |      |                 |                                                                                                               |68.7708  |
|Total                         |               |   |      |                 |                                                                                                               |74.444391|

## Production notes

The layer stackup should be JLC0616H-3313, and a stencil with electropolishing is recommended.
