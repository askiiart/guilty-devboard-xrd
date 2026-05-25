# Guilty Devboard Xrd

A dev board for my keyboard, because all the options kinda suck

- Can be replaced by a stock Xiao w/ IO expander (if the board using it is designed as such)
- Plenty of GPIO (36, designed for easy addition of an IO expander for up to 52)
- Same size as a standard Xiao
- As power efficient as possible
- Reasonably fast battery charging (configurable ~50-700mA) and over(dis)charge protection
- Built-in 5V boost converter

## Schematic

Use Kicanvas to see the [schematic](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Faskiiart%2Fguilty-devboard-idk%2Fblob%2Fmain%2FPCB%2Fguilty-devboard-idk.kicad_sch)


## Parts

- [nrf54lm20a](https://www.mouser.com/ProductDetail/Nordic-Semiconductor/nRF54LM20A-PAAA-R)
- [antenna - 2450AT18A100E](https://www.lcsc.com/product-detail/C89334.html)
- [high current diodes - BAT60B](https://www.lcsc.com/product-detail/C7502695.html)
- [low current diodes - TPB4010ESB](https://www.lcsc.com/product-detail/C907849.html)
- [ferrite beads - BLM15PD121SN1D](https://www.lcsc.com/product-detail/C76891.html)
- [MOSFETs for battery overcharge/discharge](https://www.lcsc.com/product-detail/C41355091.html)
- [single MOSFET for boost converter on/off](https://www.lcsc.com/product-detail/C144959.html)
- [reset button](https://www.lcsc.com/product-detail/C720477.html)
- [usb-c](https://www.mouser.com/ProductDetail/Amphenol/124019772112A?qs=OlC7AqGiEDmvQ2B4jeqfyg%3D%3D)
  - specifically this because it has a very small footprint on the board
- []