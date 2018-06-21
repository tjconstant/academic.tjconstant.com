+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Electromagnetic Software"

# Project summary to display on homepage.
summary = "Software for Electromagnetic Development"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "software.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["software"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

Over the course of my academic career, I have mostly used the statistical programming language `R` for the analysis of my data and exploration of theory. I have developed several R packages in that time for various useful optics calculations and for data-processing.


## mlfilms

The `mlfilms` package uses the transfer matrix method to calculate the reflection and transmission of plane polarised light from an arbitary stack of thin films.

It is the most complete R package I have created, with documentation and examples.

<a class = "btn btn-primary btn-outline" href="http://mlfilms.tjconstant.com"><i class="fa fa-book"></i> Documentation</a> <a class = "btn btn-primary btn-outline" href="https://github.com/tjconstant/mlfilms"><i class="fa fa-github"></i> Github</a>


## thor2

The `thor2` package provides the optical response of various thorlab components for use in R.

<a class = "btn btn-primary btn-outline"  href="https://github.com/tjconstant/thor2"><i class="fa fa-github"></i> Github</a>

## disp.plot

Package for producting colourplots/heatmap plots of linearly-spaced data with arbitrary non-linear coordinate transformations. 

Developed by necessity to be able to transform wavelength $(\lambda)$ and angle $(\theta)$ data to non-linearly spaced colourplots of frequency $(1/\lambda)$ and momentum $(\propto (1/\lambda) \sin{\theta})$, but also works for any linearly-spaced to nonlinear-spaced data. For example the Cartesian to polar colourplot transformation $f(x,y) \rightarrow f(r, \theta)$.

<a class = "btn btn-primary btn-outline"  href="https://github.com/tjconstant/disp.plot"><i class="fa fa-github"></i> Github</a>

## rindex

`rindex` allows you to browse refractive index data from <http://refractiveindex.info> directly in R, and to directly use the datasets or interpolated refractive index functions for a wide range of materials. 

<a class = "btn btn-primary btn-outline"  href="https://github.com/tjconstant/rindex"><i class="fa fa-github"></i> Github</a>

## fdtd

An example script showing how to implement a simple Finite Difference Time Domain calculation in R.

<a class = "btn btn-primary btn-outline"  href="https://github.com/tjconstant/fdtd"><i class="fa fa-github"></i> Github</a>

## grapheneSPP

An R implementation to calculate Surface Plasmon Polariton dispersion in Graphene, including interactions with substrate phonons. 

<a class = "btn btn-primary btn-outline" href="https://github.com/tjconstant/grapheneSPP"><i class="fa fa-github"></i> Github</a>

## photonMonkey / ultrafastMonkey

Miscellaneous convenience functions for use in optics.

<a class = "btn btn-primary btn-outline" href="https://github.com/tjconstant/photonMonkey"><i class="fa fa-github"></i> Github (photonMonkey)</a>
<a class = "btn btn-primary btn-outline" href="https://github.com/tjconstant/ultrafastMonkey"><i class="fa fa-github"></i> Github (ultrafastMonkey)</a>


