# Dissatisfaction30 PCB

![Dissatisfaction30 - Imgur](https://user-images.githubusercontent.com/800930/187589746-8d064423-baf6-4710-8635-935d9f0d5ee1.jpg)

To get the PCB manufactured, upload `dissat-pcb.zip` to [JLCPCB](https://jlcpcb.com), select your desired PCB color while keeping all the other default options, and place your order (minimum 5).  If you made tweaks to the PCB in KiCad, follow [this tutorial](https://support.jlcpcb.com/article/194-how-to-generate-gerber-and-drill-files-in-kicad-6) to generate new Gerber files

## Requied Components
| Name                   | Qty | Notes |
| ---------              | --- | ----- |
| Elite-C controller     | 1   | Soldered directly onto PCB
| SSD1306 128x32 OLED    | 1   |
| EC11 rotary encoder    | 1   |
| Key switches           | 30  |
| 3u stabalizer          | 1   |
| 2u stabalizer          | 1   |
| OLED header (1x4)      | 1   | [Link](https://www.mouser.com/ProductDetail/517-929850-01-04-RA)
| Kailh hot swap socket  | 30  | [Link](https://www.aliexpress.com/item/2255800865526224.html?spm=a2g0o.order_list.0.0.71e51802oef56x&gatewayAdapt=4itemAdapt)
| BAV70 SMD diode        | 16  | [Link](https://www.digikey.com/en/products/detail/onsemi/BAV70LT3G/1475508)

You will need to sand the OLED header down so that the plastic is about 7mm in height (not including the pins).  Also remove any plastic spacers on the OLED pins, and make sure the pins insert fully into the now shorter header.  If it doesn't sit flush with the OLED PCB, cut the OLED pins a bit shorter until it does.

![dissat30build-7](https://user-images.githubusercontent.com/800930/189470454-2783b242-2c0e-40f9-a2c1-5690e2e030d7.jpg)

It is also possible to replace the Elite-C with a nice!nano for wireless support or a Pro-Micro since the bottom 5 pins are not used.  But the included case design expects the controler to be soldered directly onto the PCB, so using a controller that requires low-profile sockets (I suggest Mill-Max 315-43-112-41-003000) will also require a change to the case to allow for the extra height.  Try cutting out a space below the controller on layer `#8` (similar to layer `#7`)

![dissat30build-9](https://user-images.githubusercontent.com/800930/189470452-f8f0792e-10ee-434f-b5df-a280ca10161f.jpg)

![dissat30build-8](https://user-images.githubusercontent.com/800930/189470446-33380574-48f0-4bad-8a88-e00755b319ba.jpg)
