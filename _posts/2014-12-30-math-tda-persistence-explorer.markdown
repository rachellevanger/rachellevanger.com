---
layout: post
title:  "TDA Persistence Explorer"
date:   2014-12-30 11:30:02 -0500
categories: math
---

Ever wonder how the points in your persistence diagram correspond to the features in the digital images you're processing? Download the [tda-persistence-explorer](https://github.com/rachellevanger/tda-persistence-explorer) app from GitHub and explore your data! Based on the persistence computations from [PHAT](https://github.com/blazs/phat) that utilize discrete Morse theory, this software enables you to encircle persistence points of interest and will then display the corresponding critical cell pairings overlaid on your image, as the screen shot below shows. It also includes a reverse search feature: select a region of interest on the image and the tool will highlight any persistence points with critical cells from their underlying pairings that fall inside.

<center>
<img src="../images/tda-d3-explorer.png" />
</center>

The tool is also great for studying time series of persistence diagrams generated from digital images. The software includes an installation script that will locally install a copy of PHAT and other required dependencies. It also includes [a Jupyter notebook that will get you started on some test data](https://github.com/rachellevanger/tda-d3-explorer/blob/master/doc/Tutorial.ipynb). The test images are numerical simulations of Rayleigh-Benard convection flow and were generously provided by the [Paul Research Group](http://www.me.vt.edu/mpaul/) at Virginia Tech.



