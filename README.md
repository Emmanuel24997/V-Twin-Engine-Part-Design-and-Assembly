# V-Twin-Engine-Part-Design-and-Assembly Project

A custom V-Twin engine assembly modeled and simulated in SOLIDWORKS, highlighting precise component design, thermodynamic-to-mechanical motion conversion, and 90° cylinder orientation.

## 📸 Visual Showcase

![V-Twin Engine Assembly](Renders/isometric-view.png)

## 📊 Technical Specifications

| Parameter | Specification |
| :--- | :--- |
| **Engine Configuration** | V-Twin Engine (90° Cylinder Orientation) |
| **Core Components** | Piston, Crankshaft, Connecting Rod, Cylinder Block |
| **Material Selection** | 1.4122 (X39CrMo17-1) Stainless Steel (Pistons) |
| **CAD Software** | SOLIDWORKS |

## ⚙️ Design & Manufacturing Highlights

* **Precision Component Modeling:** Modeled parts entirely from scratch, utilizing core features such as Extrude Boss and Extrude Cut for pistons, and mastering the *Offset Entities* tool during connecting rod development.
* **Kinematic Power Conversion:** Engineered the assembly to accurately translate linear piston reciprocation (during compression and expansion strokes) into smooth rotational crankshaft output.
* **Detail-Oriented Engineering:** Addressed critical micro-details like fillet radiusing to prevent cyclic loading crack initiation and ensure proper component seating.
* **90° V-Block Assembly Configuration:** Implemented precise coincident mates linking the pistons, connecting rods, and crankshaft, orienting the two cylinders at a 90° angle to each other.
* **Real-World Functional Focus:** Balanced theoretical thermodynamic principles with strict geometric precision to ensure physical assembly viability.

## 📁 Repository Directory Structure

```text
v-twin-engine-design/
├── CAD/
│   ├── V_Twin_Assembly.SLDASM
│   └── ...
├── Renders/
│   └── isometric-view.png
├── Animations/
│   └── motion-study.mp4
└── Docs/
    └── specs.txt
_______Drawings/ V_Twin_Assembly.SLDRW
