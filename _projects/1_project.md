---
layout: page
title: Intrinsically Ductile Refractory Alloy Development
description: PhD Thesis
img: assets/img/1_project/thumbnail.jpg
importance: 1
category: work
---

Developing ductile refractory alloys has remained a challenge due to various design parameters put forth by different researchers to understand the intrinsic ductility of BCC alloys. Here I am focusing on the intrinsic ductility parameter (D) to develop concentrated refractory alloys.

The D is defined as,
<p>$$ D = \frac{\gamma_s}{\gamma_{usfe}} $$</p>
where, $$\gamma_s$$ is surface energy and $$\gamma_{usfe}$$ is unstable stacking fault energy. Under the framework of <a href="https://en.wikipedia.org/wiki/Density_functional_theory">Density Functional Theory (DFT)</a>, the $$\gamma_s$$ is defined as,
<p>$$ \gamma_s = \frac{E_{pristine}-E_{pristine+vac}}{Area\ of\ surface} $$</p>
Here, the $$E_{pristine}$$ is the energy of the pristine supercell without any surface and $$E_{pristine+vac}$$ is the supercell having surface, i.e. the same pristine supercell is exposed to vacuum of suitable A (generally a vacuum of $$\geq7A$$ should suffice). The $$\gamma_{usfe}$$ is defines as,
<p>$$ 	\gamma_{usfe} = \frac{E_{faulted}-E_{pristine}}{(Area\ of\ Plane)} $$</p>
Here, the $$E_{faulted}$$ is the energy of supercell having a stacking fault and the $$E_{pristine}$$ is the energy of pristine supercell. The {110}<111> slip system of BCC metals/alloys has the lowest energy barrier for activation. Therefore, we have chosen the same slip system in present study.
	
<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/1_project/shearingVideo.mov" title="Shearing video" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/1_project/shearingRelaxation.mov" title="Shearing relaxation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    First half of the supercell being shearing with respect to the bottom half. Relaxation happening at the unstable stacking fault.
</div>

Accurate calculation of D requires an accurate estimate of $$\gamma_s$$ and $$\gamma_{usfe}$$. Therefore, in my Master's Thesis I developed a <a href="/projects/2_project/">methodology</a> based on DFT framework to accurately calculate the $$\gamma_s$$ and $$\gamma_{usfe}$$ and quantify the errors associated with them.

Based on the above methodology our goal is to optimally reduce the number of alloys studied as we move from binaries to ternaries to higher-order alloy systems, as depicted in the figure below.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/1_project/funnel.jpg" title="funnel" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The alloy development funnel drastically reduces the number of systems to be studied.
</div>

The alloy development funnel ensures that the compositional explosion does not take place as we move from binaries to ternaries to higher-order alloy systems. What criteria to be selected to filter out alloy candidates is an integral part of my PhD dissertation. Every stage in the above funnel reduces the number of alloys to be studied based on specific property expectations criteria.

This is ongoing work; hence this page will be updated periodically.
