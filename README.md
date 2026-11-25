# Softform — Customization Studio

DESN2002 interactive ergonomic squishy configurator. This version retains the Version 3 blue/orange palette and Roboto typography.

## Use

Open `index.html` in Chrome or Safari. Choose a form, hand dimensions, resistance preferences and color. Click **Create my squishy** to see the order summary.

- **Download design package**: ZIP containing an exterior STL, CSV order sheet and printing notes.
- **3D model (.stl)**: closed, scaled exterior mesh from the Rhino-derived website geometry. Coordinates are in millimetres; import as mm. The lowest point is set to Z=0.
- **Order sheet (.csv)**: open in Excel or Numbers. Includes customer choices, target dimensions, scale factors and all five finger preferences.
- **Print / save as PDF**: opens the browser print dialog for a readable summary.

All files are generated locally. No customer information is submitted, no order is placed, and no backend is needed.

## Manufacturing limitations

The STL is a fit prototype exterior, not the finished graded-lattice squishy. It does not include the 1.2 mm shell or 10 mm BC lattice, and selecting resistance does not change the exterior STL. A slicer's conventional infill is not equivalent to the intended graded lattice. The original Grasshopper/Kangaroo/Crystallon definition must be run separately to create the final design. Transfer the CSV settings, verify radii, shell, union, print process, support/powder removal and mechanical response before customer manufacture. No material or comfort validation is implied.

## GitHub Pages

Upload `index.html` and `README.md` to the root of the existing repository and commit directly to `main`. The existing Pages URL remains unchanged. The 3D model and code are embedded in the HTML; Google Fonts loads online with local fallback fonts.
