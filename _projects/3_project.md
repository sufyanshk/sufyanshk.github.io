---
layout: page
title: Refractory High Entropy Alloys
description: PI - Prof. B. S. Murty (IIT Madras)
img: assets/img/3_project/thumbnail.jpg
importance: 3
category: work
---

This project was sponsored by the United States Air Force Research Laboratory with Prof. B. S. Murty of Indian Institute of Technology Madras as PI. Me and Dr. Lavanya Raman together worked on this project. Dr. Raman led the experimental part of study and I was leading the modeling part.

I studied 126 quaternary and 126 quinary equiatomic refractory high entropy alloys (RHEA), made from Group IV (Ti, Zr, Hf), Group V (V, Nb, Ta) and Group VI (Cr, Mo, W) elements. We used Rule-of-mixtures (ROM) technique to calculate liquidus temperature, density (ρ), Young’s modulus (E), % atomic size difference (δ), valence electron concentration (VEC) and specific heat at constant pressure and at 1273 K (Cp). CALPHAD technique is used (thanks of V. S. Hariharan) to predict the number of phases formed at 298 K, ρ and liquidus temperature.

We found that the ROM calculated densities are matching perfectly with CALPHAD values. Densities and E are directly proportional to the VEC and liquidus temperature of the alloys. Ti, Zr, Hf are ductilizing the alloys and making them light; whereas Cr, Mo and W, are reducing the alloys’ ductility and making them heavy. For quinary RHEAs, Cp showed six distinct groups with δ, but a similar trend was not observed in quaternary RHEA. Here we used scatter matrix methodology to screen a large number of alloys based on various properties.

This work resulted in a <a href="https://doi.org/10.1016/j.intermet.2020.106926">publication</a> in the Intermetallics journal and an <a href="https://apps.dtic.mil/sti/pdfs/AD1170060.pdf">AFRL project report</a>.


Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

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
