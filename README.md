# Guilty Devboard Xrd

A dev board for my keyboard, because all the options kinda suck

- Same footprint as Xiao Plus
- As efficient as possible
- Fast battery charging (configurable ~50-700mA) and over(dis)charge protection
- Up to 5V 3A from USB, and 3.3V 1A (including MCU power draw)

## Note: DRC errors

DRC shows ~50 clearance errors due to the Xiao Plus footprint having

## Schematic

Use Kicanvas to see the [schematic](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Faskiiart%2Fguilty-devboard-idk%2Fblob%2Fmain%2FPCB%2Fguilty-devboard-idk.kicad_sch)

## Parts

- [nrf54lm20a](https://www.mouser.com/ProductDetail/Nordic-Semiconductor/nRF54LM20A-PAAA-R)
- [antenna - 2450AT18A100E](https://www.lcsc.com/product-detail/C89334.html)
- [low current diodes - TPB4010ESB](https://www.lcsc.com/product-detail/C907849.html)
- [ferrite beads - BLM15PD121SN1D](https://www.lcsc.com/product-detail/C76891.html)
- [MOSFETs for battery overcharge/discharge](https://www.lcsc.com/product-detail/C41355091.html)
- [usb-c](https://www.mouser.com/ProductDetail/Amphenol/124019772112A?qs=OlC7AqGiEDmvQ2B4jeqfyg%3D%3D)
  - specifically this because it has a very small footprint on the board
- [buck-boost converter (for 3.3V)](https://www.lcsc.com/product-detail/C2071126.html)
