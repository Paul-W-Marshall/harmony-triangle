Harmony Triangle

Paul Warrington Marshall — Fidelitas LLC

Reference implementation and interactive visualization of the Harmony Triangle — a novel color space design system building on James Clerk Maxwell’s 1874 color triangle. This repository provides both:

A production-ready Next.js 14 + WebGL web app (in /web) with:

Interactive barycentric triangle renderer

sRGB / Display-P3 space toggle with live badge

Draggable probe showing barycentric weights, hex color, and copy-to-JSON

PNG export (color-managed, space-aware)

A /figures TypeScript toolchain for generating publication-quality PNGs and CSV data, with shared color-math utilities and JSON-configured anchors.

Developed in parallel with the upcoming arXiv paper, which documents the theoretical and historical basis of the Harmony Triangle.

Quick Start

Clone and Install:

git clone https://github.com/Paul-W-Marshall/harmony-triangle.git
cd harmony-triangle/web
npm install

Run the Web App:

npm run dev

Visit http://localhost:3000

Generate Figures:

cd ../figures
npm install
npm run build && npm run generate

Deployment

This project is configured for Vercel deployment.

Root Directory: /web

Build Command: npm run build

Output Directory: .next

Provenance and Citations

Public repo for reproducibility and scholarly citation.

Full commit history preserved.

Original private archival repo noted in Appendix/Provenance section of the paper.

Credit to James Clerk Maxwell’s 1874 color triangle (Maxwell, J.C., "On the Theory of Compound Colours," 1860).

License

Code: MIT

Paper: CC BY 4.0

Figures: CC BY-NC 4.0

See LICENSE files in root and subdirectories for details.
