# TDA1516BQ 12W x 2 Stereo Amplifier

![Prototype build of TDA1516BQ](https://raw.githubusercontent.com/dilshan/tda1516-stereo-power-amplifier/refs/heads/main/resources/tda1516-prototype.jpg)

A simple stereo amplifier built around the classic Philips TDA1516BQ audio amplifier chip. It delivers 12W per channel on a 12V - 14V supply, with the warm, smooth sound of a traditional class AB design.

## Features

- Stereo output, 12W x 2
- 12V - 14V supply (tested with a 12V 5A PSU)
- Small PCB: 62mm x 41mm

## Bill of Materials

| Reference | Value | Qty |
|-----------|-------|-----|
| C1 | [100µF / 25V](https://s.click.aliexpress.com/e/_c3xrOqJD) | 1 |
| C2, C3 | [0.22µF](https://s.click.aliexpress.com/e/_c39Y1Dd1) | 2 |
| C4, C5 | [1000µF / 25V](https://s.click.aliexpress.com/e/_c3CeWXvv) | 2 |
| C6 | [2200µF / 25V](https://s.click.aliexpress.com/e/_c3xxjTBN) | 1 |
| C7 | [0.1µF](https://s.click.aliexpress.com/e/_c39Y1Dd1) | 1 |
| J1, J2, J3, J4, J5 | [5.08mm 2-pin screw terminal](https://s.click.aliexpress.com/e/_c3N5smMT) | 5 |
| RV1 | [B100K potentiometer](https://s.click.aliexpress.com/e/_c3qUNW6J) | 1 |
| U1 | [TDA1516BQ](https://s.click.aliexpress.com/e/_c3Xf7b8X) ([datasheet](https://pdf.datasheetcatalog.com/datasheet/philips/TDA1516.pdf)) | 1 |

The PCB can be ordered directly from [PCBWay](https://www.pcbway.com/project/shareproject/TDA1516BQ_12W_x_2_Stereo_Amplifier_b292c3b0.html).

## Construction notes

The build is straightforward. The only thing that needs care is mounting the heatsink. Large capacitors leave little room for tightening the heatsink screws, so use one of these approaches:

1. Solder the TDA1516BQ first, attach the heatsink, then solder the remaining components.
2. Solder all passive components and connectors first, and solder the TDA1516BQ last with the heatsink already attached.

## Power

Use a 12V supply, rated 5A or more. The amplifier works well and produces good quality audio with a 12V 5A PSU.
