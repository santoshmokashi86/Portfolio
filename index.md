---
layout: default
title: Home
---

I am an Electronics and Communication Engineering graduate from [PES University](https://pes.edu/) (B.Tech, 2026), currently an intern at [Omni Design Technologies](https://www.omnidesigntech.com/), and I am applying for PhD programs in **computer architecture**. My work sits at the intersection of **DRAM / memory systems** and **AI hardware**.

AI workloads are increasingly limited by the *memory wall*: moving data to and from DRAM, not compute, dominates latency and energy. My research asks how the memory system itself can become workload-aware. I developed an execution-aware DRAM scheduling architecture for near-memory AI accelerators that cut DRAM activity by ~50% (Micron Memory Awards, Taiwan). That work builds on hands-on experience across the stack: RTL/SoC design, FPGA prototyping, DFT, and SRAM circuit design.

**Research interests**
<ul class="interests">
  <li>DRAM architecture and memory scheduling</li>
  <li>Near-/in-memory computing for AI</li>
  <li>Energy-efficient, reliable memory systems</li>
  <li>Hardware/software co-design</li>
</ul>

## Publications

{% for pub in site.data.publications %}
  {% include publication.html pub=pub %}
{% endfor %}

<small>[All publications &rarr;]({{ "/publications.html" | relative_url }})</small>

## Research Projects

{% for p in site.data.projects.research %}{% if p.featured %}
  {% include project.html project=p %}
{% endif %}{% endfor %}

<small>[All projects and GitHub repositories &rarr;]({{ "/projects.html" | relative_url }})</small>

## Experience

<table class="timeline">
  <tr><td>Apr 2026 – present</td><td><strong>Digital Design and DFT Intern, Omni Design Technologies</strong><br>
    Implemented the DFT flow for TSMC 28 nm PVT IPs with Cadence Modus (99.78% stuck-at, 92% at-speed fault coverage). Developing and verifying RTL modules and APB interfaces in Cadence Xcelium / SimVision.</td></tr>
  <tr><td>Feb 2026 – Mar 2026</td><td><strong>Digital and SoC Design Intern, UniConverge Technologies</strong></td></tr>
  <tr><td>Jan 2025 – Jan 2026</td><td><strong>Project Trainee, CHIPS, PES University</strong><br>
    Center for Heterogeneous and Intelligent Processing Systems, with the VLSI Society of India. AHB micro-architecture RTL for a RISC-V SoC; AHB–APB integration of three IP blocks at 100 MHz; subsystem/IP-level verification architecture, validated in simulation with Vivado.</td></tr>
  <tr><td>Feb 2025 – May 2025</td><td><strong>Samsung Fellow / Trainee, India Semiconductor Workforce Development Program (ISWDP)</strong><br>
    Levels 1–Advanced in TCAD: 2D process and 3D device simulation, meshing strategies, physical models, mixed-mode simulation, AC and thermal analysis, and electrical/RF characterization.</td></tr>
  <tr><td>Jun 2024 – Jul 2024</td><td><strong>Summer Intern, cRAIS, PES University</strong><br>
    Center for Robotics, Automation and Intelligent Systems: ROS 2, Gazebo and RViz; drone applications in disaster and warehouse management.</td></tr>
  <tr><td>Dec 2022 – Jul 2026</td><td><strong>B.Tech, Electronics and Communication Engineering</strong><br>PES University, Bengaluru, India</td></tr>
</table>

## Honours &amp; Fellowships

<table class="timeline">
  <tr><td>Sep 2026</td><td><strong>CHIA Hackathon, A³ Workshop @ MICRO 2026</strong>: selected participant; funded GCP/Gemini compute to build agentic loops for HW/SW co-design (sponsored by Google and NVIDIA).</td></tr>
  <tr><td>Mar 2026</td><td><strong>DAC Young Fellow</strong>, 63rd Design Automation Conference, Long Beach, USA; travel grant to present a poster.</td></tr>
  <tr><td>Jan 2026</td><td><strong>Micron Memory Awards (Taiwan)</strong>: execution-aware DRAM scheduling for edge AI.</td></tr>
  <tr><td>Jan 2025</td><td><strong>Samsung Fellowship</strong>, Cohort 4, India Semiconductor Workforce Development Program (IISc Bangalore, Synopsys, Samsung Semiconductor); selected from 2,500+ applicants.</td></tr>
  <tr><td>—</td><td><strong>InFeynite Hackathon</strong>: Distinction Certificate.</td></tr>
</table>

## Skills

<table class="timeline">
  <tr><td>Languages</td><td>Verilog, SystemVerilog, C, Python</td></tr>
  <tr><td>Memory &amp; AI HW</td><td>Ramulator, SCALE-Sim, DRAM scheduling under JEDEC constraints (DDR5), RISC-V ISA extensions</td></tr>
  <tr><td>EDA</td><td>Cadence Xcelium, SimVision, Genus, Modus, Virtuoso, Assura; Xilinx Vivado</td></tr>
  <tr><td>FPGA</td><td>Xilinx PYNQ-Z2 prototyping, timing closure</td></tr>
  <tr><td>Protocols &amp; flows</td><td>AMBA AHB, APB, UART; RTL-to-GDSII; DFT; static timing analysis; TCAD</td></tr>
  <tr><td>Certifications</td><td>Cadence Design for Test Fundamentals v25.1 · Cadence Basic Static Timing Analysis v3.0 · Cadence Essentials of SystemVerilog for UVM (training) · ISWDP Advanced Level</td></tr>
  <tr><td>Languages</td><td>English (professional), Kannada (native), Hindi (elementary)</td></tr>
</table>

## Leadership &amp; Service

- **Secretary**, IEEE Photonics/SSCS Joint Student Branch Chapter, PES University (Sep 2024 – Jan 2026)
- **Campus Ambassador**, Indian Science Technology and Engineering facilities Map (I-STEM) (May 2025 – May 2026)
- **Co-Founder**, [Apna MeetUp](https://www.apnameetup.com/) (Jan 2024 – Sep 2024)
- Teaching assistant and mentor in student technical communities

## Other

<span style="font-size:18px;">[Blog]({{ "/blog.html" | relative_url }})</span> for notes on research and the PhD application process.
