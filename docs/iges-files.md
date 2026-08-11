# 🔷 IGES Files — Practical Guide

**IGES (Initial Graphics Exchange Specification)** is a long-established CAD data exchange format used to transfer geometric and drawing information between engineering systems.

Common file extensions are:

```text
.igs
.iges
```

🌐 **Open iLoveIGS:** https://www.iloveigs.com/

---

## 🧩 What Is an IGES File?

IGES was created to help different CAD systems exchange design information when native CAD formats were not compatible.

Depending on the source system, an IGES file can contain entities such as:

- Lines
- Arcs
- Curves
- Surfaces
- B-spline geometry
- Trimmed surfaces
- Solid-related geometry
- Drawing information

The exact contents depend on the software and export settings used to create the file.

---

## 🔍 Opening an IGES File in iLoveIGS

A typical workflow is:

1. 🌐 Open **https://www.iloveigs.com/**.
2. 📂 Use the available file-opening workflow.
3. 🔷 Select your `.igs` or `.iges` file.
4. ⏳ Allow the browser to process the geometry.
5. 🧊 Fit the model to the viewport.
6. 🧭 Check standard views.
7. 📏 Measure geometry when required.

For a complete walkthrough, see [How to Open an IGES File Online](../guides/how-to-open-iges.md).

---

## 🏭 Why IGES Is Still Common

Although newer exchange standards are widely used, IGES remains present in many real engineering environments because of:

- Legacy CAD data
- Supplier/customer exchange requirements
- Older manufacturing archives
- Surface-model workflows
- Compatibility with established engineering systems

This means engineers and machinists can still encounter IGES files regularly.

---

## 🧊 IGES and Surface Geometry

One important characteristic of IGES is that files can represent geometry through individual surfaces and curves rather than behaving like a single watertight solid model.

This can matter when viewing or manufacturing from converted geometry.

A model may appear visually correct while still containing:

- Gaps between surfaces
- Overlapping faces
- Missing boundaries
- Small geometric inconsistencies
- Unstitched surfaces

These conditions are generally properties of the source/export workflow rather than something unique to a particular viewer.

---

## 🎨 Why Edges May Look Different

A CAD viewer may generate a visual edge representation from the geometry it receives. If the source geometry contains many small surface boundaries or complex tessellation, visible edges can differ from what you expect from the originating CAD system.

If the model looks unusual:

1. Try another display mode.
2. Fit the model.
3. Inspect several standard views.
4. Check the source file in the originating CAD system if the geometry is critical.
5. Consider requesting a STEP export when the downstream workflow supports it.

---

## 🔷 IGES vs STEP

Both are CAD exchange standards, but they are not interchangeable in how they represent and communicate engineering data.

For many modern 3D product-data workflows, **STEP is often the preferred exchange option** when both systems support it.

See the detailed [IGES vs STEP guide](../guides/iges-vs-step.md).

---

## 🧠 Practical Tips for Engineers & Machinists

Before using an IGES model for manufacturing decisions:

- Confirm the model units.
- Check the overall dimensions.
- Inspect the critical features from multiple views.
- Measure important geometry carefully.
- Check whether the model is a solid or surface-based representation.
- Compare critical dimensions with the controlled drawing/specification.
- Keep the original source file available for traceability.

---

## 🔗 Related Resources

- [Getting Started](getting-started.md)
- [STEP Files](step-files.md)
- [Measurement Tools](measurement-tools.md)
- [IGES vs STEP](../guides/iges-vs-step.md)
- [iLoveIGS](https://www.iloveigs.com/)
