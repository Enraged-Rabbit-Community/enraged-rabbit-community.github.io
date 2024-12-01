---
layout: default
title: About ERCF
nav_order: 1
---

# About ERCF

This is the place to recognize the origins and evolution of this project. ERCF was originally envisioned and created by Ette and the v1.1 release credits Tircown, the Voron Dev team (special mention to Dunar), Benoit, Dustin Speed, Kageurufu and the HonHonHonBaguette people! 

Over time and significant adoption the shortcomings of ERCF v1.1 design came to light, and that inspired a set of modifications to address them: SturdyBunny, TripleDecky, Springy, Binky and other strange names appeared. It was then that Moggieuk, the author of Happy Hare, rounded up these project authors and created the beginnings of the ERCF v2 community release. As the project developed, Kinematicdigit developed and contributed CottonTail, Sorted developed and contributed Filametrix and we were joined by some awesome talent that polished, tested and documented to complete the project.

Many hundreds of hours of volunteer effort have gone into this project and we hope it pays tribute to Ette’s wonderful original design. The BMW of MMU’s!

---

This project aims to bring multi material capabilities to 3D printers using a single Direct Drive toolhead. While this project is mainly designed to be used on VORON printers, it can also be used (or adapted) on any 3D printer that runs Klipper.

The project is composed of 5 different components, some of which are optional: 

**Enraged Rabbit Carrot Feeder (ERCF)**. The Carrot Feeder is the main unit and allows use of a high number of different filaments (tested up to 15 channels by the test team) and feed them, one at a time, into the printer toolhead on an as-needed basis.

**Enraged Rabbit Cottontail (ERCT)** is a new integrated (but optional) filament buffer system to handle the filament when it is ejected from ERCF on a tool change. It can handle up to 1.5m bowden tube lengths. This has been specifically designed to minimize friction when setup in accordance with this manual which takes into account the natural filament memory. It has options for LED gate indicators and entry sensors.

**Enraged Rabbit Filametrix (ERF)**: This filament cutter is an optional toolhead modification to cleanly cut the tip of the ejected filament, so it can be loaded easily on next use. This option alleviates the frustrating job of tuning tip formation through movement of the filament within the extruder, which often still results in strings of filament causing clogs.

**Toolhead Sensor**: This is a set of modifications for popular extruders that provides filament detection capability within the toolhead. Although optional, it is highly recommended, and makes filament change far more reliable and smooth.

**Happy Hare Firmware**: This has become the go-to extension to Klipper for controlling various types of MMU. It is optimized to support ERCF.

(Future) **Enraged Rabbit Pellet Purge (ERPP)**: Envisioned, but currently unavailable, this will alleviate the need for a purge tower meaning more room for your prints. Stay tuned.<br>

---

Let's introduce the development, test and doc team. A project like this doesn't happen without many hundreds of hours of volunteer effort and all of these folks are truely awesome. Please give some 👏 👏 👏

@moggieuk V0.1503 | V2.4088 (Mr Happy Hare & Chief whip) <br>
@gneu V2.5345 (Filament block & bling innovator) <br>
@sneakytreesnake V2.3804 (The project backbone!) <br>
@mneuhaus VT.483 (Mr Binky) <br>
@Miriax (Designer & Doc Demon) <br>
@kinematicdigit VS.744 (Mr Cotton Tail & Doc Illustrator) <br>
@ningpj (Tester, Breaker & Documenter) <br>
@fizzy (King of CAD) <br>
@gsx8299 (Test Builder Extraordinaire) <br>
@sorted (Filametrix "don't get enraged" filament cutting system) <br>
@kierantheman (Mr ThumperBlocks) <br>
@Fragmon (Videographer) <br>
@Silverback V2.1356 (Filametrix tester, builder & engineer) <br>

---

### Next: [Choosing an Extruder](./hardware.md)
