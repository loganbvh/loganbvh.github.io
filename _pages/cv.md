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

<!-- Experience
----------
* January 2021 - present: Graduate Research Assistant
  * Department of Physics, Stanford University, Stanford, CA
  * Duties included: Tagging issues
  * Advisor: Kam Moler

* January 2019 - January 2021: Research Associate
  * Quantum Circuits, Inc. (QCI), New Haven, CT
  * Duties included: Tagging issues
  * Supervisors: Harvey Moseley, Rob Schoelkopf

* September 2017 - December 2018: Graduate Research Assistant
  * Department of Physics, Stanford University, Stanford, CA
  * Duties included: Tagging issues
  * Advisor: Kam Moler

* Summer 2016: Undergraduate Research Assistant
  * Cornell Center for Materials Research, Cornell University, Ithaca, NY
  * Duties included: Tagging issues
  * Advisor: Dan Ralph

* June 2014 - December 2016: Undergraduate Research Assistant
  * Department of Physics, Clark University, Worcester, MA
  * Measurements of the RF penetration depth in unconventional superconductors at high magnetic fields.
  * Advisor: Charles Agosta -->

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
