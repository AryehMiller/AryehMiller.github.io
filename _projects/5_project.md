---
layout: page
title: Systematics and natural history
description: Research on the systematics, taxonomy, and natural history of reptiles and amphibians
img: assets/img/Micryletta.jpg
importance: 3
category: Current research foci
---

As both a natural historian and an evolutionary biologist, I firmly believe that studying the evolution and ecology of particular organismal groups, and developing an appreciation for their biology, is essential to formulating, understanding, and advancing broader concepts in biology. As a herpetologist, classifying and evaluating the relationships among reptiles and amphibians has long remained a central aspect of my research efforts. To do so, I combine genetic and phenotypic data in an integrative framework to estimate phylogenetic relationships among extant taxa to understand their evolution. Most often, this work involves re-evauluating the evolutionary relationships among species, and sometimes, it involves describing entirely new species to science. 

The research occurs in the field (deep in the tropical rainforests of Southeast Asia or on remote Caribbean islands), in natural history museum collections where specimens are houses, in state-of-the-art molecular labs where genomic material is extracted and sequenced, and on high-performance computing clusters to execute powerful, data-intensive analyses. 

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
    
Relevant publications:

1. Miller, A. H., & Zug, G. R. (2016). An enigmatic _Lygosoma_ (Reptilia: Squamata: Scincidae) from northern Myanmar. _Herpetological Review_, 47(3), 373-374.
    
2. Miller, A. H., & Zug, G. R. (2016). Morphology and biology of the Asian Common Mockviper, _Psammodynastes_ _pulverulentus_ (Boie, 1827)(Serpentes: Lamprophiidae): a focus on Burmese populations. _Proceedings of the Biological Society of Washington_, 129(1), 173-194.
    
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
{% endraw %}
