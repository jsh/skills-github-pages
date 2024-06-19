---
title: Experiments
date: 2024-06-19 10:54:00 -0600
layout: post
author: jsh
---
# An experimental post

I'll need text, equations, and code in my posts.

Here's an equation bounded by single dollar-signs: $x \geq 0$

Here's an equation bounded by double dollar-signs: $$x \lt 1$$

Here's code:
```bash
#!/bin/bash

usage=$(basename $0)
die() { echo "$*" >&2; exit 1 ; }

if [ $# -gt 0 ]; then
  die $usage
fi
exit 0
```
