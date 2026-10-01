---
layout: page
permalink: /research/
title: research
description: Computational electromagnetism, transformation optics and resonances of open photonic structures.
nav: true
nav_order: 2
---

<div class="row justify-content-center mt-3 mb-2">
  <div class="col-6 col-md-5 text-center">
    <img src="{{ '/assets/img/cloak-scattering.gif' | relative_url }}" class="img-fluid rounded z-depth-1" alt="A cylindrical wave scattered by a small triangular obstacle" loading="lazy">
  </div>
  <div class="col-6 col-md-5 text-center">
    <img src="{{ '/assets/img/cloak-cloaked.gif' | relative_url }}" class="img-fluid rounded z-depth-1" alt="The same obstacle surrounded by an invisibility cloak: the wave passes undisturbed" loading="lazy">
  </div>
</div>
<div class="caption">
  Left: a cylindrical wave is scattered by a small obstacle. Right: the same obstacle wrapped in a cloak designed by transformation optics — the wave flows around it as if nothing were there. Finite-element simulations shown in my invited talk <em>Masking with Generalized Cloaking</em> (Compumag 2009).
</div>

Early in my career, at the University of Liège, I developed finite-element and boundary-element codes for low-frequency electromagnetic problems in electrical engineering. Joining Institut Fresnel in 2000 let me bring that finite-element expertise into optics, where it was still little used — starting with the modeling of microstructured optical fibers with F. Zolla and S. Guenneau, work that led to the reference book _Foundations of Photonic Crystal Fibres_ (2005, 2nd ed. 2012).

### Transformation optics and invisibility

A differential-geometry background convinced me, as early as 2003, that any coordinate transformation could be encoded as an equivalent material: Maxwell's equations themselves are metric-free, and the metric only enters through the constitutive relations. This is the principle behind _transformation optics_, a few years before it became widely known through John Pendry's invisibility cloak. We were among the first to publish on the topic, in collaboration with Pendry himself, and summarized the idea in a _Science_ perspective, [_Cloaking with Curved Spaces_](https://doi.org/10.1126/science.1168456) (2009).

The same geometric viewpoint unifies many tools: Perfectly Matched Layers (PMLs) are complex-valued coordinate stretchings, helicoidal coordinates turn twisted fibers into two-dimensional problems, and cloaks or negative-index media correspond to puncturing or folding space.

<div class="row justify-content-center mt-3 mb-2">
  <div class="col-10 col-md-7 text-center">
    <img src="{{ '/assets/img/albert-harry.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Hand drawing of Einstein and a young wizard peeking through a hole in a field of bent lines" loading="lazy">
  </div>
</div>
<div class="caption">
  When curved spacetime meets an invisibility cloak — drawing by André Nicolet.
</div>

### Resonances of open, dispersive structures

PMLs let us handle open electromagnetic problems rigorously, including the _modal analysis of lossy, open structures_: leaky modes of waveguides and quasi-normal modes (QNMs) of resonators, which have complex frequencies. Extending this analysis to highly dispersive media, such as metals near plasmonic resonance, leads to nonlinear non-Hermitian eigenvalue problems. In 2018 we obtained a universal formulation of the modal expansion in arbitrary dispersive media, published in _Optics Letters_. This work, supported by the ANR RESONANCE project with Ph. Lalanne and C. Sauvan, continues today within the ATHENA team.

### Open-source tools

Our models are released as free software in [ONELAB Photonics](https://onelab.info/photonics/), built on the ONELAB platform of C. Geuzaine (University of Liège) and the SLEPc eigenvalue library of J. E. Roman (Universitat Politècnica de València). Our test cases have helped improve both.

### New directions

Since 2024, together with E. Chevallier, I have opened a new line of work applying differential-geometry tools to the statistics and processing of optical images, in particular polarization matrices — the subject of Gabriel Trindade's PhD, which I supervise.
