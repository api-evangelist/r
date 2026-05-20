---
title: "New Features in the R Graphics Engine"
url: "https://blog.r-project.org/2020/07/15/new-features-in-the-r-graphics-engine/"
date: "Wed, 15 Jul 2020 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Support for gradient fills, pattern fills, clipping paths and masks has been added to the R graphics engine (in the development version of R, which will probably become R version 4.1.0). An R-level interface for these new features has been added to the ‘grid’ graphics package. library(grid) For example, the following code fills a circle with a linear gradient. grid.circle(gp=gpar(col=NA, fill=linearGradient())) The next code fills a rectangle with a radial gradient.
