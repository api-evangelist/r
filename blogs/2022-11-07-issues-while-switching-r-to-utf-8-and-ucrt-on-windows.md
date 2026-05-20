---
title: "Issues While Switching R to UTF-8 and UCRT on Windows"
url: "https://blog.r-project.org/2022/11/07/issues-while-switching-r-to-utf-8-and-ucrt-on-windows/"
date: "Mon, 07 Nov 2022 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
From version 4.2.0 released in April 2022, R on Windows uses UTF-8 as the native encoding via UCRT as the new C Windows runtime. The transition for R and its packages has been a non-trivial effort which took several years. This post gives a summary some technical obstacles found on the way, focusing on aspects that may be interesting to other projects.
