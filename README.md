# physics-patch

Patches for physics package and integration of physics and siunitx packages

* Author: **Willie Shen (Willie169)**
* Repository: <https://github.com/Willie169/physics-patch>
* Latest version: 2.0
* Last update: Feb 14, 2025

## Introduction

The `physics-patch` package fixes issues in the `physics` package and improves compatibility between `physics` and `siunitx`.

It provides improved versions of `\qty`, `\dv`, and `\pdv` and introduces new macros.

## Usage

This package requires the `xparse`, `etoolbox`, and `amsmath` packages.  
Optionally, load `physics` and/or `siunitx` before this package.

```latex
\usepackage{physics} % Optional
\usepackage{siunitx} % Optional
\usepackage{physics-patch}
```

By default, `physics-patch` overrides `\qty` with an improved version. To disable this, use the `nooverride` option:

```latex
\usepackage<nooverride>{physics-patch}
```

## Communication Channels

* **Bug tracker:** <https://github.com/Willie169/physics-patch/issues>
* **Announcements:** <https://github.com/Willie169/physics-patch/releases>
* **Repository:** <https://github.com/Willie169/physics-patch>

## License and Credit

This package is released under the **LaTeX Project Public License  1.3c**.  
See <https://www.latex-project.org/lppl/lppl-1-3c> for the details of that license.

Some parts of this package are modified from the `physics` package, created by **Sergio C. de la Barrera** and licensed under **LPPL 1.3**.  
See <https://ctan.org/pkg/physics> for details on that package.

## Documentation

* [**physics-patch.tex**](physics-patch.tex)
* [**physics-patch.pdf**](physics-patch.pdf)