---
layout: resume
title: Resume
permalink: /resume
---

# Gergely Dömök

{% assign sections = site.sections | sort: 'number' %}
{% for section in sections %}
  <div class="sections">
  <section class="section">
    <h2 class="section-title"> {{section.title}} </h2>

    {{section.content | markdownify}}
  </section>
  </div>
{% endfor %}
