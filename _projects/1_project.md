---
layout: page
title: The Evolution of Key Innovations
description: Research on the evolution of organismal features that facilitate major ecological shifts
img: assets/img/12.jpg
importance: 1
category: Current research foci

---

Key innovation are novel organismal features that facilitate major ecological shifts. For example, the evolution of wings in birds enabled
access to entirely new suite of ecological resources. My research on key innovations aims to synthesize the initial ecological origins
of the concept--understanding how the role of form and function in ecology--with more recent advances in phylogenetic comparative biology
to integratively meld both evolution and ecology. 

The first portion of research describes a novel conceptual and empirical comparative framework for understanding how key innovations arise,
and inferring the eco-evolutionary dynamics of these traits through time. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MHS_01241.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MHS_01672_ArborealLizardMyanmar.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MHS_02540.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Arboreal lizards come in all shapes and sizes. On the left, a flying lizard (genus Draco) with an expanded rib cage to allow the species to "glide." Middle, an arboreal lizard with long, sharp curved claws to dig into trunks. Right, a gecko without toepads-- the bent-toed geckos, which have evolved arboreality.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure2_26May21.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Arboreality in lizards has evolved more than 100 times, but lineages possessing digital adhesive toepads
    have a distinct, remarkable evolutionary dynamic through time of ecological conservatism.
</div>r2

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
{% endraw %}
