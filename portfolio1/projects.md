---
title: Projects
---

### Research Projects

{% for p in site.data.projects.research %}
<div class="project">
  <h3>{{ p.title }}</h3>
  <p class="meta">{{ p.date }}{% if p.venue %} · {{ p.venue }}{% endif %}</p>
  <p>{{ p.description }}</p>
  {% if p.highlights %}<ul>{% for h in p.highlights %}<li>{{ h }}</li>{% endfor %}</ul>{% endif %}
  <p>{% if p.repo %}[<a href="{{ p.repo }}">GitHub</a>] {% endif %}{% for l in p.links %}[<a href="{{ l.url }}">{{ l.name }}</a>] {% endfor %}<span class="tags">{{ p.tags | join: " · " }}</span></p>
</div>
{% endfor %}

### Hardware Design & Verification

<ul>
{% for p in site.data.projects.engineering %}
  <li><strong>{% if p.repo %}<a href="{{ p.repo }}">{{ p.title }}</a>{% else %}{{ p.title }}{% endif %}</strong>{% if p.date %} ({{ p.date }}){% endif %} — {{ p.description }}</li>
{% endfor %}
</ul>

All code: [github.com/{{ site.github_username }}](https://github.com/{{ site.github_username }})
