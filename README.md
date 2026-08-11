# I ❤️ IGS — CAD Viewer & Technical Drawing Documentation

<p align="center">
  <strong>Practical documentation for viewing, inspecting, measuring, and creating technical drawing workflows from CAD files in the browser.</strong>
</p>

<p align="center">
  <a href="https://www.iloveigs.com/"><strong>🌐 Open iLoveIGS</strong></a>
  &nbsp;•&nbsp;
  <a href="https://www.iloveigs.com/"><strong>Try the Online CAD Viewer</strong></a>
</p>

<p align="center">
  📱 Mobile &nbsp;•&nbsp; 📲 Tablet &nbsp;•&nbsp; 💻 Laptop &nbsp;•&nbsp; 🖥️ Desktop
</p>

---

## 📖 About This Documentation

Welcome to the documentation hub for **iLoveIGS**, a browser-based CAD viewer and technical drawing workspace for supported engineering and drawing formats.

This repository is written for people who work with CAD in the real world: **mechanical engineers, CAD designers, CNC programmers, VMC machinists, manufacturing teams, students, educators, and anyone who needs to inspect a CAD file quickly.**

The documentation explains both the product and the concepts behind common CAD exchange workflows. It is intended to be useful even when you are simply trying to answer a question such as:

> *“I received an IGES or STEP file. How can I open it, inspect the geometry, check dimensions, and understand the model without installing a full CAD package?”*

🌐 **iLoveIGS:** https://www.iloveigs.com/

---

## ⚡ What You Can Do with iLoveIGS

Depending on the file type and current application capabilities, iLoveIGS can be used for:

- 🔓 Opening supported CAD and drawing files in a web browser
- 🧊 Inspecting 3D geometry
- 🔭 Orbiting, panning, zooming, and fitting models
- 🧭 Switching between standard engineering views
- 📏 Checking point-to-point measurements and coordinate differences
- 📐 Reviewing overall model dimensions
- 📝 Moving from 3D inspection into technical drawing workflows
- 🖨️ Preparing drawing layouts for printing or PDF output where supported
- 🔗 Sharing a useful model-view state where the application provides that capability

> **Feature note:** iLoveIGS continues to evolve. File-format support, controls, and individual features may change. The live application is the authoritative source for the current feature set.

---

## 📱 Cross-Device & Cross-Platform Access

iLoveIGS is designed as a browser-based experience and can be accessed from modern devices, including:

| Device | Typical Use |
| :--- | :--- |
| 📱 **Mobile phone** | Quick file/reference checks and lightweight inspection |
| 📲 **Tablet** | Portable CAD review and drawing/reference work |
| 💻 **Laptop** | General CAD inspection and engineering workflows |
| 🖥️ **Desktop** | Larger models, detailed inspection, measurement, and drafting |

The experience depends on the device, browser, graphics capabilities, screen size, file complexity, and the feature being used. Large or highly detailed 3D models generally benefit from a more capable desktop or laptop.

---

# 📚 Documentation

### 🟢 Start Here

- [Getting Started](docs/getting-started.md) — First steps, file loading, interface orientation, and basic navigation.
- [CAD Viewer Controls](docs/cad-viewer.md) — Mouse controls, display modes, camera movement, and standard views.

### 📐 CAD Inspection

- [IGES Files](docs/iges-files.md) — IGES concepts, extensions, viewing considerations, and practical tips.
- [STEP Files](docs/step-files.md) — STEP basics, solid-model exchange, and viewing considerations.
- [Measurement Tools](docs/measurement-tools.md) — Point-to-point measurement, deltas, bounding dimensions, and verification guidance.

### 📝 Drafting

- [Technical Drawing & Drafting](docs/drafting.md) — Standard views, drawing-sheet workflows, title blocks, dimensions, and printing.

### 🧰 Support

- [Troubleshooting](docs/troubleshooting.md) — Common browser, WebGL, file-loading, performance, and display issues.

---

# 📖 Practical Guides

These guides go beyond product instructions and explain the CAD concepts behind common workflows.

