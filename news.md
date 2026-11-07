---
layout: default
title: News
---

# News

<table class="timeline">
{% for n in site.data.news %}
  <tr><td>{{ n.date }}</td><td>{{ n.text }}</td></tr>
{% endfor %}
</table>

[Back to home]({{ "/" | relative_url }})
