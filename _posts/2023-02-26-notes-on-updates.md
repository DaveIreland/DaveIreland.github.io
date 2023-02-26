---
layout: post
title: Notes on Updates
date: 2023-02-26 14:12:41
---
# Notes on Updates to Jupyter Book on GH Pages

* Want to develop a jupyter book that contains development material as well as extras for presentations, etc.
* Start by renaming the repository on GitHub. Not that easy! Since the book is being built by GitHub Actions, several strings need to be altered to get the build to work. Eventually fixed
* Jupyter Book issue related to MathJax: to get some dollar signs as well as align, equation etc environments to work, nedd to include the following in _config.yml:
```yaml
parse:
  myst_enable_extensions:
    # don't forget to list any other extensions you want enabled,
    # including those that are enabled by default!
    - amsmath
    - dollarmath
    
```
* Added new notebook. Added Binder button, but note that the repository on GitHub needs to be up to date to launch the notebook properly. 