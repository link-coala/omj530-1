---
layout: page
title: música
permalink: /musica/
---
{% for post in site.categories.musica %}
 <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
 <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}

