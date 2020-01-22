Steps to reproduce:

1. When cloning this repository use the `--recursive` option, or if you've already cloned it without that option, run `git submodule update --init`.  This will clone the [Ergo](https://github.com/insipx/Ergo) theme under `themes` folder.
2. Run `zola serve` from the root of this project.

A script tag has been placed in `templates/base.html`.  The `base.html` from the parent theme is not being extended.
