---
layout: page
title: peliculas
permalink: /peliculas/
---
{% for post in site.categories.peliculas %}
 <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
 <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}


