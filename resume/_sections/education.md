---
layout: resume
title: Education
number: 4
---

<ul>
  {% for item in site.data.education %}
    <div>
      <li>{{item.from}} - {{item.to}} || {{item.where}}</li>
    </div>
  {% endfor %}
</ul>
