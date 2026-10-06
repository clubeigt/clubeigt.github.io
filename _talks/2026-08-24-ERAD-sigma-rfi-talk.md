---
title: "European Conference on Radar in Meteorology and Hydrology (ERAD) 2026"
collection: talks
type: "Conference"
permalink: /talks/2026-08-24-ERAD-sigma-rfi-talk
venue: "Metropol Palace Hotel"
date: 2026-05-24
location: "Belgrade, Serbia"
---

Poster-based presentation on *Detection and mitigation of RLAN interference in C-band weather radar* at ERAD 2026 conference that took place Metropol Palace Hotel in Belgrade, Serbia. This is a joint work with Mohand Tahanout.


Radio Local Area Network (RLAN) devices and C-band weather radars share the same frequency band. When RLAN devices transmit at the same or close frequency as weather radar, the resulting interference can severely limit the usefulness of radar images, creating radial patterns that affect the ability of the radar to properly detect weather echoes.

In order to avoid interfering weather radars, the International Telecommunication Union (ITU) demands the integration of a Dynamic Frequency Selection (DFS) protocol into RLAN devices. This protocol aims at detecting the presence of a weather radar in the vicinity and switching into an unused frequency band. Unfortunately, DFS is not always implemented or enabled and interference of weather radars occurs frequently.
Besides, the required DFS specifications were initially adapted to conventional tube-based weather radar systems. These radars usually transmit powerful short pulses (hundreds kW during 0.5 to 5 microseconds). However,  emerging weather radars based on solid-state transmitters, transmit weaker and longer pulses (a few kW for up to 100 microseconds). This new operating mode may cause the current DFS protocol to fail to detect weather radars and lead to interference. Therefore, whether solid-state radars are used or the RLAN DFS is not working, interference with weather radar is an open topic that needs to be addressed as it affects the quality of the output data.

To tackle this issue, several techniques exist for detecting and mitigating the artifacts caused by interference. Detection is usually performed on the radar reflectivity, where strong gradients are detected along the azimuths. The radial shape of the interference is very characteristic and, combined with other dual polarization data, can also be detected using a well-trained classification algorithm. Generally, the contaminated data are removed and replaced by data from higher elevation angle or interpolation of surrounding valid data.

Another way to detect interference is to work directly on the raw signal, two options are then of interest:  first, for a given pixel, a certain number of pulses are considered to estimate radar variables and only a few of them are actually affected by interference. In this study, the detection is performed using SIGMA, a pulse-to-pulse ground clutter indicator used at Météo-France. SIGMA is expressed in dB and is typically close to 0dB for ground clutter echoes, equal to 6dB for weather echoes and larger than 10dB for echoes contaminated with interference. The presentation includes an investigation into the statistical behavior of SIGMA from interference echoes. 
A second option explores the structure of the entire received signal (all possible ranges for a given azimuth) and attempts to detect significant changes between two consecutive pulse returns. Any significant difference is then associated with the presence of a RLAN packet signal. Once the interference is detected, the signal is then filtered out from the contaminated data.

The proposed approach is illustrated with both conventional and solid-state weather radars data, showcasing the efficiency of the detection procedure in different weather situations.

[Poster](http://clubeigt.github.io/files/2026_ERAD_sigma_rfi_poster.pdf)
