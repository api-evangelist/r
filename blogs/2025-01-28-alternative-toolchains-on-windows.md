---
title: "Alternative toolchains on Windows"
url: "https://blog.r-project.org/2025/01/28/alternative-toolchains-on-windows/"
date: "Tue, 28 Jan 2025 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
R and R packages on Windows, if they include native code, are built using compiler toolchain and libraries from Rtools. There is always a specific version of Rtools for a given version of R. Rtools44 is used for R 4.4.x, and hence R 4.4.x and packages for that version of R are always built with GCC 13.3 for x86_64 systems and with LLVM 17 for aarch64 systems. This is the case at least since Rtools42 (R 4.
