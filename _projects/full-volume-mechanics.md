---
layout: page
title: Full volume mechanics
# description:
img: assets/img/research/fullVolTendon.svg
importance: 1
related_publications: true
---

<a href="{{ '/research/' | relative_url }}"><i class="fa-solid fa-arrow-left"></i> Back to research</a>

I take a holistic approach to studying damage in soft tissues by visualizing their entire architecture and quantifying their deformation with techniques based on medical imaging.

**Advisor: Professor Ellen Arruda**

## Tear growth mechanisms in partial-thickness tears

**In collaboration with orthopaedic surgeon Professor Asheesh Bedi**

To understand how tears grow and move us closer to mechanically informed clinical decisions, I measured strain in torn ovine tendons using MRI. My 3D reconstructions from full volume data showed that tears involving more than 75% of the tendon thickness (type III tears) likely fail due to **delamination**, with **high shear strains** concentrating at the visible and internal cut-uncut interface. This failure type persisted regardless of geometry. While my research elucidated failure mechanisms, further analysis with different types of tears is needed to determine when tears start to grow, and whether a combination of geometry and load exacerbates tear progression.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research/delamination.png" title="Full volume displacements and strains in type III bursal-sided tear" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<!-- <div class="caption">
  Full volume shear strain map around a high-grade bursal-sided partial-thickness tear.
</div> -->

## Articular- vs bursal-sided tears

**In collaboration with orthopaedic surgeon Professor Asheesh Bedi**

Partial-thickness tears can start on the joint (articular) side, the visible (bursal) side, or within the tendon (intratendinous). When more than 50% of the tendon thickness has been compromised, these tears are candidates for clinical intervention, based on anecdotal evidence. However, a high rate of re-tears after repair indicates that more quantitative methods could be used to determine when a repair is clinically indicated. My preliminary data indicate that articular-sided tears of increasing sizes have negligible full volume displacement changes compared to intact tendons, while bursal-sided tears increasingly alter the displacement environment. Even with tears involving 25% of the tendon thickness, bursal-sided tears show visible changes, suggesting that repair decisions might need to account for both tear type and sidedness.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    <p class="text-center font-weight-bold mb-2">Articular-sided tears</p>
    {% include figure.liquid path="assets/img/research/articular.png" title="Full volume displacements in articular-sided tears" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    <p class="text-center font-weight-bold mb-2">Bursal-sided tears</p>
    {% include figure.liquid path="assets/img/research/bursal.png" title="Full volume displacements in bursal-sided tears" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
