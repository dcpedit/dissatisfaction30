# Dissatisfaction30 Stacked Acrylic Case (prototype)

<img src="https://user-images.githubusercontent.com/800930/189470515-34997a4e-c0cf-4e6e-b7fe-2e8514231377.jpg" />

This is a tray mount case that still needs a lot of design improvements.  The goal was to hide the case screws by using adhesive to secure to top 2 layers.  You will need the following hardware

## Case
| Position | Size | Quantity | Notes |
| -------- | ---- | -------- | ----- |
| Upper | M2x8mm standoff | 3 |
| Lower | M2x13mm standoffs | 3 |
| Top | M2x8mm screws | 6 |
| Bottom | M2x6mm screws | 6 |
| | 3mm acrylic | 9 layers |
| | Double sided adhesive | 1 | [Link](https://smile.amazon.com/gp/product/B00CCGK31G/)

## PCB Mount
| Position | Size | Quantity |
| -------- | ---- | -------- |
| | M2x6mm standoff | 4 |
| Top | M2x4mm screw | 4 |
| Bottom | M2x3mm screw | 4 |

## Foam & Plate
| Layer Name | Size | Quantity | Notes |
| -------- | ---- | -------- | ----- |
|  a) Plate foam | 1.5mm EVA | 1 | [Link](https://www.aliexpress.com/item/3256804208838525.html?spm=a2g0o.order_list.0.0.61751802IXEFAW) |
|  a) Plate foam | 2mm EVA | 1 |
|  b) Bottom foam | 1.5mm EVA | 1 |
|  c) Plate holes | 1.5mm acrylic | 1 |

## Guide
Use `plate-mount.ai` and cut the 9 layers of acrylic needed for the case (labled `#1` - `#9`).  You will also need to cut 3 layers of EVA foam (see table above for layer name and thickness).  Screw layers `#3` - `#9` together (see case table above for screw/standoff positions).  Do not secure the first two layers yet since they will be held on top by the double-sided adhesive.

<img src="https://user-images.githubusercontent.com/800930/189470548-3faac502-d5f0-44d2-832b-f31da5eeb796.jpg" width="300"/>

Place the 1.5mm bottom foam on the bottom of the case.  Attach the M2x6mm standoffs to the bottom of the PCB using the M2x4mm screws.  Place the PCB with standoffs attached over the bottom foam, and secure the PCB to the case with M2x4mm from the underside of the case. It may seem like the bottom mount holes are too big since the entire spacer fits through, but this was intentional in order reduce space under the PCB.  The intent was for the bottom foam to be just thick enough to keep the screws flush against the case bottom.

<img src="https://user-images.githubusercontent.com/800930/189470561-42219932-8e64-456a-a456-44afedf69faf.jpg" width="300"/>

Place the 2mm and 1.5mm plate foam on top of the PCB, and then the switch plate on top of the 2 layers of foam, making sure the switch holes are lined up.  Push all the switches into the switch plate.  You can put together the PCB + plate foam + plate + switches first, and then place the whole assembly inside the case.

<img src="https://user-images.githubusercontent.com/800930/189470574-80f6a5b0-55e1-4632-96df-4228814d7f6d.jpg" width="300"/>

Cut strips of double-sided adhesive so that they fit around the edges of the layer `#3` and secure layer `#2` on top, making sure it's centered.  Cut more strips of double-sided adhesive and place them around the edges of layer `#2`.  Finally secure the top layer `#1` on top while making sure it's centered.

<img src="https://user-images.githubusercontent.com/800930/189470557-94b365dc-ad13-47d4-a158-2c5cb3e308a8.jpg" width="300"/>
