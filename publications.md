---
layout: default
title: Publications
---

# Publications

See also: [Google Scholar]({{ site.scholar }}) · [arXiv]({{ site.arxiv }})

{% for pub in site.data.publications %}
  {% include publication.html pub=pub show_summary=true %}
{% endfor %}

## Posters &amp; Presentations

- Poster, **DAC Young Fellows**, 63rd Design Automation Conference, Long Beach, USA, 2026.
- Execution-Aware DRAM Scheduling for Edge-AI Applications, **Micron Memory Awards**, Taiwan, 2026.

[Back to home]({{ "/" | relative_url }})
