Stethoscope
===========

This project aims to create a research-validated stethoscope whose plans are 
available freely and openly. The goal is for the bell to cost ~USD$1-2 to produce, 
and the rest of the stethoscope to cost approximately the same.

Currently, the stethoscope resulting from this project functions as well as the 
market gold standard, the Littmann Cardiology III.


Bill of Materials
=================

**Printed parts:**
* 1 stethoscope head (head.stl)
* 2 ear tubes (eartube.stl)
* 1 Y-piece (y_piece.stl)
* 1 Spring (spring.stl)

**Other hardware:**
Some vendors are suggested. See Bill of materials ODS file for more information.
* 40cm - 50cm Silicone 12mm or 13mm OD, 8mm ID
 * [8MM I.D X 12MM O.D NGP60 Clear Translucent Silicone Hose Pipe Tubing](http://www.advancedfluidsolutions.co.uk/8mm-id-x-12mm-od-clear-transulcent-silicone-hose-pipe-tubing-2480-p.asp) (USD$6.95/meter)
 * [8MM I.D X 13MM O.D NGP60 Clear Translucent Silicone Hose Pipe Tubing](https://www.advancedfluidsolutions.co.uk/8mm-id-x-13mm-od-clear-transulcent-silicone-hose-pipe-tubing-2482-p.asp) (USD$7.34/meter)

* 20cm Silicone 6mm or 8mm OD, 4mm ID (cut into 10cm pieces)
 * [4mm ID x 6mm OD](https://www.advancedfluidsolutions.co.uk/4mm-id-x-6mm-od-clear-transulcent-silicone-hose-pipe-tubing-2450-p.asp)
 * [4mm ID x 8mm OD](https://www.advancedfluidsolutions.co.uk/4mm-id-x-8mm-od-clear-transulcent-silicone-hose-pipe-tubing-2454-p.asp)

* Diaphragm: 40mm diameter cut from a report cover with approx 0.35mm plastic sheet
 * [Staples 21639 report cover (UPC 718103160223)](http://www.staples.ca/en/Staples-Swing-Lock-Report-Cover-Clear-with-Black-Spine-5-Pack/product_780953_2-CA_1_20001) (USD$8.84)
 * You can cut the diaphragm by hand or with a stamp like [this one](https://www.amazon.ca/Karujimu-ki-jumbo-craft-circle-CN45004/dp/B001CBY41W)

* Earbuds: Any large-sized standard earbuds will do.
 * [Silicone Earbuds 7 Pairs - Large size](https://www.amazon.ca/gp/product/B006VELFJY)
 
**Optional hardware**:
* Metal spring for holding ear tubes together



Print Instructions
==================
**INFILL MUST BE 100%**

All printed parts should be printed with ABS or PLA plastic at 0.2mm layer height, 
though it is acceptable for the first layer to be 0.3mm.

We print the eartubes and Y-pieces with a brim of 2mm to ensure that none of the 
parts lift off.

**INFILL MUST BE 100%.** Otherwise, the stethoscope will not print well.


Assembly Instructions
=====================

* Insert silicone into mold and allow to set as per manufacturer instructions.
* Attach the diaphragm (40mm) to the stethoscope head.
* Attach the stethoscope head to the silicone tube.
* Attach the silicone tube to the T-Piece.
* Attach spring to ear tubes.
* Attach the T-piece to the ear tubes.
* Attach the ear tubes to the molded earplugs.
* Test the stethoscope as per the validation instructions.


Changing and creating SCAD files
================================

[CrystalSCAD](https://github.com/Joaz/CrystalScad) and [OpenSCAD](http://www.openscad.org/) 
were used to create all STL files. To recreate the stethoscope head, simpley do:

``` shell
gem install crystalscad
ruby source_files/stethoscope_head/stethoscope_head.rb
```
The SCAD files output from CrystalSCAD are found in `source_files/stethoscope_head/output` and are named as follows:
* PrintableStethoscopeHead1Assembly_output.scad - The head
* EarplugMold_output.scad - Earplug mold


Other stethoscopes
==================
Others have made 3D printed stethoscopes too. See:
* https://www.youmagine.com/designs/stethoscope-chestpiece

