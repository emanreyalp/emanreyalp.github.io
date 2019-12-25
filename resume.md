---
layout: resume
title: Resume
permalink: /resume
---

# Gergely Dömök
{% assign sections = site.sections | sort: 'number' %}
{% for section in sections %}
  <div>
    <h2> {{section.title}} </h2>
    {{section.content | markdownify}}
  </div>
{% endfor %}

https://ben.balter.com/2015/02/20/jekyll-collections/