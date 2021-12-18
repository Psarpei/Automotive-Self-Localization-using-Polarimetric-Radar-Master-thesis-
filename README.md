# Automotive Self Localization using Polarimetric Radar (Master thesis)

## General Information
<img align="right" width="300" height="" src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Logo-Goethe-University-Frankfurt-am-Main.svg">

**Supervisors:**
* [Prof. Dr. Visvanathan Ramesh](http://www.ccc.cs.uni-frankfurt.de/people/), email: V.Ramesh@em.uni-frankfurt.de
* [Dr. Michael Rammensee](http://www.ccc.cs.uni-frankfurt.de/michaelrammensee/), email: M.Rammensee@em.uni-frankfurt.de
* [Fabio Weishaupt](https://www.researchgate.net/scientific-contributions/Fabio-Weishaupt-2146626590) email: Fabio.Weishaupt@daimler.com

**Institutions:**
  * **[Goethe University](http://www.informatik.uni-frankfurt.de/index.php/en/)**
  * **[AISEL - AI Systems Engineering Lab](http://www.ccc.cs.uni-frankfurt.de/)**
  * **[Daimler AG](https://www.daimler.com/en/)**

## Work
<img align="left" width="300" height="" src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Loc_exp_0724.png">

**Abstract**
The field of autonomous driving has made great progress in recent years,
including the development of algorithms for self-localization. However,
localization in areas without satellite reception is still an open research topic.
With the help of conventional radar sensors and probabilistic model-based
methods such as particle or Kalman filters, initial successes have already
been achieved. This thesis deals with the development of a probabilistic
model-based self-localization algorithm in the form of a particle filter. Here,
in contrast to previous approaches, polarimetric radar sensors are used
to investigate the advantages of polarimetry as an additional source of
information. In the beginning, there is a general introduction to the operation
of the used radar sensors and the necessary steps in signal processing. In the
further course, the polarimetry and the developed methods for the detection
of objects in the environment with the usage of polarimetry are explained in
more detail. In addition, an algorithm for estimating the vehicles ego-motion
is presented. The ego-motion estimation algorithm forms the first major
component of the proposed approach and is used to estimate the vehicle’s
location based on its motion. To correct the error of the estimated proper
motion, a second method is developed based on the detected objects by the
polarimetric radars, which match the measured positions with objects in a
self-generated map of landmarks. In the end, it is shown that polarimetry
adds value and a comparison of the results with other methods shows that
the developed approach provides a new state of the art.

## Code
The code is under license of Daimler AG and is not published.
