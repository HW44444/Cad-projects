# Scent Holder

A desk organizer I designed to hold my deodorant, lotion, and cologne in one place instead of having them scattered around.

## Why I built it
My deodorant, lotion, and cologne were always loose on my dresser and getting knocked over. I measured each one and designed a single block with a dedicated pocket for each: two round pockets for the cylindrical bottles and one rectangular pocket for the lotion.

## Design details
- Two circular pockets sized to the bottle diameters, plus one rectangular pocket
- Filleted outer edges for a finished feel and added strength (sharp internal corners are where parts crack)
- Hollowed out with a shell to cut material use and print time
- Modeled in Autodesk Fusion

## Files
- `scent-holder.step` — universal CAD format, editable in any CAD program
- `scent-holder.stl` — mesh file, ready to slice and 3D print

## What I learned
- **Tolerances matter.** A pocket cut to the exact measured diameter of a bottle won't actually fit — printed parts need roughly 0.5 mm of clearance to slide in.
- **Design for manufacturing.** My first version was about 12 inches long, which is bigger than the build volume of most consumer 3D printers. Knowing what your machine can actually produce has to be part of the design, not an afterthought.
- **Solid blocks waste material.** Shelling the inside kept the same outward shape while dramatically reducing filament and print time.
- **Fillet before shelling** so the hollow interior follows the rounded geometry and wall thickness stays even.

## Print notes
- Print with the open (hollow) side down on the build plate
- No supports needed
- PLA is fine for this
