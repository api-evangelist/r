---
title: "Why to avoid \\x in regular expressions"
url: "https://blog.r-project.org/2022/06/27/why-to-avoid-%5Cx-in-regular-expressions/"
date: "Mon, 27 Jun 2022 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Using \x in string literals is almost always a bad idea, but using it in regular expressions is particularly dangerous. Consider this “don’t do” example in R 4.2.1 or earlier: text <- "Hello\u00a0R" gsub("\xa0", "", text) a0 is the code point of the Unicode “NO-BREAK SPACE” and the example runs in UTF-8 locale. The intention is to remove the space; a slightly more complicated variant has been discussed on the R-devel mailing list about half a year ago.
