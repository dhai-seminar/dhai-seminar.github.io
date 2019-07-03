---
layout: page
title: "The DHAI Seminar"
description: "when Digital Humanities meets Artificial Intelligence"
header-img: "img/ens1.png"
---

Welcome to the blabla.



Goal
============================

Bloblo

You can check the list of the next seminars below and the [list of past seminars](../past/).


Next seminar
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

- Me
- You


Supported by
===========================


<p align="center">

TODO add some logos.

<a href="http://www.ens.fr">
<img width="200" src="img/logo-ens.jpg"/>
</a>


</p>
