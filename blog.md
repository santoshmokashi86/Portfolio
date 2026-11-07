---
layout: default
title: Blog
---

# Blog Posts

### Notes on memory systems, hardware design, and the road to a PhD.

{% for post in site.posts %}{% if post.categories contains 'portfolio1' %}{% continue %}{% endif %}
## [{{ post.title }}]({{ post.url | relative_url }})
Date: {{ post.date | date: "%Y-%m-%d" }}
{{ post.excerpt | strip_html | truncatewords: 50 }}
{% endfor %}

[Back to home]({{ "/" | relative_url }})
