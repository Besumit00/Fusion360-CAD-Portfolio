# Electronics Enclosure (Sheet Metal)

## Objective
Design a bent sheet-metal enclosure for a small electronics project, using Fusion 360's dedicated Sheet Metal workspace to model realistic bends, flanges, and a flat pattern for fabrication.

## Skills Practiced
- Sheet Metal workspace fundamentals
- Flange, Face, and Bend tools
- K-factor & bend allowance
- Flat pattern generation
- Corner reliefs

## CAD Features Used
- Flange
- Bend
- Flat Pattern
- Corner Seam
- Extrude (mounting bosses via Rib)

## Challenges
- Flat pattern showing unexpected overlaps at corners.
- Choosing a realistic material thickness and bend radius for the intended manufacturing process.

## How I Solved Them
Applied corner reliefs at each bend intersection and set the sheet metal rule to a realistic 1.5 mm mild steel gauge with a matching bend radius, which resolved the flat-pattern overlap.

## Engineering Notes
Sheet metal design is fundamentally different from solid modeling — you're designing a flat piece of material and its bend sequence, not a solid, so the flat pattern must always be checked before finalizing.

## Manufacturing Considerations
Flat pattern (DXF) is exportable directly for laser cutting; bend sequence was checked to ensure no bend interferes with the tooling of a previous bend.

## Material Suggestions
1.5 mm mild steel or aluminum 5052 sheet, both common for laser-cut electronics enclosures.

## Improvements
Add ventilation slots and a hinge feature for a removable lid.

## Time Taken
~2 hours

## Final Images
| View | Preview |
|---|---|
| Front View | `Images/front.png` |
| Isometric View | `Images/isometric.png` |
| Exploded View | `Images/exploded.png` |

> Replace the placeholder filenames above with your actual renders/screenshots exported from Fusion 360.

## Download Files
- [Fusion 360 Native File](./CAD/Fusion360.f3d)
- [STEP File](./CAD/Model.step)
- [STL File](./CAD/Model.stl)
- [Drawing PDF](./Drawings/Drawing.pdf)
