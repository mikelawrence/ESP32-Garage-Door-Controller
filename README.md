# ESP32 Garage Door Controller
ESP32 based garage door controller. There are a lot of ESPHome based garage door controller projects on the web. What makes this one unique is the use of a rotary encoder to determine garage door position.

## Status
* Rev A PCB has been ordered and delivered but has NOT been assembled and tested yet.
* v41 of the Printable Box has been designed and tested with a bare PCB.

## PCB
PCB is designed in [KiCad](http://kicad.org) which is a great free EDA toolset

## PCB Preview
<img src="ESP32_Garage_Door_Controller.pdf" style="width:100%">
<img src="meta/ESP32_Garage_Door_Controller_Board.png" style="width:100%">

## PCB Parts List
| Qty   | Reference | Value           | Description                                   | Manufacturer                | Part Number        |
| :---  | :---      | :---            | :---                                          | :---                        | :---               |
| 1     | A1        |                 | Mod, Adafruit Feather ESP32 V2                | Adafruit                    | 5400               |
| 2     | C1, C2    | 1uF             | Cap, Ceramic, 1uF, 10V, 10%, 0805             | Kemet                       | C0805C105K8RACTU   |
| 1     | D1, D2    |                 | IC, High-Speed ESD Protection Device, SOT-553 | TI                          | TPD2E2U06DRLR      |
| 1     | J1        |                 | Conn, USB-C Power Only, SMT                   | GCT                         | USB4135-GF-A       |
| 1     | J2        |                 | Conn, Terminal Strip, 8-Pos, 3.5 mm           | Phoenix Contact             | 1843664            |
| 1     |           |                 | Conn, Terminal Strip, 8-Pos, 3.5 mm (mate)    | Phoenix Contact             | 1863217            |
| 1     | Q1-Q4     |                 | Trans, N-Ch MOSFET, 60V, 300mA, SOT-23        | OnSemi                      | 2N7002K            |
| 1     | R1-R5     | 5.1k            | Res, 5.1k, 100mW, 5%, 0603                    | YAGEO                       | RC0603JR-075K1L    |
| 1     | R6        | 680             | Res, 680, 100mW, 5%, 0603                     | YAGEO                       | RC0603JR-07680RL   |
| 1     | R7-R9     | 4.7k            | Res, 4.7k, 100mW, 5%, 0603                    | YAGEO                       | RC0603JR-074K7L    |
| 1     | R10-R12   | 300             | Res, 300, 100mW, 5%, 0603                     | YAGEO                       | RC0603JR-07300RL   |
| 1     | RL1       |                 | IC, Solid State Relay, 230V, 450mA, SIP       | IXYS                        | CPC1511Y           |

## 3D Box
I used Autodesk Fusion 360 to design a small clamshell box. This box has holes for 10mm X 3mm round magnets which hold the box pretty securely on a metal opener. There are two version of the box. One has two holes in the lid for standard PG0 gland nuts. The other has three holes for gland nuts.

Use M2.5 brass inserts and M2.5X8mm screws to hold the PCB. Use M3 brass inserts and M3x25mm screws to screw the box halves together.

<img src="meta/ESP32_Garage_Door_Controller_Box.png" style="width:100%">

## Code

```yaml
code will be uploaded here eventually
```
