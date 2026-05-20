---
title: "stringsAsFactors"
url: "https://blog.r-project.org/2020/02/16/stringsasfactors/"
date: "Sun, 16 Feb 2020 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Since its inception, R has, at least by default, converted (character) strings to factors when creating data frames directly with data.frame() or as the result of using read.table() variants to read in tabular data. Quite likely, this will soon change. In R 0.62 (released 1998), the original internal data frame code was replaced by the interpreted Statlib code contributed by John Chambers, to the effect that data.frame() would always convert strings to factors (unless protected by I()), whereas read.
