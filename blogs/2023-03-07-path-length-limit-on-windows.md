---
title: "Path length limit on Windows"
url: "https://blog.r-project.org/2023/03/07/path-length-limit-on-windows/"
date: "Tue, 07 Mar 2023 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
When testing development versions of Rtools for Windows, I’ve ran into strange failures of several CRAN packages where R could not find, read from or write to some files. The files should have been in temporary directories which get automatically deleted, so it took some effort to find out that actually they existed and were accessible. That didn’t make any sense at first, but eventually I got to this output:
