---
layout: page
title: Jekyll
permalink: /blog/categories/jekyll/
---

<h5> Projects by Course : {{ page.title }} </h5>

<div class="row">
{% for post in site.categories.jekyll %}
 <li class="card blog-post"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>