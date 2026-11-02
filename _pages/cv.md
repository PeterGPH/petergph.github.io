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
======
* Ph.D. in Physical Chemistry, University of Illinois Urbana-Champaign, 2028 (expected)
* B.S. in Chemistry, University of Liverpool, 2022
* Applied Chemistry (first two years), Xi'an Jiaotong-Liverpool University, 2018-2020

Research experience
======
* June 2025 - Present: Graduate Research Assistant
  * University of Illinois Urbana-Champaign, Aksimentiev Group
  * Physics-based and machine-learned models of nanopore sensing
  * PoreExplorer Toolkit (PETK): finite-element steric exclusion model for ionic current and conductance blockade
  * Ion-Pot and Ion-Curr: deep-learning surrogates for biomolecular electrostatics and nanopore current
  * ChatVMD: agentic assistant for molecular visualization and analysis inside VMD

* Aug. 2022 - June 2025: Graduate Research Assistant
  * University of Illinois Urbana-Champaign, Hirata Group
  * Finite-temperature mean-field theory and many-body perturbation theory
  * Supervisor: Prof. So Hirata

* Fall 2022 - Spring 2023: Teaching Assistant
  * University of Illinois Urbana-Champaign
  * CHEM 442 (Prof. David Woon) and CHEM 440 (Prof. Martin Gruebele)

Skills
======
* Programming: Python, Fortran, Tcl, MATLAB, Bash, Swift/SwiftUI
* Machine learning: PyTorch, TensorFlow, scikit-learn, NumPy, SciPy, pandas; 3D CNNs, U-Nets, ResNets, pretrained protein embeddings, LLM and agent workflows
* Scientific computing: DOLFINx/FEniCS, PETSc, APBS, VMD, finite-element methods, PDE solvers, numerical linear algebra
* HPC and systems: GPU computing, MPI, OpenMP, Linux, Slurm, AWS, Git, mixed-precision workflows
* Chemistry and physics: quantum chemistry, electronic structure, statistical mechanics, biomolecular electrostatics, nanopore sensing, molecular simulation

Awards
======
* James R. Beck Chemistry Fellowship, University of Illinois Urbana-Champaign
* Silver Medal, Kaggle CAFA 6 Protein Function Prediction, 2026
* Griffith-McKeown Prize, University of Liverpool
* Edith Kearton Prize, University of Liverpool
* Academic Excellence Award, Xi'an Jiaotong-Liverpool University

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service
======
* Reviewer, The Journal of Chemical Physics
