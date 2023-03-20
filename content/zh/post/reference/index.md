---
title: 理解C++引用
subtitle: C++引用和C的指针有什么联系？

# Summary for listings and search engines
summary: C++引用

# Link this post with a project
projects: []

# Date published
date: '2020-12-13T00:00:00Z'

# Date updated
lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - Tannal

tags:
  - Academic
  - 开源

categories:
  - C++
  - 引用
  - 指针
---

# C++中的 & 引用

下面两个代码是等价的

编译出来的汇编是一样的

```c
void increment(int *x) {
    (*x)++;
}

```

```cpp
void increment(int & x) {
    x++;
}

```


# 如何理解

可以把C++的引用理解为指针的语法糖




