---
layout: page
title: "Past"
description: "Past seminars"
header-img: "img/ens-fountain.jpg"
---

You can find below the list of past seminars.



{% for oneitem in site.data.past %}
<p>
  {{ oneitem.date }}, <a href="{{ oneitem.url }}">{{ oneitem.speaker }}</a> ({{ oneitem.affiliation }})
  {% if oneitem.video == "nothing" %}
  {% else %}
    [<a href="{{ oneitem.video }}">video</a>]
  {% endif %}
  {% if oneitem.slides == "nothing" %}
  {% else %}
    [<a href="../slides/{{ oneitem.slides }}">Slides</a>]
  {% endif %}
  <br/>
  <b>Title:</b> <i>{{ oneitem.title }}</i><br/>
  <b>Abstract:</b> {{ oneitem.abstract }}
  </p>
{% endfor %}
