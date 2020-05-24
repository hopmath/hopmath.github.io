---
layout: post
title: Lecture 00 - Intro to Python
description: Types, lists, ranges, projec euler
tags: [lecture, python]
---

[Lecture on Youtube](https://www.youtube.com/watch?v=s65sPWNEGds)
For full quality, watch at 1440p.

[Intro to Python.ipynb](https://buffalo.box.com/s/d6g603hll37zv8hi67synsy4cfkp2uou)
Save this into your 306 directory, as in the video lecture.

Here is a correction to my code for computing the "Largest Palindromic Product":

	TDNs = [n for n in range(100, 1000)]
	products = [m*n for m in TDNs for n in TDNs]
	palindromes = [p for p in products if is_palindrome(str(p))]
	max(palindromes)

The code is correct in the file `Intro to Python.ipynb` but incorrect in the video.