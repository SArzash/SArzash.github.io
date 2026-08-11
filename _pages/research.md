---
layout: page
title: research
permalink: /research/
# description: Research interests.
nav: true
nav_order: 2
---

How does a collection of living cells organize itself into a specific, **functional shape**, and do so **robustly**, despite noise, variability, and damage? To me, the emergence of such precise and reliable forms from many locally interacting agents is one of the most remarkable phenomena in nature, and uncovering its physical basis drives my research.

I work at the interface of soft matter physics, biological physics, and machine learning. Using theory and computation, I study complex, disordered systems, from biopolymer networks to living tissues, through the lens of **learning**: I ask how systems with many internal degrees of freedom can store a memory of the forces they experience, tune their own mechanical properties, and be trained toward targeted functions. By borrowing ideas such as **optimization**, **overparameterization**, and **memory** from machine learning, I aim to build a physical theory of how living matter learns and adapts, and to turn that theory into the design of new materials that program their own behavior, connecting fundamental physics with **engineering**.

Biopolymer networks such as collagen are constantly under external and internal stresses, and a hallmark of their response is that they become stronger as they are deformed. These subisostatic fiber networks undergo a **mechanical phase transition** from a soft to a rigid state under strain. My PhD work helped establish that this transition is **critical** in nature, with universal signatures that persist from two to three dimensions and up to finite temperature, providing a predictive theory for real biopolymer materials.

On the multicellular scale, the mechanics of tissues can be captured by a transition between **solid-like and fluid-like** states set by cell geometry and motility. Deciphering these collective cell behaviors is central to embryonic development, cancer progression, and wound healing.

In my recent work, I treat internal variables such as cell shape factors or junctional tensions as **tunable degrees of freedom**, and show how tissues can adapt their own rigidity, store a memory of past forces, and be trained toward target functions. These results connect the physics of tunable matter with optimization and machine learning, and open a path toward materials whose mechanical response can be trained rather than fixed by design.

<div class="research-gallery">
  <figure>
    <video autoplay loop muted playsinline aria-label="Convergent extension driven by a local active edge tension rule in a vertex model">
      <source src="/assets/img/ce_local.mp4" type="video/mp4">
    </video>
    <figcaption>A local rule on active edge tensions in a vertex model drives convergent extension, the coordinated tissue elongation that shapes the body plan during development. Here each edge tension is tuned locally from the edge's own orientation and length, and this simple rule alone generates a convergent extensional flow. Viewing morphogenesis through the framework of tunable matter lets us uncover the simple local rules that biology uses to accomplish specific tasks. See more in <a href="https://www.biorxiv.org/content/10.1101/2025.11.06.687029v1">Epithelial convergent extension as a tuning process</a>.</figcaption>
  </figure>
  <figure>
    <video autoplay loop muted playsinline aria-label="Vertex model tissue melting from solid to fluid">
      <source src="/assets/img/vertex.mp4" type="video/mp4">
    </video>
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
    <video autoplay loop muted playsinline aria-label="Local contractile pulses reprogramming tissue rheology">
      <source src="/assets/img/movie_pulsatile_contraction.mp4" type="video/mp4">
    </video>
    <figcaption>Local active contractile pulses applied to a small region reprogram the rheology of the entire tissue. The global shear modulus increases and, unlike ordinary strain stiffening, the change persists after the pulses stop. The tissue keeps a mechanical memory of past cues, learning its elasticity from local rules. See more in <a href="https://www.biorxiv.org/content/10.64898/2025.12.17.694921v1">Learning Epithelial Elasticity via Local Tension Remodeling</a>.</figcaption>
  </figure>
  <figure>
    <video autoplay loop muted playsinline aria-label="Active deformable particle model">
      <source src="/assets/img/active_dp.mp4" type="video/mp4">
    </video>
    <figcaption>Deformable particle models are a versatile playground for soft matter, spanning granular media, cells, and tissues. Beyond the usual interactions, each particle carries an extra tunable degree of freedom, its deformability, which lets these models capture tissues with gaps and the rheology of deformable particulate matter, with promise for designing novel materials. Shown here is an active deformable particle model.</figcaption>
  </figure>
  <figure>
    <video autoplay loop muted playsinline aria-label="Construction and dilution of a Mikado fiber network">
      <source src="/assets/img/mikado.mp4" type="video/mp4">
    </video>
    <figcaption>A Mikado network, named after the pick-up sticks game, is built by randomly dropping monodisperse fibers into a box and crosslinking them wherever they cross. As more fibers are added the network becomes isotropic, and we then dilute it to a target connectivity to mimic real fibrous materials such as collagen. The left panel tracks the average connectivity z during deposition and dilution, and the right panel shows the evolving distribution of fiber segment lengths. See more in <a href="https://doi.org/10.1039/D0SM00764A">Finite size effects in critical fiber networks</a>.</figcaption>
  </figure>
  <figure>
    <video autoplay loop muted playsinline aria-label="Packing-derived three-dimensional fiber network under simple shear">
      <source src="/assets/img/pd3d_shear.mp4" type="video/mp4">
    </video>
    <figcaption>To model fibrous materials in three dimensions, I build packing-derived networks: starting from a jammed packing of bidisperse spheres and extracting its contact network, whose connectivity sits near the isostatic value of 6. Randomly trimming bonds brings the network below this threshold, and applying simple shear reveals its rheology. As shown here, the shear modulus rises by orders of magnitude with strain, reproducing the strain stiffening seen in biopolymer networks. See more in <a href="https://doi.org/10.1103/PhysRevE.104.L022402">Shear-induced phase transition and critical exponents in three-dimensional fiber networks</a>.</figcaption>
  </figure>
  <figure>
    <img src="/assets/img/TriangularNetworkUnderShear.gif" alt="Diluted fiber network sheared through its mechanical critical point">
    <figcaption>A subisostatic fiber network (connectivity z = 3.3) sheared past its mechanical critical point. Initially floppy, the network rigidifies at a sharp critical strain, where forces concentrate along the paths that carry the load (color shows bond tension). These critical signatures explain the strain stiffening of collagen and other biopolymer gels. See more in <a href="https://doi.org/10.1039/D0SM00764A">Finite size effects in critical fiber networks</a>.</figcaption>
  </figure>
  <figure>
    <video autoplay loop muted playsinline aria-label="Fiber network rigidified by thermal fluctuations">
      <source src="/assets/img/movie_mc.mp4" type="video/mp4">
    </video>
    <figcaption>Below the isostatic threshold, disordered fiber networks are mechanically unstable, yet biological gels remain rigid. Here I show that thermal fluctuations alone can stabilize such networks, a mechanism distinct from classical entropic elasticity. See more in <a href="https://doi.org/10.1103/PhysRevE.108.054403">Mechanical criticality of fiber networks at a finite temperature</a>.</figcaption>
  </figure>
</div>
