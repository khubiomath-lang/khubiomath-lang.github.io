---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
description: Research interests, ongoing projects, and selected publications.
---

## Overview
I work on **infectious disease modeling and forecasting**, with a focus on integrating
**time-series methods**, **network data analysis**, and **simulation-based approaches**
(e.g., agent-based models). My goal is to develop models that are both
**mechanistically interpretable** and **predictively useful** for real-world public health settings.

---

## Research interests
- **Time-series forecasting for infectious diseases**
  - probabilistic forecasting, ensemble modeling, evaluation (proper scoring rules)
- **Network data analysis in epidemiology**
  - infection tracing networks, super-spreading events (SSEs), age-structured transmission
- **Simulation & decision-making**
  - agent-based modeling (ABM), scenario analysis, optimization and (future) reinforcement learning for intervention design

---

## Current directions (short)
**Hybrid forecasting:** combining mechanistic epidemic models with deep learning features.  
**Network-informed dynamics:** representing heterogeneity via contact structures and age mixing.  
**Policy evaluation:** comparing strategies under uncertainty and changing epidemiological conditions.

---

## Selected publications
> This section renders from `_bibliography/papers.bib` (al-folio).
>
> If you haven’t added your BibTeX yet, create/modify the file and add entries there.

{% bibliography --query @*[selected=true]* %}

<p style="margin-top: 0.5rem;">
If the list is empty, mark your BibTeX entries with <code>selected = {true}</code>.
</p>

---

## All publications
If you prefer to show everything on this page as well:

{% bibliography %}

---

## Projects
> This section renders project cards from `_projects/`.

{% include projects.html %}

---

## Methods / tools (optional)
- Programming: Python (NumPy/Pandas/SciPy), R
- Modeling: compartmental models, stochastic simulation, network models
- Reproducibility: version control, structured pipelines, transparent evaluation

---

## Contact
If you’d like to collaborate, feel free to reach out via the contact links on the site.
