---
title: Home
---

{% assign avatar = site.avatar %}{% unless avatar contains "://" %}{% assign avatar = avatar | relative_url %}{% endunless %}
<div class="avatar"><img src="{{ avatar }}" alt="Photo of {{ site.author }}" /></div>

# Santosh Hanamappa Mokashi

<h2 class="tagline">Tearing down the memory wall, one DRAM row at a time.</h2>

I am an Electronics and Communication Engineering graduate from [PES University](https://pes.edu/) (B.Tech, 2026) and a Digital Design and DFT Intern at [Omni Design Technologies](https://www.omnidesigntech.com/) in Bengaluru. I am applying for PhD programs in **computer architecture**, focusing on **DRAM / memory systems** and **AI hardware**.

AI workloads are increasingly limited by the *memory wall*: moving data to and from DRAM, not compute, dominates latency and energy. I developed an execution-aware DRAM scheduling architecture for near-memory AI accelerators that cut DRAM activity by ~50% (Micron Memory Awards, Taiwan), building on hands-on RTL/SoC design, FPGA prototyping, DFT, and SRAM circuit design.

I am happy to talk about:

📝 **Research**: memory scheduling, near-/in-memory computing for AI, and energy-efficient memory systems.

💻 **Hardware**: RISC-V cores, SoC integration, and open-source silicon (SKY130, Tiny Tapeout).

If you're working on something in this space, reach out on [LinkedIn]({{ site.linkedin }}) or via [email](mailto:{{ site.email }})!

<div class="clear"></div>

### News

<ul class="news">
{% for n in site.data.news %}
  <li><strong>{{ n.date | replace: ".", "/" | split: "/" | reverse | join: "/" }}</strong> &mdash; {{ n.text }}</li>
{% endfor %}
</ul>

### Recent Blogs

<ul class="posts">
{% for post in site.categories.portfolio1 limit: 5 %}
  <li><span class="date">{{ post.date | date: "%Y/%m/%d" }}</span> <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
