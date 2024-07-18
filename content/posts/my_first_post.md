---
title: My first post
description:
date: 2024-07-04
#tldr: (optional)
draft: true
#tags: [tag names] (optional)
params:
  math: true
---

Hello world, welcome to my first post

$$ \begin{aligned}
KL(\hat{y} || y) &= \sum_{c=1}^{M}\hat{y}_c \log{\frac{\hat{y}_c}{y_c}} \\
JS(\hat{y} || y) &= \frac{1}{2}(KL(y||\frac{y+\hat{y}}{2}) + KL(\hat{y}||\frac{y+\hat{y}}{2}))
\end{aligned}$$