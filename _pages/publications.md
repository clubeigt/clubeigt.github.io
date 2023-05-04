---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
test 3

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

test 2

{% include base_path %}

test 1

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Journals
---
0. Corentin Lubeigt, Lorenzo Ortega, Jordi Vilà-Valls, Laurent Lestarquit, Eric Chaumette, &quot;Joint delay-doppler estimation performance in a dual source context,&quot; <i>Remote Sensing</i>, <b>2020</b>, 12(23), 3894.
0. Corentin Lubeigt, Lorenzo Ortega, Jordi Vilà-Valls, Laurent Lestarquit, Eric Chaumette, &quot;On the impact and mitigation of signal crosstalk in ground-based and low altitude airborne GNSS-R,&quot; <i>Remote Sensing</i>, <b>2021</b>, 13(6), 1085.
0. Corentin Lubeigt, Lorenzo Ortega, Jordi Vilà-Valls, Laurent Lestarquit, Eric Chaumette, &quot;Clean-to-Composite Bound Ratio: a multipath criterion for GNSS signal design and analysis,&quot; <i>IEEE Transactions on Aerospace and Electronic Systems</i>, <b>2022</b>, Vol. 58, no. 6, pp. 5412--5424.
0. Corentin Lubeigt, Lorenzo Ortega, Jordi Vilà-Valls, Eric Chaumette, &quot;Untangling first and second order statistics contributions in multipath scenarios,&quot; <i>Signal Processing</i>, <b>2023</b>, Vol. 205, 108868.
0. Corentin Lubeigt, Lorenzo Ortega, Jordi Vilà-Valls, Eric Chaumette, &quot;Band-limited impulse response estimation performance,&quot; <i>Signal Processing</i>, <b>2023</b>, Vol. 208, 108998.
0. Corentin Lubeigt, François Vincent, Lorenzo Ortega, Jordi Vilà-Valls, Eric Chaumette, &quot;Approximate maximum likelihood time-delay estimation for two closely spaced sources,&quot; <i>Signal Processing</i>, <b>2023</b>, Vol. XXX, 109056.
{: reversed="reversed"}

### International Conferences
---
0. Corentin Lubeigt, Lorenzo Ortega, Jordi Vilà-Valls, Laurent Lestarquit, Eric Chaumette, &quot;Multipath estimating techniques performance analysis,&quot; <i>IEEE Aerospace Conference (AERO)</i>, <b>March 2022</b>, Big Sky, MT, USA.
0. Corentin Lubeigt, François Vincent, Lorenzo Ortega, Jordi Vilà-Valls, Laurent Lestarquit, Eric Chaumette, &quot;Close-to-ground single antenna GNSS-R,&quot; <i>ESA Workshop on Satellite Navigation Technologies and European Workshop on GNSS Signals and Signal Processing (NAVITEC)</i>, <b>April 2022</b>, Online event.
{: reversed="reversed"}

### National Conferences
---
0. Corentin Lubeigt, Jordi Vilà-Valls, Laurent Lestarquit, Eric Chaumette, &quot;Les signaux à bande large au service de la réflectométrie par GNSS à site bas,&quot; <i>Colloque du Groupe de Recherche et d'Etudes de Traitement du Signal et des Images (GRETSI)</i>, <b>September 2022</b>, Nancy, France.
{: reversed="reversed"}