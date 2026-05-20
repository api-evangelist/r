---
title: "Improvements in handling bytes encoding"
url: "https://blog.r-project.org/2022/10/10/improvements-in-handling-bytes-encoding/"
date: "Mon, 10 Oct 2022 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
In R, a string can be declared to be in bytes encoding. According to ?Encoding, it must be a non-ASCII string which should be manipulated as bytes and never converted to a character encoding (e.g. Latin 1, UTF-8).
