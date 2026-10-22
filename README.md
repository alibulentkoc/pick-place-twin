# Hydraulic pick-and-place digital twin

Browser-based digital twins of a two-cylinder hydraulic pick-and-place arm, built for AGM 4060 Fluid Power Systems at Clemson University.

- **Lab and tractor twin** (`twins/pick-place-twin.html`): the course rig on the Eaton HTS-2 trainer, plus a tractor-mounted version.
- **Amiga watermelon twin** (`twins/pick-place-twin-amiga.html`): the arm on a farm-ng Amiga rover that harvests a watermelon row.

Each twin is a single self-contained HTML file. All libraries (Three.js r147, OrbitControls, lil-gui 0.19.2) are embedded, so the files work offline. Open one in a browser; no install or build step is needed.

## Repository layout

```
index.html                 landing page (GitHub Pages entry point)
twins/                     the two digital twins
help/                      help pages (getting started, guides, reference, troubleshooting)
assets/help.css            shared style for the help pages
.nojekyll                  tells GitHub Pages to serve files as they are
```

## Publish with GitHub Pages

1. Push this folder to a GitHub repository (steps below).
2. On GitHub, open **Settings, Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://<user>.github.io/<repository>/`.

## Push to GitHub

Create an empty repository on GitHub first (no README, no license), then run:

```
cd pick-place-twin
git init
git add .
git commit -m "Pick-and-place digital twins and help pages"
git branch -M main
git remote add origin https://github.com/<user>/<repository>.git
git push -u origin main
```

The two twin files are about 0.8 to 0.9 MB each, well under GitHub's file size limits.

## Updating a twin

Replace the file in `twins/`, keep the same name, then:

```
git add twins/
git commit -m "Update Amiga twin"
git push
```

## Credits

Three.js and OrbitControls (MIT License), lil-gui (MIT License).
