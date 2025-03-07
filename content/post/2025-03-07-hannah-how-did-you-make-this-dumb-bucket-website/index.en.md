---
title: Hannah, how did you make this dumb bucket website?
author: Weller, Hannah
date: '2025-03-07'
slug: hannah-how-did-you-make-this-dumb-bucket-website
categories: []
tags:
  - bucket
---

I'll tell you how!

To create this site from R, just run the following:

```
install.packages("blogdown")
blogdown::new_site(theme = "HugoBlox/theme-academic-cv")
```

To build the site locally and view live updates while you make changes:

```
blogdown::build_site()
blogdown::serve_site()
```

You can also follow these directions to build/serve the site directly through GitHub pages: https://docs.hugoblox.com/getting-started/.