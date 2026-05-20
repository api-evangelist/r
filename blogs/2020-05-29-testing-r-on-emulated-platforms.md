---
title: "Testing R on Emulated Platforms"
url: "https://blog.r-project.org/2020/05/29/testing-r-on-emulated-platforms/"
date: "Fri, 29 May 2020 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Sometimes it is useful to test R on unusual platforms, even when the expected number of users is not large at the moment. It is better to be ready when a new platform arrives or becomes more widely used, it may be easier to find some bugs on one platform than other, and such testing may reveal code unintentionally too platform specific. Recently I wanted to test R on 64-bit ARM (Aarch64) and on Power.
