---
layout: resume
title: Hobby projects
number: 3
---

{% for item in site.hobby_projects %}
  <div>
    <b>{{item.name}}</b> - {{item.short_description}}
    {{item.content | markdownify}}
  </div>
{% endfor %}