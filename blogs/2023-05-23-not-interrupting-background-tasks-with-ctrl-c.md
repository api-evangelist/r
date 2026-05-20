---
title: "(Not) interrupting background tasks with Ctrl+C"
url: "https://blog.r-project.org/2023/05/23/not-interrupting-background-tasks-with-ctrl-c/"
date: "Tue, 23 May 2023 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
When using R interactively from the command line, one can interrupt the current computionation using Ctrl+C key combination and enter a new command. This works both on Unix terminal and on Windows console in Rterm. Such computation may be implemented in R or C and may be executing an external command while waiting for the result e.g. via system(,wait=TRUE).
