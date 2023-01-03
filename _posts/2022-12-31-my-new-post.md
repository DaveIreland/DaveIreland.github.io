---
layout: post
title: My New Post
date: 2022-12-31 16:04 +0000
---

# Compose new files
Added [jekyll-compose](https://github.com/jekyll/jekyll-compose) for creating from templates.

# Test of image gallery...

One image...

![Delta Resonances Year](/images\figures\delta_resonances_year.svg)
_Delta Resonances Year_

Gallery...
{% include image-gallery.html folder="/images/figures" %}


> An example showing the `warning` type prompt. 
{: .prompt-warning }

> An example showing the `danger` type prompt. 
{: .prompt-danger }

> An example showing the `info` type prompt. Had to re-do the original gallery generator to remove the use of the online image processing for photos. Not necessary for plots?
{: .prompt-info }

> An example showing the `tip` type prompt. Name output plots with a leading "01_", "02_", etc.
{: .prompt-tip }


# No plugin solutions
Found at [this site](https://jekyllcodex.org/without-plugins/), since deployment at GitHub Pages may not allow plugins. 