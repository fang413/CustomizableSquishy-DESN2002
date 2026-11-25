# Softform — Personalization Studio

An interactive product configurator for the DESN2002 squishy design project. The website presents ergonomic grip geometry extracted from the group's Rhino model and demonstrates personalized sizing, appearance and resistance preferences.

## Features

- Interactive 3D preview with rotation and zoom
- Three selectable product forms
- Hand length and palm width adjustment
- Overall and individual finger resistance controls
- Exterior and conceptual lattice views
- Color customization and configuration export

## Run locally

Open `index.html` in a modern browser such as Chrome or Safari. No installation, server, Rhino or Grasshopper is required. The model and application code are embedded in the HTML. Google Fonts supplies Roboto and Roboto Condensed when an internet connection is available; fallback fonts are used otherwise.

## Publish with GitHub Pages

1. Upload `index.html` and `README.md` to the root of the GitHub repository.
2. Commit the files to the `main` branch.
3. In **Settings → Pages**, choose **Deploy from a branch**, then `main` and `/ (root)`.
4. Save and open the published website after deployment succeeds.

## Design prototype

The exterior preview uses geometry extracted from the Rhino model. The sizing rules, resistance settings and lattice preview are illustrative design concepts rather than validated mechanical predictions or manufacturing-ready output. The website does not execute Grasshopper or Karamba3D.

## Visual identity

- Primary interaction color: `#70c3d6`
- Main action and heading accent: `#e88232`
- Neutral palette: black, white and gray
- Headings: Roboto Condensed
- Interface text and sliders: Roboto
