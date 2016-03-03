# About
[![OSHPark PCB Top Thumbnail](artwork/thumb_top.png?raw=true)](artwork/top.png?raw=true)
[![OSHPark PCB Bottom Thumbnail](artwork/thumb_bottom.png?raw=true)](artwork/bottom.png?raw=true)
[![EagleCAD Board Dimensions Thumbnail](artwork/thumb_dimensions.png?raw=true)](artwork/dimensions.png?raw=true)

Custom board used to convert ethernet plug to 4-pin molex connector for the [Galactic Aztec Heavy] rocket. The board was designed to interface with the [Galactic Aztec Heavy Raspberry Pi Add-on: ADC] board.

Custom EagleCAD parts on this board can be found in the [SDSU Rocket Eagle Libraries].

## Wiring
The ethernet port adheres to the following [T-568B] wiring configuration:

| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White |                |
| 2   | Orange       |                |
| 3   | Green/White  |                |
| 4   | Blue         | Supply Voltage |
| 5   | Blue/White   | Supply Voltage |
| 6   | Green        |                |
| 7   | Brown/White  | Ground         |
| 8   | Brown        | Ground         |

# Bill of Materials
| Qty | Name | Description                          | Part Number       | Vendor   |
|:---:|:----:|--------------------------------------|------------------:|----------|
| 1   |      | Jack RJ45 CAT5/CAT5e                 | [380-1046-ND]     | DigiKey  |
| 1   |      | Molex Mini Fit Jr. 4-pos Right Angle | [WM1352-ND]       | DigiKey  |
| 1   | D1   | LED Yellow Vf=1.8V If=2mA 0603       | [475-1196-1-ND]   | DigiKey  |
| 1   | R1   | Resistor 15kΩ 1/4W ±1% 0603          | [RHM15.0KADCT-ND] | DigiKey  |


[Galactic Aztec Heavy]: http://rocket.sdsu.edu/rockets#galactic-aztec-heavy
[Galactic Aztec Heavy Raspberry Pi Add-on: ADC]: https://github.com/twyatt/galactic-aztec-heavy-rpi-addon-adc
[SDSU Rocket Eagle Libraries]: https://github.com/twyatt/SDSURocket-Eagle-Libraries
[T-568B]: https://en.wikipedia.org/wiki/TIA/EIA-568#Wiring
[380-1046-ND]: http://www.digikey.com/product-detail/en/SS-7188-NF/380-1046-ND/388308
[WM1352-ND]: http://www.digikey.com/product-detail/en/0039301040/WM1352-ND/561079
[475-1196-1-ND]: http://www.digikey.com/product-detail/en/LY%20L29K-H1K2-26-Z/475-1196-1-ND/810357
[RHM15.0KADCT-ND]: http://www.digikey.com/product-detail/en/rohm-semiconductor/ESR03EZPF1502/RHM15.0KADCT-ND/1983758
