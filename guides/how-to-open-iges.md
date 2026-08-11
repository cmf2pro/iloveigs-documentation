# 🔷 How to Open an IGES File Online

Need to inspect an **IGES (`.igs` / `.iges`) file** but do not have a desktop CAD package available?

[iLoveIGS](https://www.iloveigs.com/) provides a browser-based workflow for supported IGES files.

---

## ⚡ Quick Answer

**Open iLoveIGS → load your `.igs` or `.iges` file → fit the model → inspect standard views → measure or draft where required.**

🌐 **Open the viewer:** https://www.iloveigs.com/

---

## 1️⃣ Open iLoveIGS

Use a modern web browser and visit:

**https://www.iloveigs.com/**

The browser-based approach is useful when you need a quick CAD inspection without setting up a full desktop CAD environment.

---

## 2️⃣ Find Your IGES File

Locate the file on your device.

Typical extensions are:

```text
part.igs
part.iges
assembly.igs
component.iges
```

Before opening it, make sure the file is complete and was transferred correctly.

---

## 3️⃣ Load the File

Use the available file-opening controls in the application to select the IGES file.

On supported workflows, you may also have a drag-and-drop option.

> 📱 On mobile and tablet devices, file selection behavior is controlled by the operating system and browser. The exact interaction can differ from desktop file selection.

---

## 4️⃣ Wait for Processing

An IGES file contains CAD geometry rather than a simple picture. The browser may need to process the geometry before it can display it interactively.

Processing time depends on:

- File complexity
- Number of entities
- Surface complexity
- Device hardware
- Browser resources

Large or complicated models may take longer than simple parts.

---

## 5️⃣ Fit the Model

Once the model appears, use the available **Fit** command to frame the complete geometry.

If you cannot immediately see the model, fitting the camera should be one of the first things to try.

---

## 6️⃣ Inspect Standard Views

Review the model using:

- 🧭 Front
- 🧭 Back
- 🧭 Left
- 🧭 Right
- 🧭 Top
- 🧭 Bottom
- 🧊 Isometric

Standard views help you understand the model before taking measurements or creating drawing references.

---

## 7️⃣ Inspect Edges and Surfaces

Where supported, change the display mode to make geometry easier to interpret.

For example, an edge-enhanced display can make:

- Holes
- Pockets
- Steps
- Boundaries
- Slots
- Feature transitions

more visible during inspection.

---

## 8️⃣ Measure the Model

If the measurement workflow is available, you can use it to inspect selected points and obtain information such as:

- 3D distance
- Delta X
- Delta Y
- Delta Z

For critical manufacturing dimensions, verify the result against the authoritative engineering drawing or controlled CAD model.

---

## 9️⃣ Create a Drawing Reference

Where supported, the drafting workflow can help move from a 3D model toward a technical drawing layout with standard views and drawing information.

See [Drafting & Drawing Workspace](../docs/drafting.md).

---

## 📱 Can I Open an IGES File on Mobile?

The browser-based nature of iLoveIGS allows access from modern mobile and tablet browsers where the device and browser support the required application capabilities.

However, large 3D models can be demanding. For detailed inspection, a laptop or desktop can provide:

- Larger viewing area
- More precise input
- More processing resources
- Better support for complex CAD models

---

## 🧰 If the IGES File Does Not Open

Try these steps:

1. Confirm the file extension is `.igs` or `.iges`.
2. Try another known-good IGES file.
3. Refresh the application.
4. Try another modern browser.
5. Check whether the source CAD system can reopen the file.
6. If possible, request a STEP export from the source system.

For more help, see [Troubleshooting](../docs/troubleshooting.md).

---

## 🔗 Related Resources

- [IGES Files](../docs/iges-files.md)
- [IGES vs STEP](iges-vs-step.md)
- [Getting Started](../docs/getting-started.md)
- [CAD Viewer Controls](../docs/cad-viewer.md)
- [iLoveIGS](https://www.iloveigs.com/)
