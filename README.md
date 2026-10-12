## Fourier Epicycle SVG Path Drawing Machine

Visualizes how Discrete Fourier Transform (DFT) decomposes any closed path into a sum of rotating circles (epicycles). Five built-in shapes (star, heart, wave, letter A, spiral) are sampled into 128 points, DFT is computed in-browser, and the resulting frequency components animate as concentric spinning arms that together trace the original path.

**Tech:** Vanilla JS, SVG animation via requestAnimationFrame, Tailwind CSS. **How to use:** Select a shape, adjust the epicycle count slider (1–60) to see how more circles produce a more accurate trace, and control animation speed. The cyan line is the traced path; the dashed yellow shows the original shape for comparison.
