---
layout: page
permalink: /theses
title: theses
description: Collection of my Dissertations/Theses
---

### ECE University of Patras Thesis

My thesis title was '**Stereo Vision of Dual View Meteosat Images**' and it was conducted in collaboration with the Vrije Universiteit Brussel [VUB](https://www.vub.be/en/home) and the Royal Meteorological Institute of Brussels [KMI](https://www.meteo.be/en).

The primary supervisor from University of Patras was [Prof. Athanassios Skodras](http://www.ece.upatras.gr/skodras/).

Its central objective was the application of advanced stereo vision techniques for the estimation of cloud height based on images from the MSG-3 and MSG-1 satellites.

In the context of the thesis I have specifically focused on the following:

1. Extensive review of prior work regarding image registration methods.
2. Implementation of several state-of-the-art image registration methods. Specifically, I have compared two major algorithmic family of methods, i.e.
    * One operating on the pixel domain, which is based on the maximization of the Mutual Information of the image pair and
    * One operating on the low-level features of the images. In this approach, the features were extracted using the SIFT and SURF algorithms. The transformation model for registering the images was estimated using these features and the RANSAC algorithm.
3. Review and application of Graph Cut algorithms based on the Markov Random Fields theory to extract the disparity map.

Download: <a class="page-link" href="https://cdn.jsdelivr.net/gh/tsikup/AwesomeCV@master/assets/pdf/tsik-thesis.pdf"
          target="_blank">PDF</a> (English)