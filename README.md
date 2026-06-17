# Matplotlib Book

A comprehensive guide to **Matplotlib**, covering everything from basic plotting to advanced visualization techniques, publication-quality figures, performance optimization, animations, and interactive applications.

This book is written for:

* Students learning scientific visualization
* Researchers preparing publication-quality figures
* Data analysts and scientists
* Python programmers who want to master Matplotlib

## Topics Covered

### Fundamentals

* Introduction to Matplotlib
* Figure and Axes architecture
* Object-Oriented API
* Basic plotting functions
* Labels, titles, legends, and annotations

### Advanced Plotting

* Subplots and GridSpec
* Shared axes and colorbars
* Contour and filled contour plots
* pcolormesh and imshow
* Histograms and statistical plots
* Polar projections

### Styling and Publication Graphics

* rcParams customization
* Custom style sheets
* Typography and LaTeX integration
* Journal-quality figure preparation
* Colorblind-friendly visualizations

### Scientific Visualization

* Heatmaps
* Spectral data visualization
* Radio astronomy examples
* Cosmology and astrophysics applications

### Interactive Features

* Widgets
* Buttons
* Sliders
* Event handling

### Animation

* FuncAnimation
* ArtistAnimation
* Saving animations

### Performance Optimization

* Efficient rendering
* Large dataset visualization
* Memory considerations
* Backend selection

### Reference Material

* Matplotlib Cheat Sheet
* Common Errors and Fixes
* Useful Colormaps
* Object-Oriented API Reference

## Custom mplstyle Files

All figures throughout this book are generated using custom **Matplotlib style sheets (`.mplstyle`)** developed specifically for this project.

The style files provide:

* Consistent typography
* Publication-quality layouts
* Improved spacing and readability
* LaTeX-compatible rendering
* Standardized figure aesthetics

Example usage:

```python
import matplotlib.pyplot as plt

plt.style.use("publication.mplstyle")
```

The corresponding `.mplstyle` files are included in this repository and can be reused in your own projects.

## Requirements

* Python 3.10+
* NumPy
* Matplotlib
* SciPy (selected chapters)

Optional:

* LaTeX installation (for `text.usetex=True`)
* Jupyter Notebook

## Building the Book

The manuscript is written in LaTeX.

Compile using:

```bash
pdflatex book.tex
bibtex book
pdflatex book.tex
pdflatex book.tex
```

or

```bash
latexmk -pdf book.tex
```

## Repository Structure

```text
matplotlib_book/
│
├── chapters/
├── figures/
├── styles/
│   ├── publication.mplstyle
│   ├── presentation.mplstyle
│   └── dark_theme.mplstyle
│
├── code_examples/
├── bibliography.bib
├── book.tex
└── README.md
```

## License

This project is released under the MIT License unless otherwise stated.

## Author

John

A practical and research-oriented guide to Matplotlib, focusing on real-world scientific visualization and publication-quality figure creation.
