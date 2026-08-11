# I ❤️ IGS — Free Online CAD & Drawing Viewer

<p align="center">
  <strong>Browser-based CAD viewer and technical drawing workspace for IGES, STEP, STL, DXF, DWG, and PDF files.</strong>
</p>

<p align="center">
  <a href="https://www.iloveigs.com/">
    <strong>🌐 Visit iLoveIGS — www.iloveigs.com</strong>
  </a>
</p>

---

## 🚀 About iLoveIGS

**iLoveIGS** is an online CAD file viewer and technical drawing workspace designed for engineers, designers, machinists, manufacturing professionals, students, and CAD users.

It provides browser-based tools for opening, inspecting, measuring, and working with supported CAD and drawing files without requiring traditional desktop CAD software.

The platform focuses on practical CAD inspection workflows, including:

- 3D CAD model visualization
- IGES and STEP file viewing
- CAD model measurement
- Bounding-box dimensions
- Standard engineering views
- Technical drawing generation
- 2D drafting workflows
- CAD-style model navigation
- Drawing and PDF workflows

🌐 **Website:** https://www.iloveigs.com/

> **Important:** File processing and privacy behavior may depend on the specific feature and implementation. Refer to the live website for the current behavior of each tool.

---

## 🌟 Why iLoveIGS?

### No Traditional CAD Installation

iLoveIGS runs directly in a modern web browser, making CAD inspection accessible without installing a large desktop CAD application.

### CAD-Focused Workflow

The interface is designed around common engineering inspection tasks such as viewing geometry, changing standard views, measuring models, and preparing technical drawings.

### Multiple CAD Formats

The platform supports several commonly used engineering and technical file formats.

### Browser-Based Experience

Users can access the tools from supported desktop browsers without requiring a dedicated CAD workstation for basic viewing and inspection workflows.

---

# 📂 Supported File Formats

| Format | File Extension | Typical Use |
| :--- | :--- | :--- |
| **IGES** | `.igs`, `.iges` | CAD data exchange |
| **STEP** | `.step`, `.stp` | 3D product and CAD data exchange |
| **STL** | `.stl` | 3D mesh and manufacturing models |
| **DXF** | `.dxf` | 2D CAD drawings |
| **DWG** | `.dwg` | CAD drawing data |
| **PDF** | `.pdf` | Technical drawings and documents |

> Format support and available operations can change as iLoveIGS evolves. Check the live application for the latest capabilities.

---

# ✨ Key Features

## 1. 3D CAD Model Inspection

iLoveIGS provides tools for inspecting 3D CAD geometry directly in the browser.

Features include:

- Shaded model display
- Edge visualization
- Interactive orbit
- Pan
- Zoom
- Dynamic camera movement
- Standard engineering views
- Isometric view
- Front view
- Back view
- Left view
- Right view
- Top view
- Bottom view
- Model fitting
- Bounding-box information

These tools make it easier to quickly understand the geometry and overall dimensions of a CAD model.

---

## 2. CAD-Style Navigation

The viewer provides interactive controls designed around common CAD inspection workflows.

Depending on the active tool and application mode, users can work with:

- Geometry selection
- Window selection
- Crossing selection
- Pan
- Orbit
- Zoom
- Fit-to-model
- Contextual display controls

The goal is to make browser-based CAD inspection feel familiar to users who already work with professional engineering software.

---

## 3. Measurement Tools

Measurement is an important part of CAD inspection.

iLoveIGS provides tools for examining model geometry and obtaining dimensional information.

### Point-to-Point Measurement

Users can select points on a model to calculate:

- 3D distance
- Delta X
- Delta Y
- Delta Z

The measurement workflow can provide a visual measurement line between selected points.

---

## 4. Model Dimensions

The viewer can provide overall model dimensions based on the model bounding box.

Typical dimensional information includes:

```text
X Dimension
Y Dimension
Z Dimension
```

This is useful for quickly understanding the approximate overall size of a loaded model.

---

# 📐 Technical Drawing & Drafting

iLoveIGS extends beyond basic 3D viewing with a technical drawing workflow.

The drafting workspace is designed to help users create an engineering-style representation of a 3D model.

### Drawing Views

Supported drawing workflows can include views such as:

- Front
- Top
- Right
- Isometric

### Drawing Sheet

The technical drawing workspace can arrange model views on a drawing-sheet layout with:

- Drawing borders
- View placement
- Dimensions
- Title-block information
- Printable drawing layout

### Print Workflow

