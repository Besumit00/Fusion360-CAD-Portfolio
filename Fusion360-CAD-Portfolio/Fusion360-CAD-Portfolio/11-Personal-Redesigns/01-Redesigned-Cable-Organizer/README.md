# Redesigned Desk Cable Organizer

## Objective
Reverse-engineer and improve an everyday household object (a desk cable organizer) by measuring the original, modeling it in Fusion 360, and iterating on the design to fix real usability problems I identified with the original product.

## Skills Practiced
- Reverse engineering from physical measurements
- Iterative design improvement
- Fit/tolerance for snap-fit features
- 3D-print-aware design (overhangs, wall thickness)

## CAD Features Used
- Sketch
- Extrude
- Fillet
- Shell
- Snap-fit cantilever clip design

## Challenges
- The original snap-fit clip was too stiff to insert/remove cables easily by hand.
- Balancing wall thickness for 3D-printability against structural strength.

## How I Solved Them
Reduced the cantilever clip thickness and increased its length slightly to lower the insertion force while keeping enough retention force to hold a cable in place, based on basic cantilever beam deflection reasoning rather than pure guesswork.

## Engineering Notes
Redesigning something physical (rather than following a tutorial) forced me to think about tolerances, print orientation, and real user interaction — this is the closest folder in this repo to genuine product-design practice.

## Manufacturing Considerations
Modeled specifically for FDM 3D printing: minimum wall thickness 1.2 mm, no unsupported overhangs beyond 45°, chamfered edges to avoid print-bed lift.

## Material Suggestions
PETG for its balance of flexibility (for the snap-fit clip) and durability.

## Improvements
Test-print an actual prototype and iterate the clip geometry based on measured insertion force.

## Time Taken
~2.5 hours

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
