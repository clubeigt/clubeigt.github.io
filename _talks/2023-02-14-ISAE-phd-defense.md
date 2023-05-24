---
title: "PhD Defense"
collection: talks
type: "Defense"
permalink: /talks/2023-02-14-phd-defense
venue: "Salle des thèses, ISAE-SUPAERO"
date: 2023-02-14
location: "Toulouse, France"
---

***Signal processing for GNSS reflectometry***

[Final version of the manuscript](/files/2023_PHD_thesis.pdf) 

[Presentation slides](/files/2023_PHD_defense_presentation.pdf)

Jury
----

President:

- Mr. Nabil EL KORSO, Professor at CentraleSupélec

Rapporteurs:

- Mr. Fabio DOVIS, Professor at Politecnico di Torino
- Mr. Guillaume GINOLHAC, Professor at Polytech Annecy-Chambéry

Examiners:

- Ms. Estel CARDELLACH, Research Director at ICE (IEEC-CSIC)

Supervisors:

- Mr. Laurent LESTARQUIT, Engineer at CNES
- Mr. Lorenzo ORTEGA, Professor at IPSA Toulouse
- Mr. Jordi VILA-VALLS, Professor at ISAE-SUPAERO
- Mr. Eric CHAUMETTE, Professor at ISAE-SUPAERO


Abstract
--------

Global Navigation Satellite Systems (GNSS) Reflectometry, or GNSS-R, is the study of GNSS signals reflected from the Earth’s surface. These so-called signals of opportunity, usually seen as a nuisance in standard navigation applications, contain meaningful information on the nature and relative position of the reflecting surface. Depending on the receiver platform (e.g., ground-based, airplane, satellite) and the reflecting surface itself (e.g., rough sea, lake), the reflected signal, more or less distorted, is difficult to model, and the corresponding methods to estimate the signal parameters of interest may vary.

This thesis starts from the navigation multipath problem in harsh environments, which can be seen as a dual source estimation problem where the main source is the signal of interest, and the secondary one is a single reflection of the main source. Depending on the scenario and the resources at hand, it is possible i) to estimate the parameters of interest (i.e., time-delay, Doppler frequency, amplitude and phase) of both sources, or ii) to estimate only one source’s parameters, although these estimates may be biased because of the interfering source. Either way, it is necessary to know the achievable performance for these estimation problems. For this purpose, tools from the estimation theory, such as the Cramér-Rao bound (CRB), can be used. In this thesis a CRB expression was derived for the properly specified case (dual source), and the misspecified one (single source). These bounds were compared to the performance obtained with different estimators, in order to theoretically characterize the problem at hand.

This study allowed to establish a clear mathematical framework that also fits the ground-based GNSS-R problem, for which the reflected signal is little distorted by the reflecting surface. In this case, the direct and reflected signals are close in time, which inevitably leads to interference, or crosstalk, and then to a clear performance degradation. Standard GNSS-R techniques, which do not perform well in this ground-based scenario, were compared to the CRB and two proposed approaches: i) a Taylor approximation of the dual source likelihood criterion when both sources are very close in time, and ii) a dual source estimation strategy to reduce or cancel the crosstalk. This part on ground-based GNSS-R was supported by a real data set, obtained from a data collection campaign organized by CNES (Toulouse, France). 

The problem changes slowly when the satellite elevation increases: the reflection, assumed coherent so far, turns non-coherent because of the reflecting surface roughness. The automatic detection of this transition (i.e., from coherent to non-coherent) is of great interest for future satellite missions. Reflection coherence is mainly observed by looking at the relative phase between the reflected and direct signals. Consequently, a statistical study of phase difference time series allowed to build tests that depend on the time series Gaussianity or regularity. The proposed tests were applied to a data set provided by the IEEC (Barcelona, Spain).

Finally, for scenarios where the reflecting surface distorts the signal significantly, it is necessary to adapt the signal model. The approach proposed in this thesis is to consider the received signal as a convolution between the transmitted signal and the reflecting surface impulse response. This signal model goes with the derivation of the corresponding CRB and the implementation of the maximum likelihood estimator. The question of the impulse response size determination, that is, the determination of the number of pulses required to describe the impulse response, was also tackled based on hypothesis tests. Simulation results show the potential of this approach.