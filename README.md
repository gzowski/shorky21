# Shorky21 - Rev 1

21 key macro pad with twin rotary encoders
![Shorky21-rev1](https://github.com/gzowski/shorky21/blob/main/images/lights.jpg)

PCB available for purchase via my Etsy page: "when i add it"

Thanks again to PCBWay who made yet another of my projects a possibility, I will soon be providing further images relating to the build but for now this will have to do.
PCBWay provided all 3 plates which make up the macropad.

## Features
* 21 Key layout
* 2 rotary encoders
* Per key LED's for centre arrow keys
* Wireless with ZMK
* Nice Nano or equivilent micro controller
* Firmware available here: https://github.com/gzowski/shorky21-shield-module/actions/runs/15693301024

## Parts

| Part | Quantity     | Description                |
| :-------- | :------- | :------------------------- |
| Diodes | 23 | SMD 1N4148W |
| Microcontroller | 1 | NiceNano |
| Switches | 21 | MX switches, 5 pin |
| EC11 | 2 | Rotary Encoders |
| Keycaps | 19 | 1u keycaps |
| Keycaps | 2 | 2u keycaps |
| Stabalisers | 2 | 2u screw mounted stabalisers |
| LED Diodes | 4 |  SK6812 MINI-E |
| M2 Standoff | 4 | M2x10mm |
| M2 Screws | 8 | M2x6mm |
| PTS526 | 1 | Reset button |
| 2P JST PH plug | 1 | socket for battery |
| 1200mAh battery | 1 | battery with 2P JST connector |
| PCM12SMTR | 1 | Power switch (Optional) |

## Build Guide

1. Solder the micro controller to the top of the PCB facing down (components underneath).
2. Solder the diodes to the back of the board, noting the orientation of each diode ->|-
3. Solder on the 2P JST socket on the pack, recommend snipping pins shorter so they do not stick through the top of the PCB so far.
4. Solder the reset switch onto the back
5. Solder the PCM12SMTR power switch on (if applicable), you can join the traces for switch bypass if not using a power switch.
6. Solder in each of the LED's if using LED's
7. Turn the PCB over, insert both of the screw mounted stabalisers and screw in from the underside
7. Insert each of the MX switches into the top PCB plate, ensure correct orientation.
8. Place the switch top plate and switches onto the middle PCB, turn the PCB back over and solder each of the switches in, ensure each switch is pushed down flush with the PCB.
9. Turn back over and now insert both of the EC11 rotary encoders, this is a tight squeeze but does fit.
10. Turn back over again and solder each of the encoders in place.
11. Connect up the battery if applicable to the 2P socket (Double sided tape helps hold in place)
12. Sandwich all PCB's held together with the M2 standoffs and screws.
