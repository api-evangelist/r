---
title: "UTF-8 Support on Windows"
url: "https://blog.r-project.org/2020/05/02/utf-8-support-on-windows/"
date: "Sat, 02 May 2020 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
R internally allows strings to be represented in the current native encoding, in UTF-8 and in Latin 1. When interacting with the operating system or external libraries, all these representations have to be converted to native encoding. On Linux and macOS today this is not a problem, because the native encoding is UTF-8, so all Unicode characters are supported.
