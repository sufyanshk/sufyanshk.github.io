---
layout: page
title: Refractory binary alloy development.
description: Masters Thesis
img: assets/img/2_project/thumbnail.jpg
importance: 2
category: work
---

Understanding the role of enthalpy of formation in enhancing the intrinsic ductility of equiatomic binary refractory alloys. Here I found that the enthalpy of formation strongly influences the change in γ_usfe over its composition averaged value.

I studied 36 equiatomic binary refractory alloys and found that the enthalpy of formation should be within -120 meV/Atom to +120 meV/Atom for the alloys to be intrinsically ductile. The large enthalpy of formation requirement should be compensated by a sufficiently large entropy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2_project/workflow.jpg" title="workflow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The workflow developed in this work can be 9x faster than the brute-force calculation of γ_usfe using DFT.
</div>

Here we showed that the widely held notion of reduction in valence electron concentration (VEC), leading to improvement in ductility of refractory alloys may not be applicable everywhere. I found that it is the large decrease in the γ_usfe which is leading to improvement in intrinsic ductility of refractory alloys. This observation is supported by the role of low valency Ti/Zr/Hf as well as high valency Re in improving the ductility of refractory alloys.

I had presented this work at the CALPHAD-2022 conference in Sweden. This work has been <a href="https://doi.org/10.1016/j.jallcom.2022.168597">published</a> in the Journal of Alloys and Compounds.





To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

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


You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


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
