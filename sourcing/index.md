---
layout: default
title: Sourcing Information
has_children: true
nav_order: 4
---

# Sourcing Information

## Bill of Materials and Source Guide

The Bill of Materials (BOM) is generated from the [ERCF website](https://ercf.community).  Select the printer to be built, then select 'Configurator' and choose from the parameters.  A customized BOM will be presented.  The BOM is considered the absolute guide for what is actually required to build the printer.

The Sourcing Guide is made available at the same time as the customized BOM.  It is a list of Voron maintained references to where to purchase the various components listed on the BOM for the different printers.  _The sourcing guide is not customized to the printer.  All quantities are mostly incorrect._  There are additional tabs at the bottom of the sourcing guide for optional or additional components.

## Printing Parts

### Material

Please see the [materials guide](./materials.md) for more detailed information.

### Colors and Quantities

The recommended accent parts are denoted with a "[a]_" in the filename. Many of these are still functional in nature and should still follow the recommended print settings.

Filenames that end with "_x#", indicate that the part must be printed multiple times (ie. x2, x4, etc.)

Typical printers require approximately 1.5kg of the primary color and 0.3kg of the alternate color, assuming no failed or reprinted parts. Most people end up reprinting a few parts and a few mods, so plan on 2kg of the primary color. Refer to the table [here](./sourcing_faq.md) for your specific model.

For information on selecting parts to print, clarification of colors and quantities, and even what parts PIF will provide, see the [Printed Part Reference](https://docs.google.com/spreadsheets/d/1njgHapSZLiQHobrEVkeuAuhhDsXzFOJOiIpvfVFeGxQ/edit?usp=sharing) spreadsheet.

### Print Settings

These are the recommended settings.

- Layer height: 0.2mm
- Extrusion width: 0.4mm, forced
- Infill percentage: 40%
- Infill type: grid, gyroid, honeycomb, triangle, or cubic
- Wall count: 4
- Solid top/bottom layers: 5
- Supports: NONE

## Ordering Parts

When purchasing, the sourcing guide and the bill of materials (BOM) are not the same.  Be sure to refer to the BOM for all quantities.  If unclear please see the [explanation of differences](#bill-of-materials-and-source-guide).

*When purchasing small items, it is recommended to buy extras (round up). Having a few extra screws or connectors around may actually help you later.*

_Note:_ The generated BOM part numbers for Misumi extrusions are the exact part numbers.  Enter them into Misumi's website and they will return exactly what needs to be ordered, including any extra drilling or tapping operations.

There are a growing number of suppliers that are assembling kits to build Voron printers.  Outside of the sourcing guide, Voron does not implicitly endorse any specific vendor of Voron kits.

### Parts Selection / Alternates

When choosing extrusions, V-slot extrusions are discouraged.  This is due to the use of the MGN9 linear rail as the V-slot and width of the rail are very close and cause misalignment.  Vendors of extrusions other than Misumi are generally fine but verification of the extrusion profile is highly recommended to ensure they will fit with the rails.

If trying to keep costs down, the display / screen on any printer is entirely optional. Many builders solely use the web interface.

Builders are welcome to make substitutions as they see fit but this printer is not a race to be as cheap as possible. It is designed to compete with many other high-end printers while still being affordable. Substituting parts may also have other unintended side effects and cause compatibility issues. Please feel free to ask for advice before any substitutions are made.

More sourcing information can be found in the [sourcing FAQ](./sourcing_faq.md)

## Unsupported Configurations

## Tools

### Required Tools

_It might be possible to build, troubleshoot, and tune an ERCF without this list, but it will be much harder._

* Set of metric hex wrenches ("keys") from at least 1.5mm - 5mm. (Wiha, Wera, or Bondhus are preferred)
* Standard screwdrivers
* Wire strippers from 16 gauge (1.25mm) to 26 gauge (0.405mm)
* Diagonal wire cutters, small
* Soldering iron (solder helpful)
* Multimeter
* Metric calipers, 6"/150mm
* Crimpers
  * Molex Crimpers (Good: IWISS IWS-3220M, Better: Engineer PA-09, Best: Molex Crimper)
  * Ferrule Crimpers
  * Terminal Crimpers

### Helpful / Nice To Have Tools

_These make Voron life a little nicer._

* Needle nose pliers
* Tweezers
* Small "X-Acto" knife
* Machinist scale / ruler, either 6"/150mm or 12"/300mm
* Machinist square, 4"/100mm or larger (Sometimes called "locksmith angles", see DIN 875)
* Deburring tool
* Small files
* Small flashlight
* Precision screwdriver set
* Heat shrink labeler

---

### Next: [The Build](./build/index.md)
