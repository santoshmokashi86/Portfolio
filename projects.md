---
layout: default
title: Projects
---

# Projects

Research and engineering projects. Where code is public, click **GitHub repo** to open the repository. Everything else is at [github.com/{{ site.github_username }}](https://github.com/{{ site.github_username }}).

## Research

{% for p in site.data.projects.research %}
  {% include project.html project=p %}
{% endfor %}

## Hardware Design &amp; Verification

{% for p in site.data.projects.engineering %}
  {% include project.html project=p %}
{% endfor %}

[Back to home]({{ "/" | relative_url }})
