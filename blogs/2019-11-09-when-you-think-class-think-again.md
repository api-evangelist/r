---
title: "When you think `class(.) == *`, think again!"
url: "https://blog.r-project.org/2019/11/09/when-you-think-class.-think-again/"
date: "Sat, 09 Nov 2019 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
short lines !! -- Historical relict: R matrix is not an array In a recent discussion on the R-devel mailing list, in a thread started on July 8, head.matrix can return 1000s of columns – limit to n or add new argument? Michael Chirico and then Gabe Becker where proposing to generalize the head() and tail() utility functions, and Gabe noted that current (pre R-4.x.y) head() would not treat array specially.
