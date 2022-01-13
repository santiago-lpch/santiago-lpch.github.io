---
layout: page
title: top quarks and leptons
description: an NLO QCD implementation for POWHEG-BOX
img: assets/img/gg2.png
importance: 1
category: work
---

<div class="container-fluid">
  <div class="row justify-content-center">
    <div class="test-center">
        {% include figure.html path="assets/img/gg2.jpg" title="LO diagram" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>
</div>
<div class="container">
  <div class="caption">
    Exemplary leading-order diagram of the \( pp \to t\bar{t}\ell^+\ell^- \) process.
  </div>
</div>

The top quark, discovered in 1995 at the [Tevatron](https://en.wikipedia.org/wiki/Tevatron), is the heaviest elementary particle we know of. The LHC at CERN has the capacity to produce an unprecedented number of them, allowing experimentalists to collect large amounts of data from processes in which top quarks are involved. To probe the couplings of top quarks to the electroweak $$W$$ and $$Z$$ bosons, people study production processes, such as $$ pp \to t\bar{t}Z $$ and $$ pp \to t\bar{t}W^\pm $$. Such processes are also important backgrounds to the associated production of the Higgs boson with a top quark pair $$(pp \to t\bar{t}H)$$. There have been previous calculations of these processes at NLO QCD precision, where the electroweak bosons have been treated in the narrow-width approximation. The goal of this project was to study the influence on key observables of a more complete description of the $$ pp \to t\bar{t}Z $$ process. We have implementesd the $$ pp \to t\bar{t}\ell^+\ell^- $$ process, which includes both $$Z$$ boson and photon induced contributions. Thus, our calculation includes fully off-shell description of the $$Z$$ boson, which can be compared to the studies of the $$ pp \to t\bar{t}Z $$ process that use the narrow-width approximation by imposing appropriate cuts on the invariant mass of the lepton pair. Furthermore, our implementation supports a handling of the top-quark decays that retains spin correlations. We have shown that these theoretical improvements of our implementation give rise to effects of the order of 10-20% in specific regions of the kinematic distributions of the final state, which are visible after matching to a parton shower and beyond the scale uncertainty due to a seven-point variation of  renormalization and factorization scales.


