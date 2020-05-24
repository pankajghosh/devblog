+++ 
draft = false
date = 2020-05-24T10:45:57-07:00
title = "This blog setup"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
+++

This blog is maintained in Git here: https://github.com/pankajghosh/devblog

Built using Hugo (https://gohugo.io/), and utilizing a minimal theme (https://github.com/luizdepra/hugo-coder/), this blog is hosted on Netlify(https://www.netlify.com/)

Netlify has pretty neat integration and support for Hugo, and a quick step-by-step process can be found here: https://www.netlify.com/

# Hugo commands 

Creating a new post is as easy as
```
hugo new posts/new-post.md
```

Running Hugo locally as a daemon
```
hugo server -D --baseURL=http://localhost:1313/
```