---
title: "GFortran Issues with LAPACK II"
url: "https://blog.r-project.org/2019/09/25/gfortran-issues-with-lapack-ii/"
date: "Wed, 25 Sep 2019 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
This is an update on my previous post from May. A number of things changed since: GFortran started adopting a fix that by default prevents optimizations which break code calling BLAS/LAPACK functions from C without hidden length arguments. R has been updated to internally add these hidden length arguments (and also in other cases where LTO type mismatch was detected).
