# Fillet, Chamfer & Pattern Practice

## Objective
Take a simple extruded block and practice applying fillets, chamfers, mirror, and rectangular/circular patterns to understand Fusion 360's feature-based (parametric) modeling approach.

## Skills Practiced
- Fillet (constant, variable)
- Chamfer (equal distance, distance-distance)
- Mirror
- Rectangular Pattern
- Circular Pattern
- Shell

## CAD Features Used
- Fillet
- Chamfer
- Mirror
- Pattern (Rectangular & Circular)
- Shell

## Challenges
- Fillets failing on tangent edges that met at sharp internal corners.
- Patterning a feature and having it reference the wrong instance count/spacing.

## How I Solved Them
Reordered the timeline so fillets were applied after all cuts were finalized, and used 'Distance and Count' instead of 'Spacing' in the pattern dialog to get predictable, evenly spaced instances.

## Engineering Notes
Feature order in the timeline matters — fillets and chamfers are timeline-sensitive and should generally be applied late, after the base geometry is finalized, to avoid solver failures during edits.

## Manufacturing Considerations
N/A — learning exercise, though the shell operation here mirrors real enclosure design (wall thickness selection).

## Material Suggestions
N/A — if made real, ABS or PLA would be suitable for a 3D-printed version.

## Improvements
Practice combining shell + pattern to model something closer to a real enclosure with mounting bosses.

## Time Taken
~1 hour

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
