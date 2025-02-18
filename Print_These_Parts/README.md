# Printed part directory
If you don't decide to build the printer using a kit that comes with all of the printed (or CNC'd) parts, you will need to print them yourself. Since the assembly has been heavily simplified, there aren't that many parts left to print.

The "Ready_To_Print_Prearranged" folder comes with preset plates that you can load into your slicer, and go. The .3mf file also includes the default recommended settings for FDM:
* 0.2mm layer height
* 0.4mm forced extrusion width
* Infill types: either grid, gyroid, honeycomb, triangle or cubic
* 40% infill percentage
* 4 perimeters (walls)
* 5 top/bottom solid layers.

For the material, the recommendation is always ABS/ASA as other materials like PLA can degrade and crack, especially when under temperature. Since we are not using an enclosure and heated bed, you could possibly get away with it, but we highly recommend sticking with ABS/ASA to avoid issues.

You can also use the Voron community Print It Forward (PIF) scheme to pay community members located near you to print and ship the parts to you. To find out more, visit https://pif.voron.dev/


# Part file naming guide
The "Individual_STL" files contains all the separate STL files, in case you want to slice and print them separately.

**QUANTITY REQUIRED**

*Thumb_Nut_x3.stl*  
Any file that ends with “_x#” is telling you the quantity of that part required to build the machine.

**FYI: ACCENT COLOR**

*[a]_Tensioner_Knob_x2.stl*  
The original Voron files use the "[\a]" prefix to indicate the part should be printed with a coloured accent (and "[\c]" for clear parts). This is unnecessary, and just complicates the overall build process, so we recommend printing all parts in one colour. Noting it here to indicate what it means in the original Voron naming scheme that you might notice being used if reusing parts from other repositories.

# Optional files
The "[\Optional]_Extra_or_Alternative_Parts" folder contains optional addons, adapters for alternative electronics boards, etc. You do not need to print these for the stock build.