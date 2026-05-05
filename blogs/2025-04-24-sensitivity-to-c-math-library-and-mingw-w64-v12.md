---
title: "Sensitivity to C math library and mingw-w64 v12"
url: "https://blog.r-project.org/2025/04/24/sensitivity-to-c-math-library-and-mingw-w64-v12/"
date: "Thu, 24 Apr 2025 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
C math library functions, such as exp or sin, are heavily used by R and packages. The C standard doesn’t require these functions to be “precise”. Instead, there is room for performance optimizations causing a reasonable amount of inaccuracy. The results differ between platforms and may change even on a single platform. This happened with mingw-w64 v12, the SDK/runtime used by GCC and LLVM on Windows, which reduced accuracy of many math functions (for performance and maintenance reasons).
