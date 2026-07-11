---
layout: page
title: research
permalink: /research/
# description: Research interests.
nav: true
nav_order: 2
---

My research sits at the interface of soft matter physics, biological physics, and machine learning. I study the mechanical and dynamic properties of soft and living materials, from biopolymer networks to whole tissues, using computational models and theoretical frameworks to identify the important parameters that govern these complex systems.

Biopolymer networks such as collagen are constantly under external and internal stresses, and a hallmark of their response is that they become stronger as they are deformed. These subisostatic fiber networks undergo a mechanical phase transition from a soft to a rigid state under strain. My PhD work helped establish that this transition is critical in nature, with universal signatures that persist from two to three dimensions and up to finite temperature, providing a predictive theory for real biopolymer materials.

On the multicellular scale, the mechanics of tissues can be captured by a transition between solid-like and fluid-like states set by cell geometry and motility. Deciphering these collective cell behaviors is central to embryonic development, cancer progression, and wound healing.

Most recently, I have been asking how soft and living systems can learn. By treating internal variables such as cell shape factors or junctional tensions as tunable degrees of freedom, tissues and networks can adapt their own rigidity, store a memory of past forces, and be trained toward target functions. This perspective connects the physics of tunable matter with optimization and machine learning, and points toward designing novel materials that program their own mechanical response.

<div class="research-gallery">
  <figure>
    <img src="/assets/img/TriangularNetworkUnderShear.gif" alt="Diluted fiber network sheared through its mechanical critical point">
    <figcaption>A subisostatic fiber network (connectivity z = 3.3) sheared past its mechanical critical point. Initially floppy, the network rigidifies at a sharp critical strain, where forces concentrate along the paths that carry the load (color shows bond tension). These critical signatures explain the strain stiffening of collagen and other biopolymer gels. See more in <a href="https://doi.org/10.1039/D0SM00764A">Finite size effects in critical fiber networks</a>.</figcaption>
  </figure>
  <figure>
    <img src="/assets/img/movie_mc.gif" alt="Fiber network rigidified by thermal fluctuations">
    <figcaption>Below the isostatic threshold, disordered fiber networks are mechanically unstable, yet biological gels remain rigid. Here I show that thermal fluctuations alone can stabilize such networks, a mechanism distinct from classical entropic elasticity. See more in <a href="https://doi.org/10.1103/PhysRevE.108.054403">Mechanical criticality of fiber networks at a finite temperature</a>.</figcaption>
  </figure>
  <figure>
    <img src="/assets/img/vertex.gif" alt="Vertex model tissue melting from solid to fluid">
    <figcaption>In a vertex model of confluent tissue, cell shape sets the mechanics. As the target shape index increases, junctional tensions relax (red, with thickness proportional to tension) and the tissue transitions from a solid to a fluid. This geometric rigidity transition governs how epithelia flow during development and disease. See more in <a href="https://doi.org/10.1103/9ktk-6rqc">Universality in the Mechanical Behavior of Vertex Models for Biological Tissues</a>.</figcaption>
  </figure>
  <figure>
    <img src="/assets/img/energy_barrier.gif" alt="Energy barrier of a T1 cell rearrangement">
    <figcaption>Tissues remodel through T1 transitions, in which four cells swap neighbors. The energy barrier to a T1 event stays finite in the solid state and vanishes as the tissue fluidizes, setting the rate of cell rearrangement in morphogenesis and wound healing. See more in <a href="https://doi.org/10.1038/s41567-026-03311-6">A minimal in vitro assay for cell intercalation</a>.</figcaption>
  </figure>
  <figure>
    <img src="/assets/img/movie_G_learning.gif" alt="Tissue tuning its own rigidity through target shape factors">
    <figcaption>Tissues can fluidize themselves by adaptively tuning their target shape factors. Treating these shape factors as tunable degrees of freedom lets a tissue shift its own rigidity transition, a concrete route for living matter to program its mechanics. See more in <a href="https://doi.org/10.1103/PhysRevResearch.7.013157">Rigidity of epithelial tissues as a double optimization problem</a>.</figcaption>
  </figure>
  <figure>
    <img src="/assets/img/movie_pulsatile_contraction.gif" alt="Local contractile pulses reprogramming tissue rheology">
    <figcaption>Local active contractile pulses applied to a small region reprogram the rheology of the entire tissue. The global shear modulus increases and, unlike ordinary strain stiffening, the change persists after the pulses stop. The tissue keeps a mechanical memory of past cues, learning its elasticity from local rules. See more in <a href="https://www.biorxiv.org/content/10.64898/2025.12.17.694921v1">Learning Epithelial Elasticity via Local Tension Remodeling</a>.</figcaption>
  </figure>
</div>
