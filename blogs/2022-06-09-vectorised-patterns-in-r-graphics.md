---
title: "Vectorised Patterns in R Graphics"
url: "https://blog.r-project.org/2022/06/09/vectorised-patterns-in-r-graphics/"
date: "Thu, 09 Jun 2022 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Support for pattern fills was added to the R graphics engine in R version 4.1.0, with an R interface via the ‘grid’ package. library(grid) For example, the following code defines a linear gradient that varies horizontally from red to white and a tiling pattern that is based on a repeating red circle. gradcol <- c(palette()[2], "white") grad <- linearGradient(gradcol, y1=.5, y2=.5) patcol <- 2 pat <- pattern(circleGrob(r=unit(2, "mm"), gp=gpar(col=patcol, fill=patcol)), width=unit(5, "mm"), height=unit(5, "mm"), extend="repeat") The next code calls grid.
