---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Bachelor's Thesis
Kalina cycle system (KCS) is a modified Rankine cycle proposed by Alexander Kalina, which operates with water-ammonia solution instead of pure water. The new mixture's boiling point and temperature change differ from a pure fluid. Apart from being a toxic gas, it is well-established that Ammonia can be integrated into the water without applying any modifications to the cycle. Furthermore, since Ammonia has a lower boiling point than water, the new mixture could take advantage of the temperature difference between the source and sink. Due to this exciting characteristic in capturing the low-temperature heat source's power, the Kalina cycle system can be used in parallel with geothermal sources, solar cells, or even reusing industrial waste heat, e.g., cement kilns.

In this research, the efficiency of Kalina cycle system 11 (KCS11) and Kalina cycle system 111 (KCS111) based on different decision variables were studied. The results were compared with some benchmarks in the literature. From a thermodynamics perspective, and apart from KCS111's complex configuration and high costs, it is more efficient than the base cycle, KCS11.

The inlet fluid is supposed to be at three different temperature levels, very low, low, and intermediate. The decision variables are pressure levels, mass flow rate, and ammonia concentration. Exergy and thermal efficiency are taken as the objective function, and the novel double pressure Kalina cycle and the base Kalina cycle are compared. Results show that the Kalina cycle system named 111 is much more efficient than the base cycle, KCS11. It is also demonstrated that raising the heat source temperature increases the exergy efficiency of the base cycle, KCS11, while the new cycle's exergy efficiency, KCS111a, remains nearly the same. Engineering Equation Solver (EES) has been used to develop the codes. [(EES codes)](https://github.com/arashjkh/Thermodynamic-and-exergy-analysis-of-KCS11-and-two-other-types-with-three-pressure-levels-BSc-Thesis)

## Master's Thesis
Hydrogen’s abundance on earth and its great potential to reduce the greenhouse gas (GHG) emission renders it an interesting topic for researchers to investigate further. Hydrogen can be used for storing surplus electricity from the grid during periods of low demand for electrical energy. It can also be used to carry the electrical energy generated from renewable energy sources such as solar and wind farms that are not connected to the grid. For these applications, electrical power is consumed to generate hydrogen through electrolyzers. That is to say, the electrical energy is converted to hydrogen as a gaseous substance, which is referred to as the power-to-gas (P2G) technology. As a result, hydrogen is used as a green energy carrier due to its zero emissions.

Hydrogen generated from these power-to-gas applications has to be transported to the end-users. The most cost-effective hydrogen delivery solution is to use the existing gas network by injecting hydrogen into methane, in which the two gaseous substances are transmitted as a mixture. Due to the different thermodynamic properties of the two gases, the new mixture has significant changes in the delivery network as compared to pure gas transmission. These changes are associated with pressure drop and temperature profiles along the operating line. The changes also vary with the high-pressure, medium-pressure, and low-pressure grids. Overall, hydrogen-enriched-methane has beneficial influence on the conditions of its transmission. However, the molar fraction of hydrogen in the mixture should not exceed 15%–20% due to the drop-in heating value. Differences between transporting hydrogen-enriched-methane and pure methane also take place at compression and decompression stations.

The integration of generated green hydrogen from solar cells and wind farms into the existing grids from CFD and thermodynamics insight is studied in this research. It is expected that this approach will lower GHG emissions considerably. A multi-species approach through different equations of state (EoS) and mixing/combining rules is conducted. For the purpose of numerical simulation, ANSYS Fluent is used, and the multi-species codes are developed and compiled separately in C/C++.