- [IGES vs STEP](guides/iges-vs-step.md) — Understand the practical differences between the two exchange formats.
- [How to Open an IGES File Online](guides/how-to-open-iges.md) — A step-by-step workflow for opening `.igs` and `.iges` files.
- [Browser-Based CAD Viewer Guide](guides/cad-file-viewer-guide.md) — When an online viewer makes sense and what to consider before using one.

---

# 🧪 Examples & Resources

The `examples/` directory is reserved for small, practical CAD-learning examples and reproducible documentation workflows.

The `assets/` directory is reserved for documentation images, diagrams, screenshots, and other visual resources.

```text
iloveigs-documentation/
│
├── README.md
│
├── docs/
│   ├── getting-started.md
│   ├── iges-files.md
│   ├── step-files.md
│   ├── cad-viewer.md
│   ├── measurement-tools.md
│   ├── drafting.md
│   └── troubleshooting.md
│
├── guides/
│   ├── iges-vs-step.md
│   ├── how-to-open-iges.md
│   └── cad-file-viewer-guide.md
│
├── examples/
└── assets/
```

---

# 🧩 Supported Formats

The documentation currently covers workflows around commonly encountered formats such as:

- **IGES / IGS** — `.igs`, `.iges`
- **STEP / STP** — `.step`, `.stp`
- **STL** — `.stl`
- **DXF** — `.dxf`
- **DWG** — `.dwg`
- **PDF** — `.pdf`

Actual support and available operations depend on the current iLoveIGS application and the characteristics of the file being opened.

---

# 🛠️ Technology Overview

The iLoveIGS ecosystem uses modern browser technologies for CAD visualization and document workflows. Depending on the feature, the technology stack includes:

- **Three.js / WebGL** — 3D rendering and visualization
- **OpenCASCADE-based WebAssembly tooling** — CAD geometry processing for supported formats
- **occt-import-js** — WebAssembly-based CAD import tooling
- **DXF parsing technology** — 2D CAD data workflows
- **PDF.js** — PDF rendering workflows
- **HTML, CSS & JavaScript** — Browser application and interface

Third-party projects remain governed by their own licenses and documentation.

---

# 🎯 Who Is This For?

This documentation is especially useful for:

- 👷 Mechanical engineers
- 🧑‍💻 CAD designers
- ⚙️ CNC programmers
- 🏭 VMC machinists
- 🛠️ Manufacturing engineers
- 📐 Tool and die designers
- 🎓 Engineering students
- 🧪 Prototype and product teams
- 🔧 CAD/CAM professionals
- 📋 Teams reviewing supplier or customer CAD data

---

# 🔍 A Practical CAD Inspection Workflow

A typical workflow looks like this:

**1. Receive the file** → **2. Open it in iLoveIGS** → **3. Fit the model** → **4. Check standard views** → **5. Inspect geometry** → **6. Measure important features** → **7. Create/review drawing views** → **8. Verify against authoritative engineering data**

This repository explains each stage in more detail so that the documentation remains useful beyond the application itself.

---

# 🤝 Documentation Principles

We aim to keep this project:

- ✅ Practical rather than promotional
- ✅ Clear enough for beginners
- ✅ Detailed enough for experienced CAD users
- ✅ Honest about limitations and file-format differences
- ✅ Focused on real engineering workflows
- ✅ Easy to navigate and maintain

For manufacturing-critical decisions, always verify dimensions and requirements against the authoritative CAD model, engineering drawing, specification, or other controlled source.

---

# 🌐 iLoveIGS

**Try the live application:**

👉 https://www.iloveigs.com/

The website is the current source for the latest available tools and supported workflows.

---

## ❤️ Built for the CAD Community

iLoveIGS is focused on making everyday CAD inspection more accessible through the browser — whether you are at a workstation, on a laptop, using a tablet, or checking something from a phone.

<p align="center">
  <strong>Open CAD. Inspect Geometry. Understand Your Model.</strong>
  <br><br>
  <a href="https://www.iloveigs.com/">🌐 Explore iLoveIGS</a>
</p>
