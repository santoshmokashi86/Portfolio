---
title: "Why I Care About the Memory Wall"
date: 2026-11-07
author: Santosh H. Mokashi
tags: [DRAM, AI hardware]
---

Modern AI accelerators can perform trillions of operations per second, yet much of the time they sit waiting for data. Fetching an operand from DRAM costs orders of magnitude more energy than computing on it. This is the *memory wall*, and it is the reason I am pursuing research in memory-centric computer architecture.

In my DRAM scheduling project for the Micron Memory Awards, we asked a simple question: *what if the memory controller knew what the accelerator was about to execute?* Making scheduling execution-aware, and evaluating it with Ramulator and SCALE-Sim under JEDEC DDR5 timing, reduced DRAM activity by about 50% and saved up to 33% energy.

*(This is a starter post. Edit or replace it in `_posts/`.)*
