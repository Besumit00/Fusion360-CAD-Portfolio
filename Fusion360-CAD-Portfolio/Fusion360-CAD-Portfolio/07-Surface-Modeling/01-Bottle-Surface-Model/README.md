# Contoured Bottle (Surface Modeling)

## Objective
Model an organic, contoured bottle shape using Fusion 360's Surface workspace — lofting between sketch profiles and stitching surfaces into a watertight solid.

## Skills Practiced
- Surface Loft
- Patch
- Stitch
- Surface offset & thicken
- Rail curves

## CAD Features Used
- Loft (surface)
- Patch
- Stitch
- Thicken

## Challenges
- Loft self-intersecting between profiles with very different shapes.
- Getting a fully watertight solid from multiple stitched surface patches.

## How I Solved Them
Added intermediate guide profiles between the top and bottom sketches to control the loft's transition, and used the Stitch tool's 'tolerance' setting to close small gaps between surface patches so the model would convert cleanly to a solid.

## Engineering Notes
Surface modeling is the right tool whenever a shape can't be described by simple extrudes/revolves — organic, ergonomic, or aerodynamic shapes almost always need surfaces rather than solids as the starting point.

## Manufacturing Considerations
N/A directly, though a real bottle would be blow-molded or 3D printed for a prototype.

## Material Suggestions
PETG (if 3D printed) or HDPE (if blow-molded) would be typical for a real bottle.

## Improvements
Practice with the 'Rule' surface and boundary fill for sharper transitions.

## Time Taken
~1.5 hours

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
