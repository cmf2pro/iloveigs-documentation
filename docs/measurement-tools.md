# 📏 Measurement Tools

Measurement is one of the most useful parts of CAD inspection. iLoveIGS provides measurement-oriented workflows for supported 3D model inspection.

🌐 **Open iLoveIGS:** https://www.iloveigs.com/

> ⚠️ Measurements should be treated as an inspection aid. For manufacturing-critical dimensions, verify the result against the authoritative engineering drawing, controlled CAD model, tolerance specification, or inspection procedure.

---

## 🎯 Point-to-Point Measurement

A point-to-point workflow can be used to examine the spatial relationship between two selected points.

A typical sequence is:

1. 📐 Activate the measurement tool.
2. 🎯 Select the first point on the intended geometry.
3. 🖱️ Move toward the second point to preview the measurement where supported.
4. 🎯 Select the second point.
5. 📊 Review the resulting measurement information.

---

## 📊 Measurement Results

Depending on the active workflow, useful results can include:

| Value | Meaning |
| :--- | :--- |
| **3D Distance** | Direct linear distance between the selected points |
| **Delta X** | Difference along the X direction |
| **Delta Y** | Difference along the Y direction |
| **Delta Z** | Difference along the Z direction |

The Delta values are particularly useful when you want to understand how far two points are separated along individual model axes.

---

## 📦 Bounding-Box Dimensions

A model's bounding box provides an overall geometric envelope.

Typical information can be expressed as:

```text
X Length
Y Width
Z Height
```

Bounding dimensions are useful for quick checks such as:

- 📦 Approximate part size
- 🏭 Manufacturing envelope review
- 🚚 Packaging or handling estimates
- 🧰 Workholding considerations
- 📐 Drawing-reference information

A bounding box does **not** describe every feature of a part. A part with holes, pockets, tapers, or irregular geometry may have the same overall envelope as a very different part.

---

## 🧭 Measurement Best Practices

### 1. Confirm the model orientation

Before interpreting Delta X, Y, and Z, make sure you understand the model coordinate system and current orientation.

### 2. Zoom before selecting

When measuring a small feature, zoom into the area first. This can make point selection more precise.

### 3. Use standard views

Front, Top, Right, and Isometric views can help you understand where a selected point sits in relation to the rest of the model.

### 4. Repeat important measurements

For an important dimension, take the measurement again or inspect it from another view.

### 5. Verify critical dimensions

For production work, compare critical dimensions with the controlled drawing or authoritative engineering data.

---

## 🏭 Manufacturing Examples

### Checking a hole location

Use a suitable reference point and inspect the coordinate differences to understand the hole's approximate position.

### Checking overall stock envelope

Use bounding dimensions to get a quick sense of the part's maximum X/Y/Z extent.

### Reviewing a machined feature

Zoom into the feature, use the appropriate view, and measure between meaningful geometry points.

> 💡 Preliminary viewer measurements are useful for understanding a model, but they should not replace a controlled dimensional inspection process.

---

## 🔗 Related Documentation

- [CAD Viewer Controls](cad-viewer.md)
- [Getting Started](getting-started.md)
- [Technical Drawing & Drafting](drafting.md)
- [STEP Files](step-files.md)
- [IGES Files](iges-files.md)
