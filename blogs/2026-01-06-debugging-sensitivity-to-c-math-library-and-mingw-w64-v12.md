---
title: "Debugging Sensitivity to C math library and mingw-w64 v12"
url: "https://blog.r-project.org/2026/01/06/debugging-sensitivity-to-c-math-library-and-mingw-w64-v12/"
date: "Tue, 06 Jan 2026 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
C math library functions, such as exp or sin, are not guaranteed to be “precise”. The results might be slightly different on different platforms. A recent change in mingw-w64 v12, which is a core dependency of compilers we use on Windows (both GCC and LLVM), resulted in failures in about 20 CRAN packages. Rtools45 uses mingw-w64 v11, the same version as Rtools44, to allow time for resolving the issues. The change in mingw-w64 v12 switched about 90 math functions from internal implementations to UCRT, the Windows C runtime provided by Microsoft and shipped with the OS.
