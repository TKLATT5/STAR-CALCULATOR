# Star Calculator

A single-file web tool for designing and fabricating multi-point, raised-center 3D stars — the "kite-and-brace" construction. Enter the star's dimensions, see it in 2D and 3D, and print 1:1 cut templates you can lay straight onto material.

**Live:** https://tklatt5.github.io/STAR-CALCULATOR/

## What it does

- **2D + 3D preview** — adjust points, outer radius, inner radius, and height; rotate and zoom the 3D model.
- **Exact developed geometry** — each star panel is a single kite folded along its center crease (outline B–Z–D–C), with a matching triangular brace per arm.
- **PDF worksheet** — the flat kite pattern with measured dimensions.
- **1:1 cut templates (PDF)** — true-scale piece outlines packed across Letter pages:
  - Small pieces nest two-or-more per page.
  - Long kites are rotated onto the page **diagonal** (judged by the real kite footprint, not its bounding box) so stars up to ~14" tip-to-tip print 1:1 on Letter without tiling any single piece.
  - Every page carries a print-at-100% warning, a 1-inch ruler check, and corner registration marks.
  - A live fit readout shows how many pages a design needs and recommends the largest printable size.
- **SVG / PNG export** and a local saved-designs gallery.

## Usage

Just open the page. Everything (Three.js, jsPDF) is inlined in `index.html` — no build step, no dependencies, no server.

When printing templates, **set your printer to 100% / Actual Size** (not "Fit to page") and confirm the 1-inch ruler measures true before cutting.

## Files

- `index.html` — the entire app.

## License

Personal project. Use freely.
