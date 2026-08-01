# 6-DOF Robotic Arm

## Objective
Design a fully articulated 6 degree-of-freedom robotic arm in Fusion 360, including individually modeled links, joints, and a base — built as a bridge between pure CAD practice and real robotics work, and exported as a URDF-ready assembly.

## Skills Practiced
- Multi-body, multi-component assembly design
- Revolute joints matching real servo/actuator specs
- Joint limits and motion studies
- Designing for a URDF export workflow
- Mass/inertia-aware modeling for simulation accuracy

## CAD Features Used
- Sketch, Extrude, Revolve for individual links
- Joints (Revolute x6)
- Motion Study / Animation
- Assembly-level interference checks
- Component mass properties (for URDF inertial tags)

## Challenges
- Getting joint axes to align exactly with intended rotation axes so the eventual URDF export wouldn't need manual correction.
- Keeping the assembly light enough to simulate joint motion smoothly in Fusion without lag.
- Deciding realistic joint torque/range limits based on hobby servo specifications rather than arbitrary numbers.

## How I Solved Them
Placed each joint origin on a dedicated construction axis defined before modeling the surrounding geometry, so every revolute joint's rotation axis was guaranteed correct by construction rather than fixed up after the fact. Simplified visual geometry (fewer fillets on non-functional edges) to keep the assembly responsive during motion studies.

## Engineering Notes
This project directly informed how I approached the ROS2 delivery robot below — modeling joint axes deliberately, and thinking in terms of links/joints from the start, made the later URDF work far faster since the CAD geometry was already 'robot-description-ready'.

## Manufacturing Considerations
Structural links are sized to be 3D-printable in one piece per link, with servo mounting pockets matching standard hobby servo horn patterns for real-world buildability.

## Material Suggestions
PLA/PETG for printed links, with steel fasteners and standard hobby servos at each joint for an actual physical build.

## Improvements
Add gripper end-effector as its own sub-assembly and formalize the URDF export with proper inertial and collision geometry.

## Time Taken
~15 hours across multiple sessions

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
