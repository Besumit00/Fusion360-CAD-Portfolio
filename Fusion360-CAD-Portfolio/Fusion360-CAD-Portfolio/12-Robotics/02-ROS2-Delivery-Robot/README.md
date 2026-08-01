# ROS2 Delivery Robot — Mechanical Design

## Objective
Design the mechanical chassis and drivetrain housing for a ROS2-based autonomous delivery robot, modeled to match the URDF used in simulation and to house real sensors (LiDAR/camera) and drive motors.

## Skills Practiced
- Chassis design for differential-drive mobile robots
- Sensor mount design (LiDAR, camera) with correct sensor-frame offsets
- Motor/wheel mounting and ground clearance planning
- CAD-to-URDF consistency (link dimensions matching the ROS2 description package)
- Cable routing and access-panel design

## CAD Features Used
- Sketch, Extrude for chassis plates
- Shell (motor housings)
- Pattern (mounting hole arrays)
- Assembly joints matching the robot's kinematic tree
- Fillet/Chamfer for edge safety and print quality

## Challenges
- Keeping the CAD model's link origins consistent with the ROS2 URDF/TF tree so simulation (Gazebo/RViz) matched the physical design.
- Fitting the LiDAR, drive motors, battery, and controller board within a compact footprint without collisions.
- Ensuring enough ground clearance for the differential drive wheels without raising the center of gravity too much.

## How I Solved Them
Defined all chassis reference geometry relative to a single 'base_link' origin matching the URDF convention, and cross-checked sensor mount positions against the TF tree used in the ROS2 stack before finalizing dimensions. Used a layered chassis (motor deck below, electronics deck above) to solve the packaging/clearance conflict.

## Engineering Notes
This is the project where CAD stopped being an isolated skill and became part of a full robotics pipeline — the mechanical design here directly feeds the URDF, which feeds simulation in Gazebo, which feeds the navigation stack. Getting frame conventions right in CAD saves significant debugging time later in ROS2.

## Manufacturing Considerations
Chassis plates designed for either laser-cut acrylic/aluminum (flat plates) or 3D-printed brackets, chosen per component based on load and cost.

## Material Suggestions
6061 aluminum or laser-cut acrylic for structural plates; PETG for printed sensor/motor mounts.

## Improvements
Add a swappable battery tray and formalize a full mechanical BOM alongside the existing ROS2 software stack.

## Time Taken
~20+ hours across multiple sessions

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
