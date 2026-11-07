---
title: Papers
---

### Papers

{% for pub in site.data.publications %}
- **{{ pub.title }}** — {{ pub.authors }}, _{{ pub.venue }}_, {{ pub.year }}.{% if pub.status %} <span class="status">{{ pub.status }}</span>{% endif %}{% for l in pub.links %} [[{{ l.name }}]]({{ l.url }}){% endfor %}
{% endfor %}

### Posters & Presentations

- **DAC Young Fellows poster** — 63rd Design Automation Conference, Long Beach, USA, 2026.
- **Execution-Aware DRAM Scheduling for Edge-AI Applications** — Micron Memory Awards, Taiwan, 2026.

More on [Google Scholar]({{ site.scholar }}) and [arXiv]({{ site.arxiv }}).
