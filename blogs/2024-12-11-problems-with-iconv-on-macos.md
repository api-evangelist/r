---
title: "Problems with iconv on macOS"
url: "https://blog.r-project.org/2024/12/11/problems-with-iconv-on-macos/"
date: "Wed, 11 Dec 2024 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
For conversion of strings from a given character encoding to another, R uses iconv, a function defined by POSIX. It is available on Linux and macOS with the operating system and for Windows, R ships with a slightly customized version of win_iconv, which implements the same functionality on top of Windows API.
The differences between iconv implementations, partially allowed by a rather permissive definition of the interface in POSIX, pose a challenge for maintaining R and cause differences between platforms observed by users.
