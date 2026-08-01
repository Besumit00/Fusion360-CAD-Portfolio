# Parametric Mounting Bracket

## Objective
Design a mounting bracket entirely through user parameters, so that bolt spacing, bracket length, and thickness can be changed instantly without re-modeling any feature — a core skill for real design engineering work.

## Skills Practiced
- User parameters
- Parametric relationships between dimensions
- Configurations via parameter sets
- Design intent planning

## CAD Features Used
- Sketch (parameter-driven dimensions)
- Extrude
- Fillet
- Pattern (parameter-driven spacing)

## Challenges
- Sketches breaking when a parameter was changed to an extreme value.
- Deciding which dimensions should be independent vs derived from other parameters.

## How I Solved Them
Added parameter equations (e.g., hole_spacing = bracket_length / 3) instead of hardcoding values, and tested the model at minimum and maximum realistic parameter values to confirm it didn't break.

## Engineering Notes
True parametric design means defining relationships between dimensions, not just naming dimensions — this is what allows a single model to represent an entire family of parts.

## Manufacturing Considerations
Parameters were kept within realistic sheet/plate stock sizes so the bracket stays manufacturable at any configuration within the tested range.

## Material Suggestions
Aluminum 6061 for a lightweight, corrosion-resistant bracket.

## Improvements
Turn this into a full configuration table (small/medium/large) using Fusion's configuration tool.

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
