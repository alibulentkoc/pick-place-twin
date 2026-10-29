# Hydraulic pick-and-place digital twin

A browser-based digital twin of a two-cylinder hydraulic pick-and-place arm, for AGM 4060 Mechanical and Hydraulic Systems at Clemson University.

- **Lab and tractor twin** (`twins/pick-place-twin.html`): the course rig on the Eaton HTS-2 trainer, and the design project: a harvesting arm on a tractor.

The twin is one self-contained HTML file. All libraries (Three.js r147, OrbitControls, lil-gui 0.19.2) are in the file, so it operates offline. Open it in a browser. No installation is necessary.

## Repository layout

```
index.html                 landing page (GitHub Pages entry point)
twins/                     the digital twin
help/                      help pages (getting started, guide, reference, troubleshooting)
assets/help.css            shared style for the help pages
.nojekyll                  tells GitHub Pages to serve the files as they are
```

## Update the twin

Replace the file in `twins/` with the same name, then:

```
git add .
git commit -m "Update the twin"
git push
```

## Copyright

Copyright 2026 Clemson University. All rights reserved. The embedded libraries keep their own licenses: Three.js and OrbitControls (MIT License), lil-gui (MIT License).
