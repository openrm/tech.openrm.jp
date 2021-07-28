---
title: "Getting Started"
date: 2021-07-28T09:47:45+09:00
draft: false
tags:
- blog
- how-to
---

This post describes how to set up local environment for editing blog posts.

# Clone the repository
```bash
$ git clone --recursive git@github.com:openrm/tech.openrm.jp.git
```

# Install Hugo
You can follow the instructions here: https://gohugo.io/getting-started/installing/

# Create a post
```bash
$ hugo new posts/some-slug-for-the-post.md
```

# Start the server
```bash
$ hugo server -D
```
