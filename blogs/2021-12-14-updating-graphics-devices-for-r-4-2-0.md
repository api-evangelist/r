---
title: "Updating Graphics Devices for R 4.2.0"
url: "https://blog.r-project.org/2021/12/14/updating-graphics-devices-for-r-4.2.0/"
date: "Tue, 14 Dec 2021 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
A number of new graphics features have been added to the R graphics engine in the development version of R (to become version 4.2.0): groups, compositing operators, affine transformations, stroking and filling paths, and luminance masks. This has consequences for R packages that provide graphics devices, like the ‘ragg’ package. For users of R packages that provide graphics devices, those packages will need to be reinstalled when updating to R 4.
