# Nut & Bolt Assembly

## Objective
Model a hex bolt and matching hex nut as separate components, then join them in an assembly using joints and motion constraints to simulate a real threaded fastener coming together.

## Skills Practiced
- Multi-component assemblies
- Rigid & revolute joints
- Joint origins
- Component patterning in assemblies
- Interference detection

## CAD Features Used
- Sketch
- Revolve (bolt shank/head)
- Extrude (hex profile)
- Thread tool (modeled threads)
- Joints (Rigid, Revolute)

## Challenges
- Getting the bolt and nut to align concentrically without manually dragging components.
- Avoiding creating in-context 'sketch links' between components that make files fragile.

## How I Solved Them
Used joint origins placed on the central axis of each part and applied a Rigid joint (with a Revolute joint on a duplicate) so the bolt could be spun in to simulate tightening, without ever linking sketches across components.

## Engineering Notes
This project taught me the difference between constraining components (older Fusion workflow) and the modern Joints workflow, which I now use by default for anything that will move or needs a defined mate.

## Manufacturing Considerations
Designed to real M8 x 1.25 thread pitch dimensions so it could theoretically be manufactured or ordered as a standard fastener rather than custom-machined.

## Material Suggestions
Steel (grade 8.8) for the bolt and nut, as would be standard for a general-purpose fastener.

## Improvements
Add a washer component and a simple bracket to bolt the assembly through, to practice a 3-component stack-up.

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
