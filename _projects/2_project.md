---
layout: page
title: Methodology Development for Calculating USFE 
description: Masters Thesis
img: assets/img/2_project/thumbnail.jpg
importance: 2
category: work
---

Understanding the role of enthalpy of formation in enhancing the intrinsic ductility of equiatomic binary refractory alloys. Here we found that the enthalpy of formation strongly influences the change in $$\gamma_{usfe}$$ over its composition averaged value.

We studied 36 equiatomic binary refractory alloys and found that the enthalpy of formation should be within -120 meV/Atom to +120 meV/Atom for the alloys to be intrinsically ductile. The large enthalpy of formation requirement should be compensated by a sufficiently large entropy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2_project/workflow.jpg" title="workflow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The workflow developed in this work can be 9x faster than the brute-force calculations.
</div>

Here we select only the equiatomic shearing interface to calculate the $$\gamma_{usfe}$$ and $$\gamma_s$$ of alloys. The equiatomic shearing interface ensures that the values are inline with the the accurate formula chemistry of the alloy. In some of the earlier <a href="https://doi.org/10.1016/j.actamat.2021.116800">works</a>, the $$\gamma_{usfe}$$ was being calculated for all the shearing interfaces present in the supercell. If the supercell had 10 slip planes then the final $$\gamma_{usfe}$$ was the average of 9 different $$\gamma_{usfe}$$ values as given in belowe figure.

<div class="row justify-content-sm-center">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/2_project/shearingInterfaces.jpg" title="Shearing interfaces" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
	The same supercell can give 9 different USFE values depending upon the stoichiometry of that shearing interface.
</div>

Therefore selecting the shearing interface with formula stoichiometry can give the correct $$\gamma_{usfe}$$ 9x faster than the earlier method.

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/2_project/shearings.jpg" title="shearing method" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The same supercell can be sheared in 4 different directions to give 4 different USFE values.
</div>

The shearing interface with correct stoichiometry can be sheared in 4 different directions leading to 4 different $$\gamma_{usfe}$$ values. However, we select the $$\gamma_{usfe}$$ corresponding to the lowest energy difference between pristine and sheared supercell. This ensures that the large change in stoichiometry does not affect our final $$\gamma_{usfe}$$ and $$\gamma_s$$ values. This methodology also helps us quantify the errors associated with the $$\gamma_{usfe}$$ value due to stoichiometry change after shearing.

Here we showed that the widely held notion of reduction in valence electron concentration (VEC), leading to improvement in ductility of refractory alloys may not be applicable everywhere. we found that it is the large decrease in the $$\gamma_{usfe}$$ which is leading to improvement in intrinsic ductility of refractory alloys. This observation is supported by the role of low valency Ti/Zr/Hf as well as high valency Re in improving the ductility of refractory alloys.

I had presented this work at the CALPHAD-2022 conference in Sweden. This work has been <a href="https://doi.org/10.1016/j.jallcom.2022.168597">published</a> in the Journal of Alloys and Compounds.
