# 🧰 Troubleshooting iLoveIGS

This guide covers common problems when using a browser-based CAD viewer and technical drawing workflow.

🌐 **Current application:** https://www.iloveigs.com/

> 💡 First principle: if a problem appears, determine whether it is related to the **file**, **browser**, **device resources**, or **viewer workflow**. This makes troubleshooting much faster.

---

## 1️⃣ The File Does Not Open

### Possible causes

- Unsupported file type or entity.
- Corrupted or incomplete file.
- File contains unusual CAD entities.
- Browser resource limitations.
- The source CAD system exported unexpected geometry.

### What to try

1. Confirm the extension is supported.
2. Try opening another known-good CAD file.
3. Refresh the application.
4. Try a current version of Chrome, Edge, Firefox, or Safari.
5. If possible, validate the file using the originating CAD system.

If another file opens normally, the issue may be specific to the original file.

---

## 2️⃣ The 3D Viewport Is Blank or Black

### Possible causes

A 3D viewer depends on browser graphics capabilities such as **WebGL**. Hardware acceleration, graphics drivers, browser configuration, or device limitations can affect rendering.

### What to try

- 🔄 Refresh the page.
- 🌐 Try another modern browser.
- ⚙️ Check whether hardware acceleration is available/enabled in the browser.
- 🖥️ Update graphics drivers on a desktop/laptop where applicable.
- 📦 Try a smaller model to determine whether the issue is related to file complexity.

---

## 3️⃣ The Model Loaded but I Cannot See It

The model may simply be outside the current camera view or extremely small/large relative to the viewport.

Try:

1. 🎯 Use **Fit**.
2. 🧭 Switch to an Isometric or standard view.
3. 🔍 Zoom out and then back in.
4. 🎨 Change the display mode.
5. 🔄 Reload the file if necessary.

---

## 4️⃣ STEP or IGES Takes a Long Time to Process

Large CAD files can require substantial processing resources, especially when the geometry contains many faces, complex surfaces, or large assemblies.

Performance can depend on:

- File size
- Model complexity
- Number of bodies
- CPU performance
- Available memory
- Browser implementation
- Device hardware

### What to try

- Close unnecessary browser tabs.
- Use a laptop or desktop for large models.
- Try a simplified export if the source CAD system allows it.
- Wait for processing to complete before repeatedly reloading the page.

> ⚠️ Avoid assuming that file size alone determines complexity. A smaller CAD file can still contain computationally expensive geometry.

---

## 5️⃣ The Model Looks Different from the Original CAD System

CAD exchange is not always lossless across every system and workflow.

Differences can be caused by:

- Tessellation settings
- Unsupported entities
- Surface healing
- Export settings
- Units or coordinate transformations
- Differences in how CAD systems display edges

For critical geometry, compare the file with the originating CAD system or authoritative engineering data.

---

## 6️⃣ Right-Click Does Not Open the Context Menu

In CAD-style interaction, the right mouse button may serve more than one purpose.

If right-button dragging is used for orbiting, a movement can be interpreted as camera control instead of a context-menu action.

Try releasing the right mouse button without dragging when a context menu is expected.

---

## 7️⃣ Measurements Need Verification

A measurement that looks correct should still be verified when it affects manufacturing or inspection decisions.

Check:

- Model orientation
- Selected points
- Units
- Geometry location
- Drawing/specification requirements

For critical work, compare the result with the authoritative engineering source.

---

## 8️⃣ The Viewer Feels Slow

### On desktop/laptop

Try:

- Closing unnecessary tabs and applications.
- Using a modern browser.
- Testing a smaller model.
- Updating graphics drivers where applicable.

### On mobile/tablet

Large 3D models can be more demanding because mobile devices have different CPU, memory, GPU, and thermal constraints.

For detailed CAD inspection, a desktop or laptop may provide a smoother experience.

---

## 9️⃣ Drawing or PDF Output Looks Different

Browser print settings can change the final result.

Before printing:

- Check orientation.
- Check page size.
- Check scale settings.
- Use print preview.
- Confirm that the complete drawing fits the page.

When using **Save as PDF**, review the resulting PDF before sharing it as engineering documentation.

---

## 🔟 Still Having Trouble?

If a problem persists, record as much information as possible:

```text
Device:
Operating system:
Browser:
File format:
Approximate file size:
What happened:
What you expected:
Steps already tried:
```

This information makes technical troubleshooting much easier.

🌐 **Visit iLoveIGS:** https://www.iloveigs.com/

---

## 🧠 Quick Diagnostic Checklist

**File problem?** → Test another file.

**Browser problem?** → Try another current browser.

**Graphics problem?** → Check WebGL/hardware acceleration.

**Performance problem?** → Test a smaller model or stronger device.

**Geometry problem?** → Compare with the source CAD system.

**Dimension problem?** → Verify against the authoritative engineering data.
