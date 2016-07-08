---
layout: page
title: plugs
permalink: /plugs/
---
{% for post in site.categories.plugs %}
 <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
 <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}