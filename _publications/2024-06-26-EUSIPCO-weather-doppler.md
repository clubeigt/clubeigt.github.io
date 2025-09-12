---
title: "Deliberate model misspecification for weather radar signal Doppler spectrum moments estimation"
collection: publications
permalink: /publication/2024-08-26-EUSIPCO-weather-doppler
excerpt: 'This paper presents an estimation method of the first two moments (mean power and mean frequency) of the Doppler spectrum of radar weather signals based on a signal model misspefication. The Misspecified Cramér-Rao bound is used to evaluate the performance of the proposed approach.'
date: 2024-08-26
venue: '32nd European Signal Processing Conference (EUSIPCO)'
doi: ''
---
Deliberate model misspecification can be a way to work around over-complicated estimation problems. In weather radar signal estimation, the key parameters involved in most numerical weather prediction algorithms are the first two moments of the signal Doppler spectrum: the mean power, related to reflectivity coefficients and the mean Doppler frequency, related to the mean radial velocity. The spectral width of the Doppler spectrum is not always used (or even estimated) in operational systems which lets think that one could simply discard this parameter and apply potentially simpler estimators to obtain the desired estimates. This falls in the field of estimation theory under model misspecification in the case of an unconditional signal model. In this contribution, the misspecified Cramér-Rao bound for the problem at hand is evaluated to compare two estimators: the candidate mismatched unconditional maximum likelihood estimator and the pulse-pair estimator widely used in operational systems. Simulations show how the spectral width affects the considered estimators performance. The widely used pulse-pair estimator happens to remain the best option being both unbiased and with a fairly simple implementation, even though there is still room for improvement for the estimation of the mean Doppler frequency.

[Author version](http://clubeigt.github.io/files/2024_EUSIPCO_weather_doppler.pdf)

Recommended citation: Corentin Lubeigt, &quot;Deliberate model misspecification for weather radar signal Doppler spectrum moments estimation,&quot; <i>32nd European Signal Processing Conference (EUSIPCO)</i>, Lyon, France, August 2024.

[Bibtex](http://clubeigt.github.io/files/2024_EUSIPCO_weather_doppler_bib.bib)