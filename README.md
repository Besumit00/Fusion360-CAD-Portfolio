# 🛠️ Fusion360-CAD-Portfolio

**An engineering portfolio documenting my journey from beginner CAD sketches to industrial robotics design — built one project at a time in Autodesk Fusion 360.**

![Fusion 360](https://img.shields.io/badge/CAD-Fusion%20360-orange)
![Status](https://img.shields.io/badge/Status-Actively%20Learning-brightgreen)
![Focus](https://img.shields.io/badge/Focus-Robotics%20%26%20Mechanical%20Design-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📖 About This Portfolio

This repository is not a folder of random tutorial exports — it's a structured, chronological record of how I learned mechanical CAD design, from my first fully-constrained sketch through to multi-body robotic assemblies. Every project has its own folder with source CAD files, renders, and a full engineering write-up covering objective, challenges, engineering reasoning, and manufacturing considerations.

I'm building this in public because I believe an engineer's portfolio should show **process**, not just polished final renders — the mistakes, the fixes, and the reasoning behind design decisions are what actually demonstrate engineering judgment.

## 👋 About Me

I'm an **AI and Robotics** student at **Madhav Institute of Technology and Science (MITS), Gwalior**, building toward a career as a **Robotics Design Engineer**. My core toolset is Fusion 360 for mechanical design, paired with ROS2/URDF for bringing that design into robotics simulation and control.

Flagship projects driving this portfolio:
- 🦾 A **6-DOF robotic arm** — full CAD design from individual links to a joint-driven assembly, structured for URDF export.
- 🤖 A **ROS2 delivery robot** — mechanical chassis and sensor-mount design built to be consistent with its ROS2 URDF/TF tree for simulation in Gazebo/RViz.

I'm currently seeking **internship and entry-level roles in CAD design and robotics**.

## 📌 Current Learning Status

| Area | Status |
|---|---|
| Core Sketching & Solid Modeling | ✅ Comfortable |
| Assemblies & Joints | ✅ Comfortable |
| Drawings (GD&T basics) | 🟡 Learning |
| Sheet Metal | 🟡 Learning |
| Surface Modeling | 🟡 Learning |
| Parametric / Configuration Design | 🟡 Learning |
| Rendering | 🟢 Comfortable |
| CAM / CNC Toolpaths | 🟡 Learning |
| Robotics-focused CAD (URDF-ready modeling) | 🟢 Active Focus |

See [`00-Portfolio/Learning-Roadmap.md`](./00-Portfolio/Learning-Roadmap.md) and [`Skills-Tracker.md`](./Skills-Tracker.md) for the full breakdown.

## 🗂️ Repository Structure

```
Fusion360-CAD-Portfolio/
│
├── README.md                     → You are here
├── LICENSE
├── .gitignore
├── Learning-Tracker.md           → Chronological log of every project
├── Skills-Tracker.md             → Feature-by-feature proficiency tracker
├── Project-Index.md              → Direct links to every project folder
│
├── 00-Portfolio/                 → About me, roadmap, skills summary
├── 01-Beginner/                  → First sketches, extrudes, fundamentals
├── 02-Sketch-Practice/           → Geometric & dimensional constraint drills
├── 03-Feature-Practice/          → Fillet, chamfer, pattern, shell drills
├── 04-Assemblies/                → Multi-component assemblies & joints
├── 05-Drawings/                  → 2D engineering drawings, GD&T
├── 06-Sheet-Metal/               → Bent sheet metal parts & flat patterns
├── 07-Surface-Modeling/          → Organic/surfaced geometry
├── 08-Parametric-Design/         → Parameter-driven, configurable models
├── 09-Rendering/                 → Studio renders & presentation visuals
├── 10-CAM/                       → CNC toolpath programming & simulation
├── 11-Personal-Redesigns/        → Reverse-engineered, improved products
├── 12-Robotics/                  → 🦾 Flagship robotics CAD projects
├── 30-Day-Challenge/             → 🎥 Daily Fusion 360 challenge (YouTube companion series)
├── Machine-Design-Practice-Pack/ → 🔩 25-part mechanical practice set (Curtis Waguespack / KKMSoft)
└── Resources/                    → Cheat sheets, notes, reference links
```

Every individual project folder follows the same layout:

```
Project-Name/
├── Images/            → front.png, isometric.png, exploded.png, etc.
├── CAD/                → Fusion360.f3d, Model.step, Model.stl
├── Drawings/           → Exported 2D drawing PDFs
└── README.md           → Full engineering write-up
```

## 🧩 Skills Learned

`Sketching` · `Extrude/Revolve/Sweep/Loft` · `Fillet & Chamfer` · `Shell` · `Mirror & Pattern` · `Assemblies & Joints` · `Motion Studies` · `Sheet Metal & Flat Patterns` · `Surface Modeling` · `Parametric Design & User Parameters` · `Rendering` · `CAM Toolpaths` · `Engineering Drawings & GD&T basics` · `URDF-ready Robotics CAD`

Full detail: [`00-Portfolio/Skills-Learned.md`](./00-Portfolio/Skills-Learned.md) · [`Skills-Tracker.md`](./Skills-Tracker.md)

## 💻 Software & Tools

| Tool | Purpose |
|---|---|
| Autodesk Fusion 360 | Primary CAD/CAM modeling environment |
| ROS2 | Robot software stack — consumes this portfolio's robotics CAD via URDF |
| URDF / Xacro | Robot description format linking CAD geometry to simulation |
| Gazebo / RViz | Simulation & visualization of modeled robots |
| Git / GitHub | Version control for this portfolio |

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Besumit00&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Besumit00&layout=compact)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Besumit00)

## 🎥 30-Day Fusion 360 Challenge

A focused, daily learning challenge documented alongside a companion **YouTube playlist** — one build a day, each with its own CAD files, images, and full write-up.

**Progress: 16 / 30 days complete** — most recent: Day 16, Auger (helical/coil-driven patterning, segmented shaft flighting).

📁 [`30-Day-Challenge/`](./30-Day-Challenge/README.md) · 📺 YouTube playlist: _link pending_

## 🔩 Machine Design Practice Pack

A 25-part mechanical modeling practice set (reference geometry credited to **Curtis Waguespack / KKMSoft**), each part modeled independently in Fusion 360 with its own isometric renders, orthographic views, and write-up.

**Progress: 4 / 25 parts documented** — Fixture Block (01), Gear Pump Body (06), Dovetail Stop Guide (08), and Truss Flange (13) complete; several more folders in progress.

📁 [`Machine-Design-Practice-Pack/`](./Machine-Design-Practice-Pack/README.md)

## 🚀 Future Projects

- [ ] Robotic gripper end-effector (parametric, interchangeable fingers)
- [ ] Full mobile robot chassis v2 with swappable battery tray
- [ ] Planetary gearbox design (parametric gear ratios)
- [ ] Multi-material 3D-printable enclosure with press-fit electronics tray
- [ ] Formal GD&T-toleranced drawing set for a manufacturable assembly

## 🦾 Robotics Roadmap

| Phase | Focus | Status |
|---|---|---|
| Phase 1 | CAD fundamentals (sketching → assemblies) | ✅ Complete |
| Phase 2 | Manufacturing-aware design (sheet metal, CAM, drawings) | 🟡 In Progress |
| Phase 3 | Robotics-specific CAD (URDF-ready links & joints) | 🟢 Active |
| Phase 4 | Full mechatronic system design (actuators, sensors, wiring integration) | ⬜ Planned |
| Phase 5 | End-to-end robot: CAD → URDF → ROS2 simulation → physical build | ⬜ Planned |

## 📬 Contact

- **Email:** sumit.0sahu2003@gmail.com
- **LinkedIn:** [linkedin.com/in/sumit-sahu-10003040a](https://www.linkedin.com/in/sumit-sahu-10003040a)
- **GitHub:** [github.com/Besumit00](https://github.com/Besumit00)

---

⭐ If you're a recruiter or fellow engineer browsing this repo — start with [`Project-Index.md`](./Project-Index.md) for direct links to every project, or jump straight to [`12-Robotics/`](./12-Robotics/) for the flagship work.
