# 2026 Texas Voter Guide — Denton County Precinct 1052-70G

Static, responsive visual voter guide with candidate comparison infographics in the supplied ballot order. No dependencies or build step.

## Publish to GitHub Pages

1. Create a **public** GitHub repository (for example, `texas-voter-guide-2026`).
2. Upload **all files and the `images` folder** from this package to the repository root (not the ZIP file itself). Commit them to `main`.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**; select `main` and `/(root)`, then Save.
4. Visit `https://YOUR-USERNAME.github.io/texas-voter-guide-2026/` once GitHub finishes publishing.

## Notes

- Text labels use the user-provided ballot list. Infographics are shown as supplied; some candidate names in the images differ from the list. Verify against the official sample ballot.
- The shared uncontested-office infographic is linked from each uncontested race.
- All images are stored locally in `images/`, so no external hosting is needed.
- To replace an image, update the corresponding file in `images/` or its reference in `index.html`.
