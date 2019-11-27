---
layout: resume
title: Work experiences
number: 3
---

{% for item in site.work %}
  <div>
    <h3> {{item.period}} || <b> {{item.position}} - {{item.company}} </b> </h3>
    {{item.content | markdownify}}
  </div>
{% endfor %}