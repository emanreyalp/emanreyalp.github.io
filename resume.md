---
layout: resume
title: Resume
permalink: /resume
---

{% include resume-title.html %}

<div class="sections">
{% assign sections = site.sections | sort: 'number' %}
{% for section in sections %}
  <section class="section">
    <h2 class="section-title"> {{section.title}} </h2>
    {{section.content | markdownify}}
  </section>
{% endfor %}
</div>
