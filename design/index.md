---
layout: default
title: "Design"
category: design
sort_order: 1
---

<div class="page-header">
    <h1>{{ site.title }}</h1>
</div>

{% assign pages = (site.design | sort:"name" ) %}

{% for p in pages %}
  {{ p.name | capitalize }}
{% endfor %}
