physics-patch 2.4

Improved version of the physics package

This package is released under the LaTeX Project Public License (LPPL) 1.3c
See https://www.latex-project.org/lppl/lppl-1-3c for the details of that license
Many parts of this package are modified from the physics package, created by Sergio C. de la Barrera and licenced under LPPL 1.3
See https://ctan.org/pkg/physics for the details of that package

This package requires amsmath, etoolbox, xcolor, xparse, and xstring package.
Commands that have different definitions come with PT in the beginning of their name (e.g. \PTmqty).
physics-patch has covered all commands in physics since version 2.0, so there's no need to load physics.
It is ok to load physics before this package. This package will silently overrides macros in physics with an improved version. To use the original version provided by physics, load physics before this package and use the nooverride option (not recommended).
This package pretends that physics package is loaded so that this package won't be overriden if loading physics is called afterward and packages loaded afterward that checks whether physics is loaded to determine its behavior (e.g. siunitx) work correctly. To disable this, use the nopretend option (not recommended).
If siuitx is loaded before this package, this package will define \ITquantity and \ITqty as the integration of the improved definition of physics's \qty (in \PHquantity and \PHqty) and siuitx's \SI. You can optionally set siintegrate option to override \PTquantity and \PTqty with \ITqty (not recommended).

Author: Willie Shen (Willie169)
Repository: https://github.com/Willie169/physics-patch
Last update: Feb 16, 2025

For documentation, see physics-patch.pdf