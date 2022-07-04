## 3D Printing

## Getting started / First Timers

NOTE: Talking about Filament based printers here, Resin printers will have their own section later.

#### Prusa MK3S+ - £699
The gold standard, 250x210x210mm print area, spring steel bed, bed leveling, direct drive extruder, very polished and well supported.

#### Prusa Mini+ - £334
Smaller print Area, 180x180x180mm print area, spring steel bed, bed leveling, bowden extruder, very polished and well supported.

#### Anycubic Kobra - £290
220x220x250mm print area, spring steel bed, bed leveling, direct drive exturder, not as polished as Prusa machines, support is china based (though have heard good things)


### So why are my top 2 picks Prusa machines?
Prusa have driven the development of the 'cartesian' 3d printer since the earliest days, they have driven alot of innovation in this field. They are a Czech company and they provide exceptional in-house support for their products while encouraging a big community arund their systems which can also provide support and modifications.

The Original MK2S machine was cloned 6 ways from sunday and most commonly seen as the Anet A8 (never buy, fire hazard) then the MK3 essentially itterated the design and refined it. Its now a go-to machine for even professional print-farmers becuase, it just works.

You can build their MK3 kit, load up prusaslic3r (a fork of Slic3r that Prusa have also been developing) load in a 3d model and hit print. It will come out looking beautiful.

With that said, I've personally not bought one of prusas printers (though i would love one) but i am already deep in the tinkering hole, so im building more advanced printers and designing my own.

"But the Kobra is less than half the price" This is true, and i have actually bought a Kobra. Its one of the first printers that on paper looked like it delivered all the features needed to get started without having to tinker and tweak to get it printing at acceptable quality.

The Kobra does seem to deliver on the promises, with its direct drive extruder able to push even flexible filaments, and the textured PEI spring steel bed makes part removal a breeze. but there are some shortcomings of the printer that need to be considered; The extruder is a bit oozy and can result in less than desirable print quality, the print head is heavy and this is reflected in the appearance of some prints depending on filament used, the bed leveling and z-offset for print bed leveling does not seem to stick between power-cycles of the machine.

Some of those shortcomings can be addressed in slicing software and some with future firmware updates (hopefully) but then it starts to dip into the territory of 'tinkering' to get it printing right. I just think the level of tinkering is low enough to make it accessable to most people getting into 3d printing.

### Slicing? Extruding? Cartesian? what?

#### Slicer
Software to turn 3d models into the layer-by-layer code (gcode) that a printer can understand.
Popular ones: Prusaslic3r (not just for prusa machines), Slic3r, Cura

#### Direct drive vs. Bowden Extruders
A direct drive means the filament is grabbed and fed right before the hot-end of a printer, reducing the distance it gets pushed to only a couple of centimeters. This is useful when you have flexible filaments such as TPU, which cannot be pushed over longer distances or it will bind up or stretch.
A bowden extruder is one that is mounted further from the hotend and linked via a PTFE tube (bowden tube) which is enough constraint for most rigid filaments. The advantage of a bowden/remote extruder is less weight on the X carriage when it moves around, meaning you can move it faster without worrying about artifacts appearing in your prints.

#### Cartesian vs. coreXY vs. delta
Cartesian generally refers to having a motor dedicated to moving one axis only X/Y/Z
CoreXY links the X and Y axis with a complex belt assembly that allows for very quick and precise movement in the X/Y directions
Delta is the mind blowing 3 pillar system that uses all 3 motors in sync to drive X/Y/Z motion and they are mesmerising to watch in action, but from experience they are the biggest pain in the arse. they can however drive the print head very quickly.

#### PLA PETG ABS ASA TPU
PLA - Bioplastic, low melt temp (175-210), very easy to print and work with, commercially compostable, smells like sugar melting
PETG - Stuff that fizzy drink bottles are made from, slightly higher print temps (190-225), good mechanical plastic.
ABS - the OG plastic gangster, higher melt temps (220-240), very good mechanical strength and less likely to deform in warm enviroments, requires a closed chamber to print in or it warps while printing, stinks like hell when printed.
ASA - Better than ABS, prints at the same temps (220-240), UV stable, still needs a closed chamber to print in, but stinks much less.
TPU - Flexible filament, comes in variety of hardnesses and thus print temperatures, good for printing things you can squish.


