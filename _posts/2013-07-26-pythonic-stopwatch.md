---
title: Pythonic stopwatch
date: 2013-07-26 17:53:33
tags: python, snippets
layout: post
---

Себе на память.

~~~ python
import time

start_time = time.time()
time.sleep(1)
elapsed_time = time.time() - start_time

print(elapsed_time)
~~~
