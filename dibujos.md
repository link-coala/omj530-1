---
layout: page
title: dibujos
permalink: /dibujos/
---
{% for post in site.categories.dibujos %}
 <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
 <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}
