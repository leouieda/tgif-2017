# Inverting gravity to map the Moho: A new method and the open source software that made it possible

by [Leonardo Uieda](http://www.leouieda.com)

TGIF Seminar given at the
[Department of Geology and Geophysics](http://www.soest.hawaii.edu/GG/index.html)
of the University of Hawaii at Manoa
on March 10, 2017.

This repository contains the LibreOffice document for the slides and the
original figures.

To see the slides and additional information go to: **link to website**

## Abstract

![](figures/flyer-image.png)

The inner density distribution of the Earth can be inferred from disturbances
in its gravitational field. However, accomplishing this is never easy. There
are many possible parameterizations for the mathematical model, which is often
non-linear. To make matters worse, gravity data alone do not contain enough
information to obtain a unique and stable solution. One must add independent
information to constrain the solution space, often in the form of
regularization. Many different methods for performing this inference have been
developed and research in this field is still active. Investigating new
methodologies implies developing complex software, which often must be able to
deal with sparse matrices and parallelism. I’ll present the open-source Python
library [Fatiando a Terra](http://www.fatiando.org). It implements many of the
components required for developing inversion methods, such as forward modeling,
data processing and I/O, and regularization. I’ll also show how I used this
library to develop a computationally efficient [method for estimating the Moho
depth from gravity data using a spherical approximation of the
Earth](http://www.leouieda.com/papers/paper-moho-inversion-tesseroids-2016.html).
