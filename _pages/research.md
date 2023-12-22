---
layout: page
permalink: /research/
title: Research
description: >
    My research focuses on modelling flows that are encountered in energy, transportation, environmental and biomedical engineering applications. I am particularly interested in studying cavitation and bubble dynamics as well as wind energy aerodynamics through a combination of numerical simulations, theory, and data-driven techniques.
nav: true
nav_order: 2
---

---
**Bubble dynamics**
Bubbles are fascinating! Even though they are tiny, they can incur significant damage to even the strongest of materials. They can also be used for drug delivery, therapy (tumour ablation, kidney stone fragmentation, tissue regeneration, pain management), cleaning of surfaces, and energy generation, to name a few other applications.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bubble2.png" title="Collapsing bubble" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bubble1.png" title="Shock-impacted bubble array" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Horizontal cut across a bubble collapsing near a solid surface (left). Three-dimensional visualisation of a bubble array following shock impact (right). Simulations were performed with <a href="https://github.com/code-mphi/ECOGEN/">ECOGEN</a> and an in-house version of <a href="https://www.ams.sunysb.edu/~linli/FronTier++_Manual/index.html">FronTier++</a>, respectively.
</div>


---
**Aerodynamics**
I am interested in aerodynamics, specifically in the context of wind energy. This includes studying the wakes and aerodynamic properties of wind turbines and more generally, bluff bodies and rotors. Additionally, I am intrigued by the interactions that occur when these bodies are grouped together or exposed to atmospheric flows.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Wind_Farm.jpg" title="Flow in a wind farm" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Flow within and around a wind farm. Simulation performed with <a href="https://github.com/xcompact3d">Xcompact3d</a> on <a href="https://www.archer2.ac.uk">archer2</a>.
</div>

---
**Methods**
My work relies heavily on computational modelling. I employ and contribute to the development of state-of-the-art solvers that can model a wide range of flows. Below is a list of some of the codes I like:

- [Xcompact3d](https://www.xcompact3d.com) is an [open-source](https://github.com/xcompact3d) high-order finite-difference framework dedicated to the study of turbulent flows. 
- [FronTier++](https://www.ams.sunysb.edu/~linli/FronTier++_Manual/index.html) is a library providing high-resolution tracking for contact discontinuities and internal boundaries via the front tracking method.
- [ECOGEN](https://code-mphi.github.io/ECOGEN/) is an [open-source](https://github.com/code-mphi/ECOGEN/) platform for the simulation of compressible multiphase flows.

Most of the simulations are run on HPC systems, such as [archer2](https://www.archer2.ac.uk), the UK's national supercomputing service. 

Besides computational modelling, I also enjoy working on theoretical and data-driven models.
