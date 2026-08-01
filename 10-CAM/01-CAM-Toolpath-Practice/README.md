# CAM Toolpath Practice — Simple Milled Plate

## Objective
Use Fusion 360's Manufacture workspace to program basic 2.5-axis CNC toolpaths (facing, pocketing, drilling, contouring) for a simple milled plate, and simulate the cut to check for collisions and gouging.

## Skills Practiced
- Setup (stock, WCS, fixturing)
- Facing
- 2D Pocket
- 2D Contour
- Drilling cycles
- Toolpath simulation

## CAD Features Used
- No new solid-modeling features — this folder documents CAM programming on an existing part

## Challenges
- Simulation showing rapid moves plunging through the stock in one pocket operation.
- Choosing realistic feeds/speeds for the assumed tool and material.

## How I Solved Them
Corrected the lead-in/lead-out and ramp settings on the pocket operation so the tool plunges via a ramp rather than a straight vertical plunge, then re-ran the simulation to confirm a clean, gouge-free toolpath.

## Engineering Notes
CAM is where a design either proves itself manufacturable or reveals problems (unreachable features, thin walls that chatter) that solid modeling alone won't show — simulating every toolpath before trusting it is non-negotiable.

## Manufacturing Considerations
Toolpaths assume a 3-axis vertical mill with standard end mills; operations were sequenced roughing-to-finishing to protect part accuracy.

## Material Suggestions
Aluminum 6061, a common and forgiving material for practicing CNC milling.

## Improvements
Practice adaptive clearing for roughing instead of standard 2D pocketing to improve tool life and cycle time.

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
