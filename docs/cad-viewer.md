# 🧊 CAD Viewer Controls

The iLoveIGS viewer is designed around practical CAD inspection: orient the model, fit it to the viewport, inspect surfaces and edges, and move between standard engineering views.

🌐 **Live viewer:** https://www.iloveigs.com/

> ⚠️ Controls can vary by device and application mode. The table below describes the documented desktop interaction model.

---

## 🖱️ Desktop Mouse Controls

| Action | Mouse input | What it does |
| :--- | :--- | :--- |
| **Select** | Left click | Selects available geometry or activates an interactive target. |
| **Window Select** | Left-button drag, left → right | Selects geometry fully contained within the selection window where supported. |
| **Crossing Select** | Left-button drag, right → left | Selects geometry crossed by the selection window where supported. |
| **Pan** | Middle-button drag | Moves the camera across the model. |
| **Orbit / Rotate** | Right-button drag | Rotates the model around the viewing target. |
| **Context Menu** | Right click / release | Opens available contextual commands where supported. |
| **Zoom** | Scroll wheel | Moves the camera closer to or farther from the model. |
| **Fit** | Fit command / double click where supported | Frames the model or selected geometry in the viewport. |

---

## 🎨 Display Modes

Different display modes are useful for different inspection tasks.

### 🧊 Shaded

Displays the model using surface shading. This is useful when you want to understand overall form and surface continuity.

### 🧊➕〰️ Shaded + Edges

Combines shaded surfaces with visible model edges. This can make pockets, steps, holes, boundaries, and other geometric features easier to interpret.

### 🕸️ Wireframe

Displays the model using line-based geometry where supported. Wireframe can be useful when you need to see through the model or inspect the underlying representation.

---

## 🧭 Standard Views

Standard views provide a consistent way to inspect engineering geometry.

Typical views include:

- **Front**
- **Back**
- **Left**
- **Right**
- **Top**
- **Bottom**
- **Isometric**

### Why standard views matter

When reviewing a model with another engineer, machinist, supplier, or customer, using a known orientation reduces ambiguity. Instead of saying “look from this side,” you can refer to a standard view.

---

## 🎯 Fit the Model

After loading a file, fitting the model should usually be the first step.

A fit operation helps ensure that:

- The entire part is visible.
- The camera is positioned appropriately.
- Small or very large geometry is easier to inspect.

If a model appears to be missing, try **Fit** before assuming that the file failed to load.

---

## 🔎 Practical Inspection Sequence

For a typical mechanical part:

**Fit → Isometric → Front → Top → Right → Orbit → Measure**

For a complex assembly:

**Fit → Isometric → standard views → zoom into critical areas → inspect geometry → measure selected features**

---

## 📱 Touch Devices

On mobile phones and tablets, interaction can differ from a desktop mouse workflow because the browser receives touch gestures rather than separate mouse buttons.

For detailed 3D work, a desktop or laptop may provide a more precise inspection experience, while mobile and tablet devices can be useful for quick review and reference.

---

## 🧠 CAD Inspection Tips

- Keep a consistent model orientation when comparing features.
- Use standard views before drawing conclusions about geometry.
- Fit the model after changing to a new file.
- Zoom into the feature before measuring it.
- Use edge display when feature boundaries are difficult to see.
- Verify critical manufacturing dimensions against authoritative engineering data.

---

## Related Documentation

- [Getting Started](getting-started.md)
- [Measurement Tools](measurement-tools.md)
- [Technical Drawing & Drafting](drafting.md)
- [Troubleshooting](troubleshooting.md)
