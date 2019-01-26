---
layout: post
cover: 'assets/images/cover7.jpg'
navigation: True
title: Data Analysis Starters
date: 2019-01-26
tags: codes
subclass: 'post tag-test tag-content'
logo: 'assets/images/ghost.png'
author: Lena
categories: codes
---

Print column titles, first few values, and null value counts

```python
def describeData(a):
 
    print('\n Column Values: \n\n', a.columns.values, "\n")
    print('\n First Few Values: \n\n', a.head(), "\n")
    print('\n Null Value Counts: \n\n', a.isnull().sum(), "\n")
```