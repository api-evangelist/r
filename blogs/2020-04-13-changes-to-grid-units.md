---
title: "Changes to 'grid' units"
url: "https://blog.r-project.org/2020/04/13/changes-to-grid-units/"
date: "Mon, 13 Apr 2020 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
One of the main downsides to the ‘grid’ graphics package is that it is slow. And that makes some important packages that depend on ‘grid’, like ‘ggplot2’, slow. For example, the scatterplots shown below are roughly equivalent, but one is drawn using ‘graphics’ and the other using ‘ggplot2’.
