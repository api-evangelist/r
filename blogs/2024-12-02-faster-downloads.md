---
title: "Faster downloads"
url: "https://blog.r-project.org/2024/12/02/faster-downloads/"
date: "Mon, 02 Dec 2024 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
Most R users would sometimes install or update R packages and hence are impacted by how long this takes. The parts of package installation that take potentially longest have already been addressed by support for binary packages and parallel installation. A remaining overhead that may be rather surprising, but is easy to reduce, is package download.
The overhead may be noticeable when installing many mostly small packages in parallel, because so far the package download has been sequential even with parallel installation.
