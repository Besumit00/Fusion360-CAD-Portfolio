# Bracket Engineering Drawing

## Objective
Take a simple L-bracket model and produce a fully dimensioned, manufacturing-ready 2D engineering drawing sheet, including title block, views, and tolerances.

## Skills Practiced
- Drawing views (base, projected, section, detail)
- Dimensioning standards
- Title block editing
- GD&T basics
- Sheet/border setup

## CAD Features Used
- Base View
- Projected View
- Section View
- Ordinate & linear dimensioning
- Title block fields

## Challenges
- Keeping dimensions readable without overlapping on a compact sheet.
- Deciding which dimensions were functionally necessary vs redundant.

## How I Solved Them
Used ordinate dimensioning for the repetitive hole pattern instead of individual linear dimensions for every hole, which cleaned up the sheet significantly and matched how the part would actually be measured on a CMM.

## Engineering Notes
A good drawing should only carry the dimensions a machinist actually needs to make the part correctly — over-dimensioning is as much a defect as under-dimensioning.

## Manufacturing Considerations
Drawing follows ANSI Y14.5 style conventions; hole callouts specify drill size and depth directly usable by a machine shop.

## Material Suggestions
Mild steel (A36) sheet, bent and drilled.

## Improvements
Add a formal GD&T frame (flatness/position callouts) once I've studied tolerancing in more depth.

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
