---
layout: page
title: top quarks and leptons
description: an NLO QCD implementation for POWHEG-BOX
img: assets/img/gg2.png
importance: 1
category: work
---

<div class="container">
  <div class="row justify-content-md-center">
    <div class="col">
        {% include figure.html path="assets/img/gg2.png" title="LO diagram" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>
  <div class="caption">
    Exemplary leading-order diagram of the \( pp \to t\bar{t}\ell^+\ell^- \) process.
  </div>
</div>

The top quark, discovered in 1995 at the [Tevatron](https://en.wikipedia.org/wiki/Tevatron), is the heaviest elementary particle we know of. The LHC at CERN has the capacity to produce an unprecedented number of them, allowing experimentalists to collect large amounts of data from processes in which top quarks are involved. To probe the couplings of top quarks to the electroweak $$W$$ and $$Z$$ bosons, people study production processes, such as $$ pp \to t\bar{t}Z $$ and $$ pp \to t\bar{t}W^\pm $$. Such processes are also important backgrounds to the associated production of the Higgs boson with a top quark pair $$(pp \to t\bar{t}H)$$. There have been previous calculations of these processes at NLO QCD precision, where the electroweak bosons have been treated in the narrow-width approximation. The goal of this project was to study the influence on key observables of a more complete description of the $$ pp \to t\bar{t}Z $$ process. We have implementesd the $$ pp \to t\bar{t}\ell^+\ell^- $$ process, which includes both $$Z$$ boson and photon induced contributions. Thus, our calculation includes fully off-shell description of the $$Z$$ boson, which can be compared to the studies of the $$ pp \to t\bar{t}Z $$ process that use the narrow-width approximation by imposing appropriate cuts on the invariant mass of the lepton pair. Furthermore, our implementation supports a handling of the top-quark decays that retains spin correlations. We have shown that these theoretical improvements of our implementation give rise to effects of the order of 10-20% in specific regions of the kinematic distributions of the final state, which are visible after matching to a parton shower and beyond the scale uncertainty due to a seven-point variation of  renormalization and factorization scales.


<!--
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %} -->
