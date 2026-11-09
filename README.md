# Crew Sales Calculator

A responsive, browser-based calculator for AC, GC, labor percentage, and GCPCH.

## Formulas

- **Total GC** = sum of the GC numbers entered (comma-separated, up to 16 values)
- **Sales** = AC × Total GC
- **Labor** = ((Crew Total HR × 68.75) ÷ Sales) × 100
- **GCPCH** = Total GC ÷ Crew Total HR

The crew rate is fixed at **$68.75**. The calculator runs entirely in the browser; it does not send or store entered values.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html` (and optionally this README) to the repository's root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. After GitHub Pages finishes publishing, use the URL shown in the Pages settings.

No build tools or dependencies are required.
