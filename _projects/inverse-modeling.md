---
layout: page
title: Computational modeling
# description: Inferring material behavior and mechanics from rich experimental data.
img: assets/img/research/inverseModeling.png
importance: 2
related_publications: false
---

<a href="{{ '/research/' | relative_url }}"><i class="fa-solid fa-arrow-left"></i> Back to research</a>

My work combines experiments, nonlinear mechanics, and computation to build models that stay interpretable and grounded in physics.

**Advisor: Professor Ellen Arruda**

## Constitutive inference using full volume information

**In collaboration with Professor Krishna Garikipati and Professor Siddhartha Srivastava**

Traditional constitutive models use predefined, fixed forms that limit the range of deformation mechanisms that can be represented. In tendons, this is particularly concerning, as they possess nonlinear behavior and an intricate architecture. In addition, surface data is employed in calibration, leaving internal behavior unvalidated. Using full volume displacement data, which activate multiple deformation components, I inferred constitutive behavior in intact and torn ovine tendons. I adapted a variational formulation framework with multiple candidate terms to identify parsimonious models from these full volume data. In all tendons analyzed, five-term exponential models were able to reproduce important internal behavior, including delamination in torn tendons, to a certain degree. More importantly, simple three-term models gave similar results, emphasizing the importance of using full volume data to identify key constitutive terms. This inference framework applies broadly to other biological soft tissues.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research/fullVolInference.png" title="Three different models showing degree of agreement compared to experimental results" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>

## Fractional solitons in nonlinear twisted ribbons

**In collaboration with Professor Xiaoming Mao**

Topological solitons are localized, stable transition waves that can carry mechanical signals through a structure. We studied how the speed of propagation changed in **fractional topological solitons** when they traveled along **nonlinear viscoelastic twisted ribbons**. Initially, theoretical predictions of speed were three orders of magnitude above experimental measurements. Using finite element simulations, I found that ribbon thickness, material viscoelasticity, and axial bending contributed to slowing down the speed of the soliton along the ribbon, ultimately reconciling apparent theoretical-experimental discrepancies. Importantly, finite element simulations with decreasing thickness approximated mathematical simulations. This work was featured on the cover of _Extreme Mechanics Letters_.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research/solitonThickness.jpg" title="Soliton traveling along ribbons with different thicknesses" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>

## Metatarsal fusion in bipedal jerboas

**In collaboration with Professor Talia Moore**

There are a variety of jerboa species, each of which has evolved different traits to adapt to its environment. In this project, we were interested in determining whether fused, partially fused, or unfused metatarsals would give an evolutionary advantage for rapid bipedal jumping. To do this, I created dynamic finite element simulations of jerboa metatarsals, reconstructed from μCT scans, impacting a solid plate, representing a jerboa landing on a solid substrate. A smaller body size alone did not protect unfused bones: the smallest jerboa, which has unfused metatarsals, developed the highest stresses. In contrast, when all bones were scaled to the same size and loading conditions, **fused metatarsals consistently developed lower stresses than unfused ones**, with partially fused metatarsals performing best. These results suggest that metatarsal fusion reinforced the foot against the high ground reaction forces of bipedal hopping, releasing the constraint on body size and allowing later jerboas to evolve much larger bodies.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research/jerboaBones.png" title="Jerboa bones impacting substrate" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
