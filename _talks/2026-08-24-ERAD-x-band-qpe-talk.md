---
title: "European Conference on Radar in Meteorology and Hydrology (ERAD) 2026"
collection: talks
type: "Conference"
permalink: /talks/2026-08-24-ERAD-x-band-qpe-talk
venue: "Metropol Palace Hotel"
date: 2026-05-24
location: "Belgrade, Serbia"
---

Presentation on *Towards a better use of X-band radars in a national weather radar network for QPE* at ERAD 2026 conference that took place Metropol Palace Hotel in Belgrade, Serbia. This is a joint work with Ludovic Bouilloud and Nan Yu.


Even though weather radars are providing observations over a rather extended coverage, a network of radars is often needed to cover a large area such as a region or a country. The choice of the radar technology depends on the budget constraints, the confidence in this technology, the specificities of the terrain and the nature of the phenomena to be observed.

Météo-France mainland weather radar network is composed of three radars types : C-band radars for most of the land coverage with few mountainous areas, S-band radars around the Mediterranean Sea for extreme events and X-band radars at locations where there is a need of extra coverage, in plains where the network coverage is less dense and essentially in the French Alps where the orography creates strong masks.

Each radar is providing 3D observation data with, associated to each cell, a weighting coefficient (Tabary et al. 2007) that mostly depends on the beam width, beam blockage, signal attenuation (due to radome, gas and precipitations) and the beam height (which is the main parameter). Based on a combination of these weighting coefficients, 2D quantitative precipitation estimation (QPE) product is elaborated for each radar with an associated quality indicator representing the confidence on the estimated quantity of precipitation. The final national composite product is obtained by averaging all contributing radars of a considered pixel, weighted by their corresponding quality indicators.

From this composition procedure, it is clear that the quality indicator, and the underlying weighting coefficients must be built in order to make the best use of each radar data. The question of their building has been studied for decades now and several standard have been proposed to try to find a homogeneous way to combine radar data regardless of the specificities of the radar technology and location (Holleman et al. 2006).

At Météo-France, the method to compute the quality indicator is almost the same for all types of radars, slight differences appear regarding the signal attenuation. This becomes a problem for X-band radars when very strong attenuation and/or close-by melting layer situations occur where the data from X-band radar is less exploitable. In fact, the current quality indicator, which depends strongly on the beam height, results in static quality indicator maps where the indicator does not really change when the situation degrades due to attenuation and/or close-by melting layer. In the radar data composition, X-band radar data with important attenuation correction (hence, possibly less reliable) is often used, rather than C-band or S-band radar data with less attenuation simply because the X-band radar beam is closer to the surface.

In this study, the quality indicator has been redesigned in order to better combine radar data considering the known weaknesses of X-band radars. This approach takes into account the radar maximum range, the location of the beam relatively to the melting layer and the estimation of attenuation. It has been tested over several X-band radars of Météo-France network in different weather situations (winter when the bright band is low enough and summer when intense storm strongly attenuated the signal) and evaluated over an extended period of time. Scores on the resulting radar QPE over rain gauges, compared to the operational product are evaluated to assess the proposed approach.

[Presentation slides](http://clubeigt.github.io/files/2026_ERAD_x_band_qpe_presentation.pdf)