# 📐 Technical Drawing & Drafting Workspace

A 3D model is often only the starting point for engineering communication. Technical drawings turn geometry into a more familiar 2D representation using standard views, dimensions, notes, borders, and title-block information.

The iLoveIGS drafting workflow is designed to help users move from supported 3D model inspection toward a technical drawing layout.

🌐 **Open iLoveIGS:** https://www.iloveigs.com/

---

## 📝 Entering the Drafting Workspace

Where available, use the **Show Draft** or equivalent drafting command in the application.

The exact interface can change as the product develops, but the general workflow is:

**Load model → inspect geometry → choose drawing views → arrange/review drawing → print or export where supported**

---

## 🧭 Standard Drawing Views

A typical mechanical drawing may use:

- **Front View** — primary representation of the part
- **Top View** — shows the part from above
- **Right View** — provides another orthographic projection
- **Isometric View** — gives a 3D-style visual reference

The best view arrangement depends on the shape and the information that needs to be communicated.

---

## 📄 Drawing Sheet Layout

The drafting workspace can organize views on a drawing-sheet style layout.

Depending on the current application capabilities, the layout may include:

- 📏 Drawing borders
- 🧭 View placement
- 📐 Overall dimensions
- 🏷️ Title-block information
- 🖨️ Print-oriented formatting

A drawing sheet should be reviewed carefully before it is treated as manufacturing documentation.

---

## 🏷️ Title Block

A title block helps identify the drawing and its context.

Useful information can include:

- Drawing name
- Part number
- Material
- Scale
- Revision information
- Company/project information

Editable fields and available metadata depend on the current iLoveIGS implementation.

---

## 📏 Dimensions

Automatically generated overall dimensions can help communicate the model envelope.

For example:

```text
Overall X
Overall Y
Overall Z
```

However, overall dimensions are not a substitute for complete manufacturing dimensioning. Holes, slots, radii, chamfers, threads, datums, tolerances, surface requirements, and other design requirements may require separate authoritative information.

---

## 🔍 Review Before Printing

Before exporting or printing a drawing, check:

- Correct model orientation
- Correct drawing views
- View visibility
- Dimension readability
- Title-block information
- Drawing scale
- Units
- Part identification
- Critical design requirements

For production use, compare the generated drawing against the controlled engineering definition.

---

## 🖨️ Printing and PDF Output

Where the current application provides a print workflow, the browser print dialog can be used to produce a physical print or save the output as a PDF.

A typical workflow is:

1. 📝 Prepare the drawing.
2. 🔍 Review the views and dimensions.
3. 🖨️ Select **Print**.
4. ⚙️ Check page orientation and scale in the browser print dialog.
5. 📄 Choose a physical printer or **Save as PDF** when available.
6. ✅ Review the resulting document before distribution.

> 💡 Browser print settings can affect the final output. Always preview the page before issuing a drawing for formal use.

---

## 📱 Using Drafting on Smaller Screens

The application is browser-based and can be accessed from mobile and tablet devices, but detailed drawing work is generally easier on a larger laptop or desktop display because technical drawings contain dense visual information.

---

## ⚠️ Engineering Review Notice

Automatically generated drawing views and dimensions should be reviewed by a qualified person before being used as manufacturing documentation.

Critical dimensions, tolerances, materials, surface requirements, and other controlled requirements should always be verified against the authoritative engineering source.

---

## 🔗 Related Documentation

- [Getting Started](getting-started.md)
- [CAD Viewer Controls](cad-viewer.md)
- [Measurement Tools](measurement-tools.md)
- [STEP Files](step-files.md)
- [IGES Files](iges-files.md)
