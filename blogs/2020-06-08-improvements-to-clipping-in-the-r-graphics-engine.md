---
title: "Improvements to Clipping in the R Graphics Engine"
url: "https://blog.r-project.org/2020/06/08/improvements-to-clipping-in-the-r-graphics-engine/"
date: "Mon, 08 Jun 2020 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
UPDATE (2020-11-18): canClip = NA_LOGICAL has been replaced by deviceClip = TRUE The R graphics engine performs some clipping of output regardless of whether the graphics device it is sending output to can perform clipping itself. For example, output that is sent to the postscript() device, which can do its own clipping, is still clipped by the graphics engine to the edges of the device. This is useful for devices that cannot clip, e.
