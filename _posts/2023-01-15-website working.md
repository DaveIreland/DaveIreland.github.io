---
layout: post
title: Getting GiHub Pages working
date: 2023-01-15 17:13:40
---

# Fixing problem with GitHub Actions
Build and deploy seemed to be broken on pushing site to GitHub, even though locally built version looked OK. Solution was found on Stack Overflow. Go to local directory of the (Jekyll) site, and arry out:

```console
%>  bundle lock --add-platform x86_64-linux
```
The problem was that the GitHub Actions will try to build the website on a ubuntu VM, whereas the site had been tested on Windows 11.

