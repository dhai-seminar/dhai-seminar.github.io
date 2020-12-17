---
layout: page
title: "The DHAI Seminar"
description: "When Digital Humanities Meet Artificial Intelligence"
header-img: "img/ens-snow.jpg"
---

Welcome to the Digital Humanities / Artificial Intelligence Seminar!



Goal
============================

Fostered by the creation of new algorithms, computation power and the development of deep learning techniques, Artificial Intelligence needs constantly to confront new issues and data sets in order to deepen its methodologies and increase its range of scientific applications.
Digital humanities, developing digital science methodologies in the study of humanities and using the critical approaches of humanities in the analysis of the contemporary "digital revolutions", are constantly in search of new tools to explore more and more complex and diversified data sets.

The coupling AI/DH is globally emerging as one key interface for both domains and will probably prove to be a deep transformative trend in tomorrow intellectual world.

The ambition of this seminar is to be one of the places where this coupling is shaped, fostered and analyzed. It intends to offer a forum where both communities, understood in a very inclusive way, exchange around emerging issues, ongoing projects, and past experiences in order to build a common language, a shared space, and to encourage innovative cooperation on the long run.

Mailing list
===========================

You can [subscribe to the mailing list from here](https://docs.google.com/forms/d/e/1FAIpQLSdQPssRAUxsw2ixoO0LtEXwLtgTpXtNCI9oUSDmQOv2HV5EVg/viewform?usp=sf_link), in order to receive the announcements of the seminars.



Past seminars
===========================

You can access [here the list of past seminars](../past/).


Next seminars
===========================


{% for oneitem in site.data.next %}
<p>
  {{ oneitem.date }}, {{ oneitem.time }}, room {{ oneitem.room }}.<br/>
  <a href="{{ oneitem.url }}">{{ oneitem.speaker }}</a>  ({{ oneitem.affiliation }})<br/>
  <b>Title:</b> <i>{{ oneitem.title }}</i><br/>
  <b>Abstract:</b> {{ oneitem.abstract }}
  </p>
{% endfor %}


Scientific Committee
============================

- [Segolene Albouy](https://github.com/Segolene-Albouy)
- [Mathieu Aubry](http://imagine.enpc.fr/~aubrym/)
- [Jean-Baptiste Camps](http://www.chartes.psl.eu/fr/jean-baptiste-camps)
- [Matthieu Husson](https://syrte.obspm.fr/spip/science/histoire/membres-de-l-equipe/article/matthieu-husson)
- [Béatrice Joyeux-Prunel](https://artlas.huma-num.fr/en/staff-member/beatrice-joyeux-prunel-2/)
- [Gabriel Peyré](http://www.gpeyre.com)
- [Thierry Poibeau](https://www.lattice.cnrs.fr/membres/direction/thierry-poibeau/)
- [Léa Saint-Raymond](https://u-paris10.academia.edu/LéaSaintRaymond)


Supported by
===========================


<p align="center">

<a href="https://www.psl.eu/">
<img width="400" src="img/psl-logo.png"/></a>

<br/><br/>

<a href="http://www.enpc.fr/"><img height="90" src="http://www.enpc.fr/sites/all/themes/enpc/images/logo.svg"/></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://prairie-institute.fr">
<img height="60" src="img/logo-prairie.png"/></a><br/>

<a href="https://ellis-paris.github.io/">
<img src="img/EllisUnit-small.png" width="400"/>
</a>

</p>
