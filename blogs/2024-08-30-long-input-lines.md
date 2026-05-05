---
title: "Long input lines"
url: "https://blog.r-project.org/2024/08/30/long-input-lines/"
date: "Fri, 30 Aug 2024 00:00:00 +0000"
author: ""
feed_url: "https://blog.r-project.org/index.xml"
---
When using R interactively via a console, one edits a line of input, confirms it by pressing ENTER, then R parses the line, evaluates it, prints the output and lets the user enter another line. This is also known as REPL (Read-Eval-Print-Loop).
The maximum length of the input line is sometimes limited. It is essentially impossible that one would run into a limit when typing the commands, but there was a report from a user who pasted generated content to the console and have ran into a limit of 4096 bytes.
