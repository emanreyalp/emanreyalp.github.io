---
layout: resume
title: Work experiences
number: 1
---

{% assign works = site.work | sort: 'number' %}
{% for item in works reversed %}
<div class="meta-info">
  <div class="row">
    <div class="col-md-8 job-title"><h4> {{item.position}}</h4></div>
    <div class="col-md-4 text-right period-time">{{item.period}}</div>
  </div>
  <div class="company"> {{item.company}} </div>
</div>
<div class="position-details">{{item.content | markdownify}}</div>
{% endfor %}
