---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Available as a PDF [here](../files/cv.pdf).

-----------------------

Education
---------
* Ph.D in Physics, Stanford University, in progress
* M.S. in Physics, Stanford University, 2019
* B.A. in Physics & Mathematics, Clark University, 2016

Experience <span style="font-size: .75rem"><em>(Click to expand)</em></span>
----------
<!-- https://github.com/gettalong/kramdown/issues/155#issuecomment-1024896918 -->

<details markdown="1">
  <summary markdown="span">January 2021 - present: Research Assistant, Stanford University</summary>

  * Department of Physics, Stanford University, Stanford, CA
  * Measurements and modeling of the local magnetic response and proximity effects in two-dimensional superconductors.
  * Advisor: Kam Moler
  * Publications from this period:
    - SuperScreen: An open-source package for simulating the magnetic response of two-dimensional superconducting devices, [Computer Physics Communications (2022)](../_publications/2022-07-27-compphys.md). Python package: [https://superscreen.readthedocs.io/](https://superscreen.readthedocs.io/)
    - Local imaging of diamagnetism in proximity-coupled niobium nanoisland arrays on gold thin films, [Physical Review B (2022)](../_publications/2022-08-30-prb-nb-islands.md) (*Editors' suggestion*).
</details>

<details markdown="1">
  <summary markdown="span">January 2019 - January 2021: Research Associate, Quantum Circuits, Inc.</summary>

  * Quantum Circuits, Inc. (QCI), New Haven, CT
  * Characterization and modeling of superconducting devices for quantum information processing using qubits encoded in microwave cavities.
  * Supervisors: Harvey Moseley, Rob Schoelkopf
  * Deliverables from this period:
    - [SeQuencing](https://sequencing.readthedocs.io/), an open-source Python package for simulating the dynamics of open quantum systems under realistic pulse sequences.
    - **qascade**, a (closed-source) Python package for estimating noise photon numbers at all stages of a quantum control microwave signal chain based on measured or simulated RF and thermal properties of microwave components.
</details>

<details markdown="1">
  <summary markdown="span">September 2017 - December 2018: Research Assistant, Stanford University</summary>

  * Department of Physics, Stanford University, Stanford, CA
  * Construction and optimization of a cryogen-free variable temperature scanning SQUID microscope; implemented digital flux feedback for SQUID readout using FPGAs.
  * Advisor: Kam Moler
  * Publications from this period:
    - Cryogen-free variable temperature scanning SQUID microscope, [Review of Scientific Instruments (2019)](../_publications/2019-06-25-rsi.md).
    - Imaging anisotropic vortex dynamics in FeSe, [Physical Review B (2019)](../_publications/2019-07-22-prb-fese.md).
</details>

<details markdown="1">
  <summary markdown="span">Summer 2016: Undergraduate Research Assistant, Cornell University</summary>

  * Cornell Center for Materials Research, Cornell University, Ithaca, NY
  * RF measurement and micromagnetic modeling of magnetic heterostructures for spintronics.
  * Advisor: Dan Ralph
  * Deliverables from this period:
    - Exploring Low-Frequency ST-FMR: Simulation and Experiment [[Report](../files/ccmr-final-lbvh.pdf), [Slides](../files/ccmr-pres-lbvh.pdf)]
</details>

<details markdown="1">
  <summary markdown="span">June 2014 - December 2016: Undergraduate Research Assistant, Clark University</summary>

  * Department of Physics, Clark University, Worcester, MA
  * Measurements of the RF penetration depth in unconventional superconductors at high magnetic fields.
  * Advisor: Charles Agosta
</details>

Skills <span style="font-size: .75rem"><em>(Click to expand)</em></span>
------
<details markdown="1">
  <summary markdown="span">Low temperature and condensed matter physics</summary>

  * Cryogenic scanning probe microscopy of quantum materials and devices
  * Electromagnetic modeling of superconducting devices
  * Operation of cryogen-free dilution refrigerators
  * Instrument control and measurement automation
</details>

<details markdown="1">
  <summary markdown="span">Quantum computing</summary>

  * Automating the characterization and calibration of superconducting qubits and cavities
  * Modeling dynamics of open quantum systems (QuTiP, [SeQuencing](https://sequencing.readthedocs.io/en/latest/))
  * Dynamical decoupling noise spectroscopy
  * Software and RF electronics for quantum control
</details>

<details markdown="1">
  <summary markdown="span">Scientific programming</summary>

  * Scientific Python (numpy, scipy, matplotlib, pandas, JAX, ...)
  * MATLAB
  * Finite element methods
  * Git and GitHub
  * Interfacing with HPC (Slurm, Bash)
</details>

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
