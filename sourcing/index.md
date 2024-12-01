---
layout: default
title: Sourcing Information
nav_order: 1
---

# Sourcing Information

## Bill of Materials

The Bill of Materials (BOM) is available [here](https://docs.google.com/spreadsheets/d/1HtVIu4yqzS6xJQr63-JKtMAh4Xq7wbtWPFeuiCnrnnE/).  Choose your desired number of channels, and the BOM spreadsheet will adjust the lengths and number of parts needed.  The BOM is considered the absolute guide for what is actually required to build the ERCF. 

## Self-Sourcing Parts
We support between 4 and 12 channels officially, but users have reported ERCFv1 up to 16 channels. Kits and certain accessories like the LED PCBs are designed around groups of 4 channels, so the primary build sizes we recommend are 4, 8, and 12. Most of our instructions depict 8 channels, and 8 channels is reportedly the most popular size to build in the community. Sourcing for each item is listed on the BOM spreadsheet with links to where to purchase the various components.  _The sourcing guide links are not customized to the ERCF.  All quantities are mostly incorrect._ 

*When purchasing small items, it is recommended to buy extras (round up). Having a few extra screws or connectors around may actually help you later.*

_Note:_ The generated BOM part numbers for Misumi extrusions are the exact part numbers.  Enter them into Misumi's website and they will return exactly what needs to be ordered, including any extra drilling or tapping operations.

More sourcing information can be found in the [sourcing FAQ](./sourcing_faq.md)

## Kit Vendors
<img src="/assets/Certified.jpg" alt='Vendor Certification' width="25%" >

These kits and specialty parts will have been checked by us and meet good quality standards. Pending Certification means it has met our first pass inspection and in the process of being verified as a V2 RC1 kit. <strong>WE DO NOT RECOMMEND PURCHASING KITS WITHOUT THE CERTIFICATION BY US. PLEASE CHECK BACK HERE FOR THE LIST OF AUTHORIZED VENDORS AND MANUFACTURERS</strong>:<br>
<ul>
  <li> <strong>Certified - Siboor</strong>
  </li>
  <li> <strong>Certified - Triangle Labs</strong>
  </li>
  <li> <strong>Certified - Seleadlabs</strong>
  </li>
  <li> <strong>Certified -  Makerpanda</strong>
  </li>
  <li> <strong>Certified -  Fysetc</strong>
  </li>
  <li> Pending Certification - LDO Motors
  </li>
  <li> Application Under Review/Pending Certification - Dodo 3D Labs
  </li>
</ul>  
  <br>
  A list of more official and certified vendors is on the way... stay tuned!

**Manufacturers:**
_If you want to be included, please contact us. We are happy to validate your kit/parts and then add you to the list._

<br>


# Printing Parts

## Material

ERCF is prototyped and tested in, and designed to use ABS. In theory, you can use PETG or PLA for most parts because they will not experience high heat, but many user attempts posted in the Discord prove that the resulting parts are slightly out of spec due to the difference in shrinkage for the different plastic types. One user reported spending a week attempting to dial in SLA settings for ERCF parts, to no avail. So please, don't attempt to print ERCF in anything but ABS.

## Colors and Quantities

The recommended accent parts are denoted with a "[a]_" in the filename. Many of these are still functional in nature and should still follow the recommended print settings.

Filenames that end with "_x#", indicate that the part must be printed multiple times (ie. x2, x4, etc.)

Light pipes for use with LEDs require the use of a clear/transparent plastic, and are denoted with "[c]_" at the beginning of the filename.

Shrouds for the LEDs and Encoder require opaque plastic to keep light from transmitting, preferably black. These parts are denoted with "[o]_" at the beginning of the filename. 

There are optional multimaterial parts denoted by "[mm]_" at the beginning of the filename. 

A typical 8-channel ERCF requires approximately 0.5kg of the primary color and 0.8kg of the accent color, assuming no failed or reprinted parts. If you're using the recommended ERCT buffer system, it uses an additional 0.3kg of the primary color and 0.7kg of the accent color, so plan on 2kg of the accent color.

For information on selecting which parts to print, see the [Printed Parts Tracker](https://docs.google.com/spreadsheets/d/1h1bJurR6Z8Ou36c5U9cWmqI86tXKlWrcZrWrHgGN13A/edit?usp=sharing) spreadsheet.

## Print Settings

ERCF requires that you have your printer calibrations all dialed in - please refer to the [Ellis print tuning guide](https://ellis3dp.com/Print-Tuning-Guide/). 
* Good, evenly adhering first layers
* Filament temperature set for your printer, environment, and brand of ABS
* Layer times and cooling tuned for your ABS so that you have the ability to print small parts and bridge at least 20mm
* Extrusion Multiplier (EM) tuned in so that you can consistently print 0.1mm gaps between walls

It is **MANDATORY** to print `Tools/Calib_Test.stl` and a `Filament_Blocks/[a]_Tophat_xN.stl` to make sure you are dialed-in enough to print ERCF! Many, many issues are caused by improperly-printed parts, so save yourself the trouble!

These are the recommended settings.   
- Layer height: 0.2mm
- Extrusion width: 0.4mm, forced
- Infill percentage: 40%
- Infill type: grid, gyroid, honeycomb, triangle, or cubic
- Wall count: 4
- Solid top/bottom layers: 5
- Supports: NONE

# Tools

### Required Tools

_It might be possible to build, troubleshoot, and tune an ERCF without this list, but it will be much harder._

* Set of metric hex wrenches ("keys") from at least 1.5mm - 3mm. Wiha, Wera, or Bondhus are top-notch tools.
* Standard screwdrivers
* Metric calipers, 6"/150mm

_If you're not purchasing a kit or pre-made wiring loom, you will need these tools to wire your ERCF:_

* Diagonal wire cutters, small
* Multimeter
* Wire strippers from 22 gauge (0.644mm) to 26 gauge (0.405mm)
* Soldering iron and solder
* Molex Crimpers (Good: IWISS IWS-3220M, Better: Engineer PA-09, Best: Molex Crimper)

### Helpful / Nice To Have Tools

_These make ERCF life a little nicer._

* Needle nose pliers
* Tweezers
* Small "X-Acto" knife
* Deburring tool
* Small files
* Small flashlight
* Heat shrink labeler


---

### Next: [The Build](../build/index.md)
