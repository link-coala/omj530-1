---
layout: page
title: fotos
permalink: /fotos/
---

{% for post in site.categories.fotos %}
 <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
 <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}

