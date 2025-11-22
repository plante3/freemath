# freemath

freemath: LaTeX math without backslashes.

Any string of at least two consecutive letters appearing in math mode will automatically be turned into the control sequence with the same name, if it exists.

This package provides the `\freemathon` and `\freemathoff` commands which activates and deactivates this behaviour respectively. It is enabled by default upon loading.

**Example**:

With freemath: `lim_{n to infty} int_Omega n log left( 1 + frac{f}{n} right) d mu`.

Without freemath: `\lim_{n \to \infty} \int_\Omega n \log\left( 1 + \frac{f}{n} ) d\mu`.

---

This package may be used in LaTeX by `\usepackage{freemath}`.

See the documentation for known limitations.

Copyright (C) 2025 plante
Version 1.0

This package is released under the LaTeX Project Public License (LPPL) 1.3c.
