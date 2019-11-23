This repository contains gapfilling code used in the Malaria Atlas Project (Oxford University) to fill gaps in MODIS LST, EVI, TCB and TCW imagery.

The code is presently contained within a Jupyter notebook. This contains a Python (2.7) / Cython reimplementation of algorithms originally developed by Dan Weiss and described in the following paper:

Weiss, D.J., Atkinson, P.M., Bhatt, S., Mappin, B., Hay, S.I. & Gething, P.W. (2014) An effective approach for gap-filling continental scale remotely sensed time-series. ISPRS Journal of Photogrammetry and Remote Sensing, 98, 106-118

This implementation was written by Harry Gibson and is presented here as a notebook which contains all necessary code, including boilerplate, to run the algorithms.