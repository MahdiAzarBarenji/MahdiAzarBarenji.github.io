---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---
---

### Master's Thesis
Moving toward a prosperous economy and cleaner climate demands building on existing measures to significantly lower GHG (greenhouse gas) emissions in the long term. Canada, alongside many other countries, is committed to achieving net-zero GHG emissions by <a href="https://www.canada.ca/en/services/environment/weather/climatechange/climate-plan/net-zero-emissions-2050.html" target="_blank" style="color:#0000FF; text-decoration:none;">2050</a>. Several climate plans have been legislated to date. For instance, the <a href="https://publications.gc.ca/collections/collection_2022/eccc/En4-460-2022-eng.pdf" target="_blank" style="color:#0000FF; text-decoration:none;">2030</a> emissions reduction plan outlines that the government will meet its enhanced Paris Agreement target to reduce emissions by 40-45% from 2005 levels by 2030. The importance of renewable and low-carbon gases such as hydrogen and biomethane is undeniable in this regard. According to a recent <a href="https://www.cdn.fortisbc.com/libraries/docs/default-source/news-events/bc-renewable-and-low-carbon-gas-supply-potential-study-2022-03-11.pdf" target="_blank" style="color:#0000FF; text-decoration:none;">joint study</a> in British Columbia (B.C.), replacing conventional natural gas with made-in-B.C. renewable and low-carbon gases plays a crucial role in achieving <a href="https://www2.gov.bc.ca/assets/gov/environment/climate-change/action/cleanbc/cleanbc_roadmap_2030.pdf" target="_blank" style="color:#0000FF; text-decoration:none;">CleanBC</a> targets for efficient and affordable decarbonization of the existing infrastructures.

The most cost-effective, efficient solution during the current transition period toward a green hydrogen ecomomy is using the existing gas infrastructure, in which the two gaseous substances are transported as one mixture called H2NG. Due to the different thermophysical properties of hydrogen and natural gas (for simplification, it will be denoted as methane), the mixture changes significantly in its transmission conditions. These changes also vary with the high-pressure, intermediate-pressure, and low-pressure networks. An in-depth understanding of the process feasibility, associated hazards and risks, and safety measures is crucial. That is to say, the high contents of hydrogen could give rise to multiple issues including but not limited to material durability, grid integrity, safety, leakage, and the necessity of modifying or altering pipelines, storage tanks, compressors, or even end-user devices.

Given this, renewable hydrogen delivery within the existing grids to reduce GHG emissions is carried out in this research. The main focus of this study is on the mixing of hydrogen and methane gases in the existing pipelines. Due to buoyancy effects and a significant density difference of eight times compared to methane, hydrogen tends to get confined near the top wall or the bottom upon its injection. The confinement zone, top or bottom, depends on how the hydrogen gets introduced to the main pipe. The first part of this study tackles the issue of how we can prevent stratified hydrogen in the pipeline to stop steel embrittlement and potential leakage. This entails immediately having a uniform mixture of two fluids in the line. Accordingly, a multi-species numerical approach using ideal and real gas equations of state (EoS) such Soave-Redlich-Kwong (SRK) and mixing/combining rules for the species is conducted. For the sake of High-Performance Computation (HPC), UBC Advanced Research Computing (UBC ARC) and ComputeCanada platforms are used. ANSYS Fluent, Fluent Meshing, and Tecplot are used for the numerical simulation, pre-processing, and post-processing stages. The multi-species codes are developed and compiled separately into the ANSYS Fluent via C/C++ (<a href="https://github.com/arashjkh/Directed-Studies-UBC-course" target="_blank" style="color:#0000FF; text-decoration:none;">sample</a>). The impacts of using static mixers and injection from different angles are studied. Furthermore, the model is expanded to high-pressure cases, which entails using real gas EoS. The diffusion, advection, and buoyancy effects on the possible stratification of gases are also studied. Below, the difference between the upper-side injection and the bottom-side injection can be observed. It is shown that the bottom-side injection results in a lower mixing uniformity length.

Top-side injection:

<p align='center'>
<iframe width="560" height="315" src="https://www.youtube.com/embed/JXl90S2QzLI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

<p align='center'>
<iframe width="560" height="315" src="https://www.youtube.com/embed/B40OWxpehKQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

Bottom-side injection:

<p align='center'>
<iframe width="560" height="315" src="https://www.youtube.com/embed/f77y9xpKKzk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

<p align='center'>
<iframe width="560" height="315" src="https://www.youtube.com/embed/VjRtbvW7s-Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

---

### Bachelor's Thesis
Comparing the efficiency of Kalina cycle system 11 (KCS11) and Kalina cycle system 111 (KCS111) based on different decision variables. The results were compared with some benchmarks in the literature. From a thermodynamics perspective, and apart from KCS111's complex configuration and high costs, it is more efficient than the base cycle, KCS11 (<a href="https://github.com/arashjkh/Thermodynamic-and-exergy-analysis-of-KCS11-and-two-other-types-with-three-pressure-levels-BSc-Thesis" target="_blank" style="color:#0000FF; text-decoration:none;">more + codes</a>).