The drawing workspace is designed with printing in mind, allowing the technical drawing area to be separated from the surrounding application interface when printing.

---

# 🔗 Shareable CAD View

iLoveIGS can provide shareable camera/view information for supported workflows.

A generated link can contain information describing the current viewing state, such as:

- Camera position
- Camera target
- Camera orientation
- Zoom
- Display mode

This can make it easier to communicate a particular model view with another person.

---

# 🛠️ Technical Specifications

iLoveIGS is designed as a modern browser-based CAD application.

| Component | Technology |
| :--- | :--- |
| 3D Rendering | Three.js / WebGL |
| STEP / IGES Processing | OpenCASCADE-based WebAssembly tooling |
| DXF Processing | DXF parsing technology |
| PDF Processing | PDF.js |
| Application Architecture | Browser-based JavaScript |
| Module System | ES Modules |
| 3D Visualization | WebGL |
| UI | HTML / CSS / JavaScript |

### Open-Source Technologies

The project ecosystem makes use of established open-source technologies and libraries where applicable.

- [Three.js](https://threejs.org/)
- [OpenCASCADE](https://www.opencascade.com/)
- [occt-import-js](https://github.com/kovacsv/occt-import-js)
- [dxf-parser](https://github.com/gdsestimating/dxf-parser)
- [PDF.js](https://mozilla.github.io/pdf.js/)

Each third-party project remains subject to its own license and terms.

---

# 🧑‍💻 Who Can Use iLoveIGS?

iLoveIGS can be useful for:

- Mechanical engineers
- CAD designers
- CNC programmers
- VMC machinists
- Manufacturing engineers
- Product designers
- Tool designers
- Students
- Engineering educators
- CAD/CAM professionals
- Manufacturing companies
- Prototype developers
- Hobbyists working with CAD models

---

# 🔍 Common CAD Workflows

iLoveIGS can be useful for workflows such as:

### CAD Model Inspection

Open a supported CAD file and inspect its geometry from different standard views.

### Manufacturing Preparation

Quickly inspect a model before machining or manufacturing.

### Dimension Checking

Use model measurements and bounding dimensions to understand geometry.

### Technical Drawing Reference

Generate or inspect drawing views for engineering communication.

### CAD File Review

Review CAD files without necessarily opening a full desktop CAD package.

---

# 📚 Documentation

This repository is intended to become the documentation and knowledge hub for iLoveIGS.

Documentation will cover topics including:

- [Getting Started](docs/getting-started.md)
- [IGES Files](docs/iges-files.md)
- [STEP Files](docs/step-files.md)
- [STL Files](docs/stl-files.md)
- [CAD Viewer](docs/cad-viewer.md)
- [Measurement Tools](docs/measurement-tools.md)
- [Technical Drafting](docs/drafting.md)
- [Troubleshooting](docs/troubleshooting.md)

More documentation will be added as the platform develops.

---

# 📖 CAD Guides

The repository can also contain educational resources covering topics such as:

- What is an IGES file?
- What is a STEP file?
- IGES vs STEP
- How to open IGES files
- How to open STEP files
- CAD file formats explained
- 3D CAD viewer workflows
- CAD model measurement
- Technical drawing basics
- Engineering drawing views
- CAD inspection workflows
- CAD data exchange

These resources are intended to provide practical information for engineers, designers, machinists, students, and CAD users.

---

# 🌐 iLoveIGS Website

The main iLoveIGS application is available at:

**https://www.iloveigs.com/**

Visit the website to access the latest version of the online CAD tools.

---

# 🤝 Contributing

Suggestions, documentation improvements, examples, and technical discussions are welcome.

If you discover an issue or have an idea for improving the documentation, please open an issue in this repository.

When contributing documentation, please aim for:

- Accurate technical information
- Clear explanations
- Practical examples
- Reproducible workflows
- Useful references
- CAD-focused terminology

---

# 📜 License

The documentation and original materials in this repository are provided under the license specified in the repository.

Third-party libraries, tools, specifications, and resources remain subject to their respective licenses and terms.

---

## ❤️ About This Project

iLoveIGS is built to make CAD inspection and technical drawing workflows more accessible through the web.

The project focuses on practical engineering use cases and browser-based CAD tools.

<p align="center">
  <strong>Explore CAD. Inspect Geometry. Create Drawings.</strong>
  <br><br>
  <a href="https://www.iloveigs.com/">
    🌐 Try iLoveIGS
  </a>
</p>
