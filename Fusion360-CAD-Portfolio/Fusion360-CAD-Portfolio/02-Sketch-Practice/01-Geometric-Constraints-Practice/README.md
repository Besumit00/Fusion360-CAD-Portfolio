# Geometric Constraints Practice

## Objective
Build a series of 2D sketches that deliberately use every major geometric constraint (coincident, collinear, parallel, perpendicular, tangent, symmetric, equal) to fully understand Fusion 360's constraint solver.

## Skills Practiced
- Geometric constraints
- Dimensional constraints
- Sketch dimensions and driven vs driving dimensions
- Fully defined sketch discipline

## CAD Features Used
- Sketch only (no 3D features) — this folder is a pure sketch-skill exercise

## Challenges
- The solver occasionally over-constrained a sketch and threw conflict warnings.
- Understanding when to use 'Equal' vs manually dimensioning every entity.

## How I Solved Them
Deleted conflicting constraints one at a time using the 'Sketch Palette' conflict warnings, then rebuilt the constraint chain more deliberately, starting from a single anchored point.

## Engineering Notes
A fully constrained sketch (all black/green geometry) is the single biggest predictor of a stable, editable parametric model downstream — this exercise was about building that discipline early.

## Manufacturing Considerations
N/A — sketch-only exercise.

## Material Suggestions
N/A

## Improvements
Practice sketch-driven patterns (rectangular/circular sketch patterns) on top of fully constrained base sketches.

## Time Taken
~45 minutes

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
