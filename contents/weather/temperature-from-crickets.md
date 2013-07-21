---
title: Temperature from Crickets
template: index.jade
mathjax: true
---

The chirps from crickets speed up with warmer weather and slow down when it is colder.  From this variation, one can get a fairly good estimation of the temperature outside by listening to these insects.


Easy
====

The simplest method of getting a ballpark temperature from counting cricket chirps is count the number of chirps in 15 seconds (@@c_15@@) and add 37.  You will then find the approximate temperature in Fahrenheit degrees.  For Celsius, count the chirps in 25 seconds (@@c_25@@), add 8, then divide by 3.

@@ °F = c_15 + 37 @@

@@ °C = (c_25 + 8) / 3 @@


More Accurate
=============

A. E. Dolbear did more studies to refine the formula and the Bessey brothers did even more refinements.  The updated, and more complex method of determining a slightly more accurate number is to use the formula below.  @@c_60@@ stands for the number of chirps in 60 seconds.

@@ °F = 60 + (c_60 - 92) / 4.7 @@

@@ °C = (140 / 9) + (c_60 - 92) / 8.46 @@


Sources
=======

* [A. E. Dolbear](../sources/dolbear-a-e.html) - Crickets
* [C. A. Bessey and E. A. Bessey](../sources/bessey-c-a-and-e-a.html)
