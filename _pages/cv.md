---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
---------
* B.A. in Physics & Mathematics, Clark University, 2016
* M.S. in Physics, Stanford University, 2019
* Ph.D in Physics, Stanford University, 2024 (expected)

<!-- Work experience
---------------
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
   -->

Skills
------
* Low temperature and condensed matter physics
  * Cryogenic scanning probe microscopy
  * Electromagnetic modeling of superconducting devices
  * Operation of cryogen-free dilution refrigerators
  * Instrument control and measurement automation
* Quantum computing
 * Characterization and calibration of superconducting qubits and cavities
 * Modeling dynamics of open quantum systems (QuTiP)
 * Dynamical decoupling noise spectroscopy
 * RF electronics for quantum control
* Scientific programming
  * Scientific Python (numpy, scipy, matplotlib, pandas, JAX, ...)
  * MATLAB
  * Git and GitHub
  * Interfacing with HPC (slurm)

Publications
------------
  <ol reversed>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>
  
Talks
-----
  <ol reversed>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ol>
  
Teaching
--------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
