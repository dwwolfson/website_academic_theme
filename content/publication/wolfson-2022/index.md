---
title: Using Piecewise Regression to Identify Biological Phenomena in Biotelemetry
  Datasets
date: '2022-07-01'
draft: false

publishDate: '2022-09-30T16:46:35.280265Z'
authors:
- David W. Wolfson
- David E. Andersen
- John R. Fieberg
tags:
- '"biotelemetry"'
- '"segmentation"'
- '"change point"'
- '"movement"'
- '"Trumpeter Swan"'
- '"Sandhill Crane"'
- '"Moose"'
- '"Black Bear"'
publication_types:
- 2
abstract: Technological advances in the field of animal tracking have greatly expanded the potential to remotely monitor animals, opening the door to exploring how animals shift their behaviour over time or respond to external stimuli. A wide variety of animal-borne sensors can provide information on an animal's location, movement characteristics, external environmental conditions and internal physiological status. Here, we demonstrate how piecewise regression can be used to identify the presence and timing of potential shifts in a variety of biological responses using multiple biotelemetry data streams. Different biological latent states can be inferred by partitioning a time-series into multiple segments based on changes in modelled responses (e.g. their mean, variance, trend, degree of autocorrelation) and specifying a unique model structure for each interval. We provide six example applications highlighting a variety of taxonomic species, data streams, timescales and biological phenomena. These examples include a short-term behavioural response (flee and return) by a trumpeter swan *Cygnus buccinator* following a GPS collar deployment; remote identification of parturition based on movements by a pregnant moose *Alces alces*; a physiological response (spike in heart-rate) in a black bear *Ursus americanus* to a stressful stimulus (presence of a drone); a mortality event of a trumpeter swan signalled by changes in collar temperature and overall dynamic body acceleration; an unsupervised method for identifying the onset, return, duration and staging use of sandhill crane *Antigone canadensis* migration; and estimation of the transition between incubation and brood-rearing (i.e. hatching) for a breeding trumpeter swan. We implement analyses using the mcp package in R, which provides functionality for specifying and fitting a wide variety of user-defined model structures in a Bayesian framework and methods for assessing and comparing models using information criteria and cross-validation measures. These simple modelling approaches are accessible to a wide audience and offer a straightforward means of assessing a variety of biologically relevant changes in animal behaviour.
featured: false
publication: '*Journal of Animal Ecology*'
url_pdf: https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.13779
doi: 10.1111/1365-2656.13779
---

