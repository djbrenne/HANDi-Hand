![](RackMultipart20200724-4-1dqkhfm_html_b76c69e8dcd0da40.png)

# Assembly Manual

Dylan Brenneis

July 2017

James Austin

Updated December 2017

![](RackMultipart20200724-4-1dqkhfm_html_689d1e323dc93bad.jpg) ![](RackMultipart20200724-4-1dqkhfm_html_ef8c7987917a965d.jpg) ![](RackMultipart20200724-4-1dqkhfm_html_974bb3794b0a0f31.png) ![](RackMultipart20200724-4-1dqkhfm_html_48ec43940872c090.png) ![](RackMultipart20200724-4-1dqkhfm_html_43d953ad9126584e.png)

Contents

[Table of Figures ii](#_heading=h.gjdgxs)

[1](#_heading=h.30j0zll)Introduction 2

[2](#_heading=h.1fob9te)Naming and Definitions 1

[2.1 Digits 1](#_heading=h.3znysh7)

[2.2 Joints 1](#_heading=h.2et92p0)

[2.3 Finger Parts 1](#_heading=h.tyjcwt)

[3](#_heading=h.3dy6vkm)Required Materials 2

[3.1 3D Printed Parts 2](#_heading=h.1t3h5sf)

[3.2 Ordered Parts 3](#_heading=h.2s8eyo1)

[3.3 Tools 5](#_heading=h.17dp8vu)

[4](#_heading=h.3rdcrjn)Assembly Flowchart 5

[5](#_heading=h.26in1rg)Material Preparation 6

[5.1 3D Printed Parts (17h 0m) 6](#_heading=h.lnxbz9)

[5.2 Potentiometers (1h 45m) 7](#_heading=h.35nkun2)

[5.3 FSRs (1h 0m) 8](#_heading=h.44sinio)

[5.3.1](#_heading=h.2jxsxqh) Fingertips 9

[5.4 Screws (0h 45m) 9](#_heading=h.z337ya)

[6](#_heading=h.1y810tw)Thumb Assembly (1h 0m) 10

[6.1 Part Assembly 10](#_heading=h.4i7ojhp)

[6.2 Optional: Adductible Thumb Assembly 11](#_heading=h.2xcytpi)

[6.3 Mounting to Palm 13](#_heading=h.2bn6wsx)

[7](#_heading=h.qsh70q)Finger Assembly (0h 15m each finger) 13

[8](#_heading=h.3as4poj)Servo Installation and Finger Tensioning (0h 7m each finger) 12

[9](#_heading=h.1pxezwc)Breadboard Hub (3h 0m) 14

[10](#_heading=h.2p2csry)Aluminum Servo Cover (0h 45m) 17

[11](#_heading=h.147n2zr)Ventral Palm Cover; USB Webcam (0h 20m) 17

[12](#_heading=h.3o7alnk)Palm Grips (1h 15m) 18

[13](#_heading=h.23ckvvd)Wiring (1h 0m) 19

[13.1 Testing 19](#_heading=h.ihv636)

[13.2 Full Implementation 20](#_heading=h.32hioqz)

[14](#_heading=h.41mghml)Appendix A: Grip Pattern Template I

[15](#_heading=h.2grqrue)Appendix B: Servo Cover Template 3

# Table of Figures

[Figure 1: Digit numbering](about:blank)1

[Figure 2: Joint names](about:blank)1

[Figure 3: Example part naming convention](about:blank)1

[Figure 4: Dorsal Palm post processing](about:blank)7

[Figure 5: Sanding locations for finger joints](about:blank)7

[Figure 6: Filing of DP - D Lock](about:blank)7

[Figure 7: Potentiometer polarity](about:blank)8

[Figure 8: Finished potentiometers](about:blank)8

[Figure 9: Fingertip assembly diagram](about:blank)9

[Figure 10: Finished fingertip without grip pads](about:blank)9

[Figure 11: Thumb assembly diagram](about:blank)10

[Figure 12: Assembled thumb prior to MC - P Geared Rotator installation, showing servo position](about:blank)10

[Figure 13: Adductible thumb assembly diagram](#_heading=h.111kx3o) **Error! Bookmark not defined.**

[Figure 14: Thumb mounted to dorsal palm](about:blank)13

[Figure 15: Index finger (D2) assembly diagram](about:blank)13

[Figure 16: Full Forward Position of servo](about:blank)12

[Figure 17: Zip-tie installed in servo spool](about:blank)12

[Figure 18: Servo spool installation on servo](about:blank)13

[Figure 19: Required cut for zip-tie](about:blank)13

[Figure 20: Servo installation and finger tensioning complete, showing servo positions for right and left hand](about:blank)13

[Figure 21: Breadboard clips salvaged from mini breadboard, cut and soldered as necessary](about:blank)14

[Figure 22: Prototyping wire soldered to individual breadboard clip](about:blank)14

[Figure 23: Soldered connections](about:blank)14

[Figure 24: Molex connector configurations](about:blank)15

[Figure 25: Breadboard orientation on hub](about:blank)15

[Figure 26: Finished soldered connections for breadboard hub, top and front view](about:blank)15

[Figure 27: Finished breadboard hub](about:blank)16

[Figure 28: Pinout for breadboard hub. Breadboard holes to the left of the green line correspond to sensor signal connections; holes to the right correspond to servo motor command signals. Use this diagram as a reference when connecting the wiring to ensure proper connection.](about:blank)16

[Figure 29: Installation of aluminum servo covers (left hand)](about:blank)17

[Figure 30: USB Webcam installed in ventral palm (right hand)](about:blank)17

[Figure 31: Grip diagram](about:blank)18

[Figure 32: Test Setup Wiring](about:blank)19

[Figure 33: Full wiring diagram for individual finger potentiometer control](about:blank)20

[Figure 34: Full wiring diagram](about:blank)21

1.
# Introduction

The HANDi Hand was designed as an open-source robotic platform specifically designed for machine learning research. The inexpensive and easily modifiable design allows versatility for research studies, and the suite of sensors provides valuable information for machine learning and prosthetics research.

The open-source release provides all solid-modelling files, .stl files, Arduino code, and assembly instruction required to construct a fully functional HANDi Hand, and should also give the maker enough flexibility to make alterations to the design as necessary to suit their own needs. Both left and right hand versions are available. To contact the original designers, or to receive support for your build, please visit BLINCdev.ca.

This assembly manual outlines all the information required to print and source parts, and assemble the HANDi Hand as currently designed. The hand takes an estimated 30 hours to build.

1.
# Naming and Definitions

This section outlines the naming conventions for the various parts of the hand.

 ![](RackMultipart20200724-4-1dqkhfm_html_5aa95e7dad2d365a.gif)

  1.
## Digits

The digits are referred to by standard numbering, beginning with the thumb as D1 (See Figure 1).

  1.
## Joints

![](RackMultipart20200724-4-1dqkhfm_html_e6dcc6d5c4ee990.gif) ![](RackMultipart20200724-4-1dqkhfm_html_3658d6b9492ebb3f.gif)

D1A

The joints are named in accordance with Figure 2. The names are constructed first with a digit indicator (i.e. D2) followed by a joint indicator D, I or P, indicating distal, intermediate, or proximal respectively. Potentiometers are named for the joints that they measure. The digit D0 refers to thumb rotation. The digit D1A refers to thumb adduction if implementing the Adductible Thumb option.

  1.
## Finger Parts

Each phalanx of the finger is made up of multiple parts. The parts are named with convention in Figure 3:

![](RackMultipart20200724-4-1dqkhfm_html_fdafa7d307257227.gif)

1: Phalanx indicator. PP = Proximal Phalanx, IP = Intermediate Phalanx, DP = Distal Phalanx, MC = Metacarpal

2: Part position indicator. P = Proximal, D = Distal

3: Position modifier. There are sometimes multiple parts in the same location that must be differentiated by their function (pivot, main, lock, tip, etc).

4: Handedness indicator. R = Right Hand, L = Left Hand

1.
# Required Materials

  1.
## 3D Printed Parts

The 3D printed parts are designed to be printed in PLA without support material and without rafts, except where indicated. Parts are designed for the print tolerance of a MakerBot Replicator 2. Some filing may be necessary to ensure a smooth running fit between parts.

All files required for 3D printing can be accessed via BLINCdev.ca. The suggested print specifications for each part are found in Table 1. The table lists all of the part sets that must be printed for a complete hand. In the event that a particular component is needed, the individual STL files can be found on blincdev.ca in addition to the grouped parts in Table 1.

To determine whether to print &quot;Full Thumb&quot; or &quot;Full Add Thumb&quot;, see Section 6.2

_Table 1: 3D printed parts_

| **Part Name** | **Print Specifications** | **Estimated Print Time** | **Est. Material Weight** |
| --- | --- | --- | --- |
| Dorsal Palm | 0.2 mm layer, 10% infill Print with raft | 6h 0m | 64 g |
| Ventral Palm | 0.2 mm layer, 10% infill | 1h 55m | 22 g |
| Thumb Screw Cap | 0.2 mm layer, 10% infill | 0h 15m | 2 g |
| D2 Full Finger | 0.2 mm layer, 10% infill | 1h 10m | 9 g |
| D3 Full Finger | 0.2 mm layer, 10% infill | 1h 10m | 9 g |
| D4 Full Finger | 0.2 mm layer, 10% infill | 1h 10m | 9 g |
| D5 Full Finger | 0.2 mm layer, 10% infill | 1h 10m | 9 g |
| Full Thumb | 0.2 mm layer, 10% infill | 2h 30m | 25 g |
| Full Add Thumb | 0.2 mm layer, 10% infill | 3h 00m | 33 g |
| Breadboard | 0.1 mm layer, 10% infill | 0h 25m | 3 g |
| Connector Hub | 0.2 mm layer, 10% infill | 0h 15m | 3 g |
| Pot Activator Set of 15 | 0.1 mm layer, 10% infill | 0h 10m | 1 g |
| Pot Placeholder Set of 6 | 0.2 mm layer, 10% infill | 0h 10m | 2 g |
| Servo Spool Full Set | 0.1 mm layer, 10% infill | 0h 25m | 4 g |
| Servo Spur Gear | 0.1 mm layer, 10% infill | 0h 5m | 1 g |
|
 | **TOTAL:** | 16h 50m | 163 g |

  1.
## Ordered Parts

The table below contains all the items (excluding tools) required for building a complete HANDi Hand.

_Table 2: Parts for ordering_

| **Item** | **Description** | **Vendor** | **Part No.** | **Link** | **QTY** | **Cost/**** Item **|** Ext. Cost **|** Curr. **|** Notes** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SENSORS/ELECTRONICS |
| Sensor Rotary Position SMD | Rotary Position Sensor, muRata Electronics | Digi-Key | 490-14859-1-ND (Digi-Key)

SV03A103AEA01R00 (MFG)
 | https://www.digikey.ca/product-detail/en/murata-electronics-north-america/SV03A103AEA01R00/490-14859-1-ND/6623608 | 9\* | $1.71 | $15.39 | CAD | Quantity is 10 if implementing the Adductible Thumb option. |
| 400 Short Tail with solder tabs | FSR 400 (force sensitive resistor) with short tail and solder tabs | Digi-Key | 1027-1014-ND (Digi-Key)

34-00004 (MFG) | https://www.digikey.ca/product-detail/en/interlink-electronics/34-00004/1027-1014-ND/2798665 | 5 | $15.46 | $77.30 | CAD |   |
| Arduino Mega | Board MCU MEGA2560 | Digi-Key | 1050-1018-ND | https://www.digikey.ca/product-detail/en/A000067/1050-1018-ND/2639006 | 1 | $50.38 | $50.38 | CAD |   |
| Wall Adapter | AC/DC Wall Mount Adapter 5V 18W | Digi-Key | Q976-ND (Digi-Key)

QAWA-18-5-US01(MFG)
 | https://www.digikey.ca/product-detail/en/qualtek/QAWA-18-5-US01/Q976-ND/6412294 | 2 | $21.14 | $42.28 | CAD |   |
| 100 kOhm Resistor | RES 100K Ohm 1/4 Watt, 5% Axial | Digi-Key | 10KEBK-ND (Digi-Key)CFR16J100K (MFG) | https://www.digikey.ca/product-detail/en/1623927-1/A105979CT-ND/3477574 | 5 | $0.15 | $0.75 | CAD |   |
| DC Barrel Jack Adapter - Female | Barrel Jack adapter | Sparkfun | PRT-10288 | https://www.sparkfun.com/products/10288 | 1 | $2.95 | $2.95 | USD |   |
| Break Away Headers - Straight | Conn Header .100&quot; SNGL STR 40 POS | Digi-Key | S1011EC-40-ND (Digi-Key)PRPC040SAAN-RC (MFG) | https://www.digikey.ca/products/en?keywords=S1011EC-40-ND | 2 | $1.04 | $2.08 | CAN |
 |
| Breadboard | Miniature Breadboard | Sparkfun | PRT-12043 | https://www.sparkfun.com/products/12043 | 1 | $3.95 | $3.95 | USD | Only the metal connectors are required for assembly; any breadboard will do. See Section 9 |
| Molex Receptacle Housing | 4POS 2MM Sherlock | Digi-Key | WM5983-ND (Digi-Key)0355070400 (MFG) | https://www.digikey.ca/products/en?keywords=WM5983-ND | 2 | $0.24 | $0.48 | CAN |   |
| Molex Receptacle Housing | 6POS 2MM Sherlock | Digi-Key | WM5985-ND (Digi-Key)0355070600 (MFG) | https://www.digikey.ca/products/en?keywords=WM5985-ND | 2 | $0.28 | $0.56 | CAN |   |
| Molex Header | 4POS 2MM Vert Tin Sherlock | Digi-Key | WM18922-ND (Digi-Key)3562-0450 (MFG) | https://www.digikey.ca/products/en?keywords=WM18922-ND | 2 | $0.47 | $0.94 | CAN |   |
| Molex Header | 6POS 2MM Vert Tin Sherlock | Digi-Key | WM18924-ND (Digi-Key)0353620650 (MFG) | https://www.digikey.ca/products/en?keywords=WM18924-ND%20 | 2 | $0.61 | $1.22 | CAN |   |
| Terminal contact | CONN TERM FEMALE 24-30 AWG TIN | Digi-Key | WM6050-ND (Digi-Key)0502128100 (MFG) | https://www.digikey.ca/products/en?vendor=0&amp;keywords=50212-8100 | 20 | $0.375 | $7.50 | CAD |   |
| Molex Receptacle Housing | Mini SPOX 2POS 2.5MM SHROUD | Digi-Key | WM18873-ND (Digi-Key)0050375023 (MFG) | https://www.digikey.ca/products/en?vendor=0&amp;keywords=50375023 | 2 | $0.30 | $0.60 | CAD |   |
| Molex Header | Mini SPOX 2POS 2.5MM Vert Tin | Digi-Key | WM18886-ND (Digi-Key)0022035025 (MFG) | https://www.digikey.ca/products/en?vendor=0&amp;keywords=22035025 | 2 | $0.68 | $1.36 | CAD |   |
| Terminal contact | CONN TERM FEMALE 22-28 AWG CRIMP | Digi-Key | WM17406-ND (Digi-Key)0008701040 | https://www.digikey.ca/products/en?x=0&amp;y=0&amp;lang=en&amp;site=ca&amp;KeyWords=08701040 | 4 | $0.33 | $1.32 | CAD |   |
| Heat Shrink Tubing | Assorted Heat Shrink Tubing | Sparkfun | PRT-09353 | https://www.sparkfun.com/products/9353 | 1 | $7.95 | $7.95 | USD | Red, black, and yellow 1.5mm diameter required for assembly, approximately 2-3 pieces of each |
| Logitech Quick-Cam Pro | Clip-on USB Webcam | Amazon | N/A | https://www.amazon.ca/Logitech-QuickCam-Pro-for-Notebooks/dp/B000RZNI4S | 1 | $203.16 | $203.16 | CAD |  \*See note below. |
| Hitec HS 35HD Servo | Ultra-Nano Analog servo, 180 degree rotation | Sparkfun | ROB-11882 | https://www.sparkfun.com/products/11882 | 6 | $24.95 | $149.70 | USD |   |
| MATERIALS |
| Medium-Strength Textured Neoprene Rubber | Adhesive Back, 1/32&quot; thick, 12&quot;x12&quot;, 40A Durometer Hardness | McMaster-Carr | 8445K61 | https://www.mcmaster.com/#8445k61/=18l0h88 | 1 | $11.08 | $11.08 | USD | Approximately 2000 mm^2 needed for assembly |
| Easy-to-Weld Corrosion-Resistant 5052 Aluminum | Sheet, 0.080&quot; Thick, 6&quot; x 6&quot; | McMaster-Carr | 88895K105 | https://www.mcmaster.com/#88895k105/=18l0irl | 1 | $5.78 | $5.78 | USD |   |
| HARDWARE/MISCELLANEOUS |
| Continuous-Flex Wire | 26-gauge continuous flex wire, 50&#39;, Black | McMaster-Carr | 7071K19 | https://www.mcmaster.com/#7071k19/=18l0k9k | 50 | $1.20 | $60.00 | USD | Approximately 50&#39; needed for in-hand wiring, 50&#39; for hand-arm wiring |
| Metric Cheese Head Slotted Machine Screw | 18-8 Stainless Steel, M2 Size, 25 mm Length, .4mm Pitch, Pack of 50 | McMaster-Carr | 91800A023 | https://www.mcmaster.com/#91800a023/=18l0ku6 | 1 | $7.45 | $7.45 | USD | 16 needed for assembly, 14 of which are cut to size as in Section 5.4 2 additional cut screws needed if implementing the Adductible Thumb option. |
| Loctite Instant-Bonding Adhesive | #404, 0.3 oz Bottle | McMaster-Carr | 7569A22 | https://www.mcmaster.com/#7569a22/=18l0vy5 | 1 | $27.37 | $27.37 | USD |  Any super-glue will work. |
| Type 18-8 Stainless Steel Flat Washer | M2.5 Screw Size, 2.2mm ID, 5.0mm OD, Pack of 100 | McMaster-Carr | 93475A195 | https://www.mcmaster.com/?error\_redirect=true%20-%2093475a196/=x3cpi7#93475a195/=18l0xfy | 1 | $1.06 | $1.06 | USD | 16 needed for assembly |
| Cable Tie | CBL TIE Locking NAT 18LB 5.9&quot; | Digi-Key | Q731-ND (Digi-Key)17-M150N-C | https://www.digikey.ca/products/en?keywords=Q731-ND | 100 | $0.084 | $8.40 | CAD | 9 needed for assembly |
| **TOTAL:** | **$760.33**
 | CAD | Delivery costs not included. Currency conversion of 1 CAD = 0.80 USD |

\* This is the camera the hand is currently designed for. Cheaper cameras could work just as well with a little re-designing of the mounts on the ventral palm.

  1.
## Tools

The following tools are required to create a HANDi Hand:

      - 3D printer (MakerBot Replicator 2 suggested)
- Dremel tool with sanding wheel
- 120 grit sandpaper
- Small files
- Narrow flat screwdriver
- #0 Philips screwdriver
- Tin snips
- Large flat metal file
- Wire strippers
- Soldering iron and solder
- Heat gun
- Hobby knife
- Fine tweezers
- Needlenose pliers
- Wire cutter

1.
# Assembly Flowchart

A particular order of operations must be followed when assembling the hand, and is outlined in the following flowchart. A process described in any bubble cannot be completed until all items attached to incoming arrows have been completed.

![](RackMultipart20200724-4-1dqkhfm_html_6e7f1784de9b6674.png)

1.
# Material Preparation

  1.
## 3D Printed Parts (17h 0m)

Print parts as specified in section 3.1 The parts are designed to involve as little post-processing as possible; however a few things should be done.

1. Dorsal Palm: Remove print supports using needlenose pliers, then sand smooth using dremel tool with sanding wheel. See Figure 4. The inside faces of the connections with the fingers should also be sanded using 120 grit sandpaper, to ensure a smooth running fit.
 ![](RackMultipart20200724-4-1dqkhfm_html_9bdb20336fb8b913.gif)

| _(a) As printed_ | _(b) Supports removed with pliers_ | _(c) Smoothed with dremel tool_ |
| --- | --- | --- |

 ![](RackMultipart20200724-4-1dqkhfm_html_105e89fdd5be73c1.gif)
1. Finger Joints: The outside faces of all XP – P Main and XP – P Pivot parts, as well as the inside faces of all XP – D parts should be sanded lightly with 120 grit sandpaper to ensure a smooth running fit between the parts. Figure 5 shows the locations that need to be sanded for the intermediate joint of the fingers. Proximal and distal joints will also need to be sanded. It is best to install the pivot parts in the main parts prior to sanding. Any surfaces that will be glued should also be sanded; refer to Figure 11 and Figure 15. ![](RackMultipart20200724-4-1dqkhfm_html_f2cc77762bc0dc6a.gif)
2. Fingertip Locks: the locking wings on all DP – D Lock parts should be filed slightly using a small semi-rounded file. The goal is to have them twist into a locked position with the DP – P Main parts. They should therefore be filed such that the twisting motion is possible, but sufficient friction still exists to keep the fingertips in the locked position.
3. Breadboard and Connector Hub: the holes in these parts will likely be partially occluded by the 3D printed plastic. It is recommended that these holes be drilled out after printing using a .95 mm drill bit.

  1.
## Potentiometers (1h 45m)

In the current version, there are 9 potentiometers (limited due to the number of analog input pins on the Arduino Mega); the Adductible Thumb options uses one additional potentiometer. The suggested lengths of the connecting wires are found in Table 3:

![](RackMultipart20200724-4-1dqkhfm_html_f0fa20ba94c50636.gif)_Table 3: Suggested wire lengths for potentiometers_

| Potentiometer ID | Suggested Wire Length |
| --- | --- |
| D0 | 150 mm |
| D1A | 150 mm |
| D1P | 150 mm |
| D1D | 190 mm |
| D2P | 150 mm |
| D2I | 190 mm |
| D3P | 150 mm |
| D3I | 190 mm |
| D4P | 150 mm |
| D5P | 150 mm |

1. Cut off the top lone pin on the potentiometer as short as possible.
2. Solder the wires to the potentiometer and a straight pin header to the other end of each wire. See note below about D0.
3. Use black heat-shrink on the connections near the potentiometer, and coloured heat shrink on the far connections corresponding to the polarity noted in Figure 7.
4. Heat shrink the 3 wires together near the loose end using a light coloured heat shrink tubing. Label the wires here with the potentiometer ID.

![](RackMultipart20200724-4-1dqkhfm_html_ac53a90ef7672ea2.gif)
**Note:** the straight pin headers for the D0 potentiometer must be soldered to the wires _after_ the potentiometer is installed in MC – Geared Rotator, and the wires routed through the narrow channel. Black heat-shrink tubing near the potentiometer will not fit in this channel, so it is omitted. Figure 8 shows finished D0 and D3I potentiometers.

  1.
## FSRs (1h 0m)

Each fingertip requires an FSR. The recommended wire length for finger FSRs is 250 mm; for the thumb FSR 200 mm is recommended.

1. Solder each wire to the solder tabs of the FSR.
2. Install FSR in fingertip (see 5.3.1 ).
3. Use black heat-shrink tubing on the connections near the FSR.
4. Solder the wires to straight pin headers.
5. Use yellow and red heat shrink tubing on the connections with the straight pin headers.
6. Heat shrink the two wires together using a light coloured heat shrink, and label the wires here with the ID of the finger they represent.
 ![](RackMultipart20200724-4-1dqkhfm_html_6a2a3914d94a96f6.gif)

    1.
### Fingertips

The fingertips should be assembled as per Figure 9. Use superglue on the surfaces marked in yellow. **It is imperative that no glue should contact the FSR Actuator or the FSR itself** ; it should move freely inside the fingertip. The finished fingertip is shown in Figure 10.

1. DP – D Tip
2. DP – D Main
3. DP – D FSR Actuator
4. FSR400 Short Tail resistor
5. DP – D Lock

![](RackMultipart20200724-4-1dqkhfm_html_60242796d83c49c5.gif)

It is recommended that fingertip grip pads be cut from the neoprene rubber sheet (See section 12 ). Be careful when gluing the rubber to the fingertip that the movement of the FSR actuator does not become restricted in any way.

  1.
## Screws (0h 45m)

The screws used as hinges in each of the finger joints are required to be cut to length from the 25 mm M2 screws. The lengths of the various screws can be referenced from Table 4. The screws should be cut to length in a manner such that the threads are preserved.

_Table 4: Screw Lengths_

| **Screw Position** | **Length of Screw Thread** |
| --- | --- |
| D2D, D3D, D4D, D5D | 15 mm |
| D2I, D3I, D4I, D5I | 15.5 mm |
| D2P, D4P, D5P | 17.5 mm |
| D3P | 20.5 mm |
| D1D | 18.5 mm |
| D1P | 22 mm |
| D0 (both bottom and top screws) | 25 mm |
| Ventral Palm Screws (4) | 12 mm |
| Geared Rotator Screws (2) | 5 mm |
| D1A (both bottom and top screws) | 20.5 mm |

1.
# Thumb Assembly (1h 0m)

  1.
## Part Assembly

![](RackMultipart20200724-4-1dqkhfm_html_d140d315b4ed0046.gif) Assemble the thumb parts as shown in Figure 11. File or sand parts as necessary to achieve good fits.

![](RackMultipart20200724-4-1dqkhfm_html_e2476f37c31fa409.gif) Use superglue on the surfaces marked in yellow.

1. Pot Activator
2. Potentiometer
3. MC – P Geared Rotator
4. Servo Spool Thumb
5. Hitec HS-35 HD Servo
6. MC –P Main
7. MC – D
8. IP – P PivotTH
9. IP – P MainTh
10. IP – DTH
11. DP – P PivotTH
12. DP – P MainTH
13. DP – D LockTH
14. DP – D MainTH
15. DP – D FSR ActuatorTH
16. DP – D TipTH

The appropriate M2 screws for each joint should be installed using an M2 washer. The screws extend through the potentiometer and pot activator, screwing into the far side of the finger joint. Tightening these screws too much will cause the joints to bind. Tighten the screws until contact with the potentiometer, then back out ½ turn.

The thumb zip-tie should be installed and tensioned before the MC – P Geared Rotator is attached using two 5mm M2 screws. See Section 8 Figure 12 shows an assembled thumb prior to MC – P Geared Rotator installation, showing the correct servo positioning for full extension.

  1.
## Optional: Adductible Thumb Assembly

The Adductible Thumb is an optional variant that adds an additional degree of freedom to the thumb digit, allowing it adduct (flex laterally towards the fingers) and abduct (extend laterally away from the fingers). Table 5 illustrates how this variant of the HANDi Hand thumb compares with the default thumb assembly. To implement the Adductible Thumb instead of the default thumb, print the parts listed in this section instead of those listed in section 6.1; this can be done by printing the &quot;Full Add Thumb&quot; X3G file instead of the &quot;Full Thumb&quot; X3G file.

_Table 5: Comparison of Default Thumb and Adductible Thumb Option_

| **Property** | **Default Thumb** | **Adductible Thumb** |
| --- | --- | --- |
| Length from D0 Axis | 93 mm | 104 mm |
| Mass (printed parts only) | 27 grams | 33 grams |
| Degrees of Freedom | 2 | 3 |
| Degrees of Actuation | 2 | 2 |
| Grips Possible | Pinch Grip, Tripod Grip, Column Grip | Key Grip, Pinch Grip, Tripod Grip, Improved Column Grip |

Note that if using an Arduino Mega, connecting to a potentiometer on the additional degree of freedom (D1A) will require replacing an existing connection pin, either by swapping an existing potentiometer out with a Pot Placeholder, or by giving up joystick control for an additional pin.

If implementing the Adductible Thumb option, assemble the thumb parts as shown in Figure 13. File or sand parts as necessary to achieve good fits. Note that the &quot;Servo Spool Thumb – Add&quot; part replaces the &quot;Servo Spool Thumb&quot; part used in the default thumb assembly.

![](RackMultipart20200724-4-1dqkhfm_html_1abb1646000bd6ab.png)

_Figure 13: Adductible thumb assembly diagram_

Use superglue on the surfaces marked in yellow.

1. Pot Activator – Add
2. Pot Activator
3. Potentiometer
4. MC – P Geared Rotator
5. Servo Spool Thumb – Add
6. Hitec HS-35 HD Servo
7. MC –P Main – Add A
8. MC –P Main – Add B
9. MC – D – Add A
10. MC – D – Add Pivot
11. MC – D – Add B
12. IP – P PivotTH
13. IP – P MainTh
14. IP – DTH
15. DP – P PivotTH
16. DP – P MainTH
17. DP – D LockTH
18. DP – D MainTH
19. DP – D FSR ActuatorTH
20. DP – D TipTH

![](RackMultipart20200724-4-1dqkhfm_html_c936419467684daa.gif) Assemble and mount as per the standard thumb assembly and mounting instructions.

  1.
## Mounting to Palm

Rotate the D0 servo with the small gear to the mounting position. Looking down from the top of the hand, this will be fully clockwise for a right hand assembly, and fully counter clockwise for a left hand assembly.

Position the thumb so that it is rotated outward as much as possible, and secure to the palm using two 25 mm M2 screws; one from the top and one from the bottom. Be sure to include a pot activator on the bottom side.

1.
# Finger Assembly (0h 15m each finger)

![](RackMultipart20200724-4-1dqkhfm_html_302de2e56cce03b4.gif)
 Assemble the finger parts as shown in Figure 15. File or sand the parts as necessary to achieve good fits.

Use superglue on the faces marked in yellow.

1. Pot Activator
2. Potentiometer\*
3. PP – P PivotD2\*\*
4. PP – P MainD2\*\*
5. PP – D
6. IP – P Pivot
7. IP – P Main
8. IP – P D
9. DP – P Pivot
10. DP – P Main
11. DP – D Lock
12. DP – D Main
13. DP – D FSR Actuator
14. DP – D Tip

\* The number of potentiometers used, and their location depends on the finger. Wherever a potentiometer is omitted, a Pot Placeholder should be used in its place. For use with an Arduino Mega, the suggested potentiometer positions are given in Figure 2, Section 2.2 .A Pot Activator should be used regardless of whether a potentiometer or a Pot Placeholder is used.

\*\* This assembly diagram shows the index finger (D2). For other fingers, substitute the appropriate parts here (i.e. D3 for middle finger, etc.).

1.
# Servo Installation and Finger Tensioning (0h 7m each finger)

Tensioning of fingers and thumb are identical processes, with the exception that the thumb servo spool will not include a zip-tie receiver. Here the tendon zip-tie passes directly through the spool.

 ![](RackMultipart20200724-4-1dqkhfm_html_55aa6112bf57ffb8.gif) ![](RackMultipart20200724-4-1dqkhfm_html_faf00ac51b55ab62.gif)

1. Rotate servo to the full forward position using the Arduino sketch Pot\_to\_Servo\_Control.ino. Wiring for this sketch is explained in section 13.1 . See Figure 16 for the definition of full forward position. Servo orientation matters for this operation, and changes depending on the finger in question. Refer to Figure 20 for correct servo positioning.
2. Install a zip-tie in the servo spool as per Figure 17.
3. Install the servo spool on the servo, using the plus-shaped servo horn with ends clipped, ensuring that the zip-tie receiving end is at the top of the servo (most ventral when mounted in the palm). See Figure 18.
4. Cut a zip-tie&#39;s receiving end so that the thickness is constant along the entire zip-tie. Sidecutters work best for this operation; fine adjustments can be made with a hobby knife when necessary. The cut is illustrated in Figure 19. This end of the zip-tie will serve as the stopper at the tip of the finger. ![](RackMultipart20200724-4-1dqkhfm_html_f690cf2769b759c9.gif)
5. Thread the zip-tie through the finger from the distal to the proximal end, staying ventral to each of the joint pivots. ![](RackMultipart20200724-4-1dqkhfm_html_6b74017d3945931b.gif)
6. Pass the tendon zip-tie through the zip-tie receiver on the servo spool (or through the spool itself in the case of the thumb spool). There should be no slack in the zip-tie when the finger is fully extended, the servo is fully rotated forward, and the servo is installed in the dorsal palm. Trim the free end of the tendon zip-tie. Figure 20 shows the completed tensioning and servo installation.

![](RackMultipart20200724-4-1dqkhfm_html_34d90e575eba0b85.gif)

1.
# Breadboard Hub (3h 0m)

Creation of the breadboard hub is by far the most technically difficult and labor intensive operation in assembling the HANDi Hand, and is not required to have a fully functional hand. The breadboard hub reduces the number of wires leaving the hand from 60 to 22, which is important when interfacing with a movable arm since a large bulk of wires will tend to bind and restrict motion of the arm. Work is currently being done on the design of an in-palm PCB which will increase the sensing capabilities of the hand while simultaneously reducing the amount of wiring required. Please check BLINCdev.ca for information about upcoming releases.

 ![](RackMultipart20200724-4-1dqkhfm_html_8acf87b3dd568b97.gif)
1. Print out the breadboard and connector hub with the specifications given in Table 1, page . Because it&#39;s such a small part with finicky details, it sometimes won&#39;t slice properly and can print with some of the insulating walls missing. If this is the case for you, glue some thin bits of plastic where the walls should be while you&#39;re assembling the rest.
2. Remove the clips from the miniature breadboard, and cut/solder them together to obtain 4 clips with 7 receptacles, 4 with 3 receptacles, and 20 with 1 receptacle. When soldering the clips together for the 7 receptacle clips, be careful to ensure that the receptacles line up with the holes of the printed breadboard. Refer to Figure 21.
3. Solder a 1&quot; piece of prototyping wire (22 AWG) to each single receptacle clip at the base (Figure 22). ![](RackMultipart20200724-4-1dqkhfm_html_6459490a75f42e35.gif)
4. Press-fit each of the receptacles into the bottom of the printed breadboard, making sure no part of any receptacle extends past the base of the board.
5. Solder jumper wires between the power receptacles and ground receptacles as in Figure 23.
6. Test the board for proper conductivity at each receptacle. Adjust receptacle positioning if necessary. ![](RackMultipart20200724-4-1dqkhfm_html_5abf2ba42c15c945.gif)
7. Superglue the molex connectors to the connector hub, referring to Figure 24.
8. Superglue the printed breadboard to the other side of the connector hub, being careful to note the orientation shown in Figure 25.
 ![](RackMultipart20200724-4-1dqkhfm_html_df9637fcc73a4c26.gif)

 ![](RackMultipart20200724-4-1dqkhfm_html_25f9b549fdff4fd.gif)

1. Solder the power and ground connections to the header pins. Refer to Figure 28 to ensure power and ground are soldered to the correct header pins. ![](RackMultipart20200724-4-1dqkhfm_html_60e2f236fed90f3c.gif)
2. Solder the yellow jumper wires to the appropriate receptacle pins, and the 100 kΩ resistors to appropriate receptacle pins as shown in Figure 26:

 ![](RackMultipart20200724-4-1dqkhfm_html_9bb99c7e8d1d5a7.gif) ![](RackMultipart20200724-4-1dqkhfm_html_11506b365bdbf770.gif)

1. Cover and protect all connections using Sugru or similar methods. See finished breadboard hub in Figure 27.

 ![](RackMultipart20200724-4-1dqkhfm_html_2ca38db7d319d980.gif)
1.
# Aluminum Servo Cover (0h 45m)

The servo covers are made of aluminum. They act as a heat sink and reduce the tendency to overheat the servos, and as well have less tendency to warp than the 3D printed plastic. They can be cut from the aluminum sheet given in the Bill of Materials, to the size and shape given in Appendix B: Servo Cover Template. Cut around the outside shape using tin snips, and file down to the exact shape and size using a flat metal file. Drill the holes using a 1/16&quot; drill bit. Attach the servo covers using the coarse thread stainless steel phillips screws provided with the HS-35HD servo motors. Refer to Figure 29 for orientation of the servo covers for installation.

1.
# Ventral Palm Cover; USB Webcam (0h 20m)

The webcam used currently is a Logitech Quickcam Pro for Notebooks. Remove the PCB and lens from the camera housing, and mount it to the ventral palm using the extra small black screws that came with the HS-35HD servo motors. Figure 30 shows the USB webcam mounted to the ventral palm.

![](RackMultipart20200724-4-1dqkhfm_html_53c76d25b8aec496.gif) The USB cable from the camera will be routed out of the wrist cavity via the USB wire channel noted earlier in section 9 .

Mount the ventral palm to the front of the dorsal palm, being careful to ensure all wires are routed properly and there are no pinch points. The ventral palm is secured using four 12mm M2 screws.

1.
# Palm Grips (1h 15m)

![](RackMultipart20200724-4-1dqkhfm_html_dbcfe837e8db9f40.gif)
 To increase the friction on the palm, palm grips made of neoprene extra strength rubber are superglued to the palm plate and the finger phalanxes. A template for the grips is found in Appendix A: Grip Pattern Template. The locations for the grips can be found in Figure 31.

The radial palm grip should be glued to both the ventral palm and the dorsal palm, covering the seam. Once glued in place, cut along the seam with a hobby knife to make the ventral palm removable again.

1.
# Wiring (1h 0m)

  1.
## Testing

The following wiring diagram (Figure 32) is intended for use with the Arduino sketch Pot\_to\_Servo\_Control.ino, for the purpose of testing an individual servo for tensioning, installation and testing finger movement.

![](RackMultipart20200724-4-1dqkhfm_html_fb3ee5a216fbc5b8.gif)

  1.
## Full Implementation

![](RackMultipart20200724-4-1dqkhfm_html_32ae7315096a1e49.gif)
 The wiring diagram in Figure 33 outlines the wiring setup including 6 control potentiometers (one for each degree of freedom), 5 position sensing potentiometers, 5 FSRs, 6 servos, and servo power switch. This wiring setup is intended for use with the Arduino sketch Potentiometer\_Control.ino.

The wiring diagram in Figure 34 outlines the complete wiring setup for 9 potentiometers, 5 FSRs, 6 servos, thumb joystick control, and servo power switch. This wiring setup is intended for use with the Arduino sketches Individual\_Vel\_rev1.ino and Grasp\_Vel\_rev2.ino.

![](RackMultipart20200724-4-1dqkhfm_html_833d2fb8642d43ac.gif)

The custom in-wrist breadboard removes a lot of the complications for wiring; if the sensors and servos are connected to the breadboard hub as per Figure 28 on page , the circuit above will be created when the following connections are made to the Arduino Mega (see Table 6):

_Table 6: Pin connections to Arduino Mega_

| **Sensor** | **Pin on Arduino Mega** |
| --- | --- |
| D0 Pot | A2 |
| D1P Pot | A3 |
| D1D Pot | A4 |
| D2P Pot | A5 |
| D2I Pot | A6 |
| D3P Pot | A7 |
| D3I Pot | A8 |
| D4P Pot | A9 |
| D5P Pot | A10 |
| D1 FSR | A11 |
| D2 FSR | A12 |
| D3 FSR | A13 |
| D4 FSR | A14 |
| D5 FSR | A15 |
| D0 Servo | Digital 3 |
| D1 Servo | Digital 5 |
| D2 Servo | Digital 6 |
| D3 Servo | Digital 9 |
| D4 Servo | Digital 10 |
| D5 Servo | Digital 11 |

1.
# Appendix A: Grip Pattern Template

![](RackMultipart20200724-4-1dqkhfm_html_e302dc2fbd2057fa.gif)

1.
# Appendix B: Servo Cover Template

![](RackMultipart20200724-4-1dqkhfm_html_726cee77c26a5217.gif)
