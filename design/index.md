---
layout: default
title: "Design"
category: design
sort_order: 1
breadcrumb: Design
---

<div class="page-header">
    <h1>{{ site.title }}</h1>
</div>

{% for page in site.pages %}
<h3><a title="{{ page.title }}" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h3>
{% endfor %}     
