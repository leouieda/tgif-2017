# Inverting gravity to map the Moho: A new method and the open source software that made it possible

by [Leonardo Uieda](http://www.leouieda.com)

TGIF Seminar given at the
[Department of Geology and Geophysics](http://www.soest.hawaii.edu/GG/index.html)
of the University of Hawaii at Manoa
on March 10, 2017.

This repository contains the source code examples used in the demo and the
original figures.

Slides and additional information:
[leouieda.com/talks/tgif-2017.html](http://www.leouieda.com/talks/tgif-2017.html)

The Jupyter notebooks used in the demos are:

* Magnetic data processing: [demo-mag-data.ipynb](http://nbviewer.jupyter.org/github/leouieda/tgif-2017/blob/master/demo-mag-data.ipynb)
  (in this repository)
* The total field magnetic anomaly: [6-igrf-anomalia-campo-total.ipynb](http://nbviewer.ipython.org/github/leouieda/geofisica1/blob/master/notebooks/6-igrf-anomalia-campo-total.ipynb)
* Introduction to seismic waves: [1-ondas-sismicas.ipynb](http://nbviewer.ipython.org/github/leouieda/geofisica2/blob/master/notebooks/1-ondas-sismicas.ipynb)
  (use [this link](http://mybinder.org/repo/leouieda/geofisica2/notebooks/notebooks/1-ondas-sismicas.ipynb)
  to run the code online)


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


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This content is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

The color palette used in the presentation is
[SCREAM! by rubyvillasenor](http://www.colourlovers.com/palette/1529379/SCREAM!).
