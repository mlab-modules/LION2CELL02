# PCB

Board size: 80.77x60.45 mm (3.18x2.38 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness | Material        | Epsilon_r | Loss tangent |
|----------------------|----------------------|------------------|-----------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |           |                 |           |              |
| F.Mask               | Top Solder Mask      |                  |        10 |                 |           |              |
| F.Cu                 | copper               |                  |        35 |                 |           |              |
| dielectric 1         | core                 |                  |      1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |        35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   |                  |        10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |           |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |           |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.2 mm (8 mils)

- By design rules: 0.2 mm (8 mils)

Drill: 0.3 mm (12 mils)

- Vias: 0.3 mm (12 mils) [Design: 0.4 mm (16 mils)]
- Pads: 0.3 mm (12 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.4/0.2 mm (16/8 mils)

- By design rules: 0.4/0.3 mm (16/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 78 (thru: 77 buried/blind: 0 micro: 1)

Outer Annular Ring: 0.05 mm (2 mils)

- By design rules: 0.1 mm (4 mils)

Eurocircuits class: 6F
- Using min drill 0.15 mm for an OAR of 0.13 mm


# General stats

Components count: (SMD/THT)

- Top: 2/19 (SMD + THT)
- Bottom: 83/0 (SMD)

Defined tracks:

- 0.2 mm (8 mils)
- 0.25 mm (10 mils)
- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)
- 0.6 mm (24 mils)
- 0.8 mm (31 mils)
- 0.86 mm (34 mils)

Used tracks:

- 0.2 mm (8 mils) (406) defined: yes
- 0.3 mm (12 mils) (81) defined: yes
- 0.4 mm (16 mils) (13) defined: yes
- 0.5 mm (20 mils) (107) defined: yes
- 0.8 mm (31 mils) (27) defined: yes
- 1.0 mm (39 mils) (53) defined: no
- 4.5 mm (177 mils) (6) defined: no

Defined vias:


Used vias:

- 0.4/0.2 mm (16/8 mils) (Count: 1, Aspect: 4.0 A) defined: no
- 0.8/0.4 mm (31/16 mils) (Count: 77, Aspect: 2.0 A) defined: no

Holes (excluding vias):

- 0.2 mm (8 mils) (7)
- 0.65 mm (26 mils) (2)
- 0.89 mm (35 mils) (34)
- 1.0 mm (39 mils) (8)
- 1.3 mm (51 mils) (8)
- 1.6 mm (63 mils) (4)
- 2.7 mm (106 mils) (6)
- 3.0 mm (118 mils) (4)

Oval holes:

- 0.6x1.4 mm (24x55 mils) (2)
- 0.6x1.7 mm (24x67 mils) (2)

Drill tools (including vias and computing adjusts and rounding):

- 0.3 mm (12 mils) (8)
- 0.5 mm (20 mils) (77)
- 0.65 mm (26 mils) (2)
- 0.7 mm (28 mils) (4)
- 1.0 mm (39 mils) (34)
- 1.1 mm (43 mils) (8)
- 1.4 mm (55 mils) (8)
- 1.7 mm (67 mils) (4)
- 2.7 mm (106 mils) (6)
- 3.1 mm (122 mils) (4)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Top    |               4 |       5.51 |      0.03 |
| Bottom |             253 |     338.26 |      1.68 |
| Total  |             257 |     343.76 |      1.71 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



