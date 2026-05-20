---
title: "Sporadic Rterm Crashes with Completion"
url: "https://blog.r-project.org/2022/11/01/sporadic-rterm-crashes-with-completion/"
date: "Tue, 01 Nov 2022 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
This post is a story of a bug in Rterm, the console R front-end on Windows, which has been bugging me for several years, but only two weeks ago it showed up unwarily so that I could trace it down and fix. The terminal sometimes crashed during completion, so after I pressed the tab key, but it was very rare, there seemed to be no way to reproduce the problem, and it was only happening with the mintty terminal (from Msys2, running bash), never with cmd.
