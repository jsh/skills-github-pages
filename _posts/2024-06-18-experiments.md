---
title: Experiments
slug: banana
date: 2024-06-19 11:59:00 -0600
layout: post
author: jsh
category: experimental
food: pizza
---

This post will contain
a variety of ever-changing experiments,
as I read about and explore Jekyll.

# An experimental post


I'll need text, equations, and code in my posts.

Here's an equation bounded by single dollar-signs: $x \geq 0$

Here's an equation bounded by double dollar-signs: $$x \lt 1$$

And here's a math block copied straight from the Kramdown documentation:

$$
\begin{aligned}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{aligned}
$$


Which doesn't work. Bummer.


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

I'll experiment with variables a bit.

Food: {{ page.food }}

Snail: {{ site.snail }}

BaseURL: {{ site.baseurl }}
