---
layout: post
title: Lecture 00 - Intro to Python
description: Types, lists, ranges, project euler
tags: [lecture, python]
---

[Lecture on Youtube](https://www.youtube.com/watch?v=s65sPWNEGds)
For full quality, watch at 1440p.

[Files for this lecture](https://buffalo.box.com/s/2i79ltzptdlp5qdoqc1uejr5tpv832sh)  
Make a 306 directory, as in the lecture. Extract this to your 306 directory.

Here is a correction to my code for computing the "Largest Palindromic Product":

	TDNs = [n for n in range(100, 1000)]
	products = [m*n for m in TDNs for n in TDNs]
	palindromes = [p for p in products if is_palindrome(str(p))]
	max(palindromes)

The code is correct in the file `Intro to Python.ipynb` but incorrect in the video.