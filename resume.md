---
layout: default
title: Resume
permalink: /resume
---

# Gergely Dömök

{% for item in site.sections %}
  <div>
    <h2> {{item.title}} </h2>
    {{item.content | markdownify}}
  </div>
{% endfor %}

https://ben.balter.com/2015/02/20/jekyll-collections/