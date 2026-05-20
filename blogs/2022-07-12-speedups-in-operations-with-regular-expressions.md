---
title: "Speedups in operations with regular expressions"
url: "https://blog.r-project.org/2022/07/12/speedups-in-operations-with-regular-expressions/"
date: "Tue, 12 Jul 2022 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Regular expression operations in R, such as grep or gsub, sometimes have significant performance overheads due to encoding conversions. Some R code tries to mitigate this by ignoring input encodings and pretending it is fine to work on individual bytes (via useBytes=TRUE). This removes such overheads, but produces correct results only in special cases, e.g. for simple regular expressions in UTF-8.
