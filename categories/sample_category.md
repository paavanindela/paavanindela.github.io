---
layout: page
title: Guides
permalink: /blog/categories/sample_category/
---

<h5> Projects by Course : {{ page.title }} </h5>

<div class="row">
{% for post in site.categories.sample_category %}
 <li class="card blog-post"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>