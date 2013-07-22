---
title: Temperature from Crickets
template: index.jade
---

The chirps from crickets speed up with warmer weather and slow down when it is colder.  From this variation, one can get a fairly good estimation of the temperature outside by listening to these insects.


Easy
====

The simplest method of getting a ballpark temperature from counting cricket chirps is count the number of chirps in 15 seconds (<math title="c_15" xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>c</mi><mn>15</mn></msub></math>) and add 37.  You will then find the approximate temperature in Fahrenheit degrees.  For Celsius, count the chirps in 25 seconds (<math title="c_25" xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>c</mi><mn>25</mn></msub></math>), add 8, then divide by 3.

<math title="°F = c_15 + 37" display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mo>&#176;</mo><mi>F</mi><mo>=</mo><msub><mi>c</mi><mn>15</mn></msub><mo>+</mo><mn>37</mn></math>

<math title="°C = (c_25 + 8) / 3" display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mo>&#176;</mo><mi>C</mi><mo>=</mo><mfrac><mrow><msub><mi>c</mi><mn>25</mn></msub><mo>+</mo><mn>8</mn></mrow><mn>3</mn></mfrac></math>


More Accurate
=============

A. E. Dolbear did more studies to refine the formula and the Bessey brothers did even more refinements.  The updated, and more complex method of determining a slightly more accurate number is to use the formula below.  <math title="c_60" xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>c</mi><mn>60</mn></msub></math> stands for the number of chirps in 60 seconds.

<math title="°F = 60 + (c_60 - 92) / 4.7" display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mo>&#176;</mo><mi>F</mi><mo>=</mo><mn>60</mn><mo>+</mo><mfrac><mrow><msub><mi>c</mi><mn>60</mn></msub><mo>-</mo><mn>92</mn></mrow><mn>4.7</mn></mfrac></math>

<math title="°C = 140 / 9 + (c_60 - 92) / 8.46" display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mo>&#176;</mo><mi>C</mi><mo>=</mo><mfrac><mn>140</mn><mn>9</mn></mfrac><mo>+</mo><mfrac><mrow><msub><mi>c</mi><mn>60</mn></msub><mo>-</mo><mn>92</mn></mrow><mn>8.46</mn></mfrac></math>


Sources
=======

* [A. E. Dolbear](../sources/dolbear-a-e.html) - Crickets
* [C. A. Bessey and E. A. Bessey](../sources/bessey-c-a-and-e-a.html)
