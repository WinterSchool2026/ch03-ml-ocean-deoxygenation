# Is the Mediterranean Sea losing its breath?
## Description
The ocean plays a fundamental role in regulating Earth’s climate, and it has absorbed ~90% of the excess heat and ~25% of the CO2 emissions generated from human activities. However, this climate service has caused severe threats to the health of marine ecosystems, including ocean warming, acidification, and deoxygenation, which have both environmental and socioeconomical consequences. Therefore, it is crucial to ensure that the state of the ocean is properly monitored and changes are detected promptly. 

In this challenge, you are tasked with filling the observational gaps of dissolved O2 concentrations in the Mediterranean Sea between 2012 and 2023 by developing a gridded product at monthly resolution and assessing the changes in O2 concentration over time. For practical reasons, we are only looking at 12 years of data, so no long-time trend can be detected. However, we can have some indications of fluctuation over time and can use this as a strating point for any future assessment. In situ measurements of O2 will be provided from the BGC-Argo+ dataset, currently being developed by the [HI-Cycles group](https://bushinskyoceanlab.org/) at the University of Hawai'i at Mānoa. 

This challenge can possibly be extended beyond the duration of this winter school.

## Jump in the notebook

All experiments are designed to run using **Google Colab**.

Click the badge below to launch the baseline notebook directly in Google Colab: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Iwo4rDZ3-wYxjzKiemVULqNOIJwu9LXY?usp=sharing)

## Understanding the problem
[Here](https://github.com/WinterSchool2026/ch03-ml-ocean-deoxygenation/slides/Intro_presentation.pdf) is a presentation to introduce you to the challenge.


## Useful reading material

[Mapping Dissolved Oxygen Concentrations by Combining Shipboard and Argo Observations Using Machine Learning Algorithms](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024JH000272) by Ito et al. (2024).

[Acidification, deoxygenation, and nutrient and biomass declines in a warming Mediterranean Sea](https://bg.copernicus.org/articles/19/4035/2022/) by Reale et al. (2022).

Potential additional data: [A consistent regional dataset of dissolved oxygen in the western Mediterranean Sea (2004–2023): CTD-O2WMED](https://essd.copernicus.org/articles/17/5315/2025/essd-17-5315-2025.html) 

---

## Challenge Objectives

You are free to explore the data and investigate any questions that you might find interesting, but please check its feasibility with me before getting started to make sure you have enough time to complete your challenge in the prescribed time. Here are some suggested topics for you to delve on:

- What are the effects of mapping at higher spatial resolution? 
- What would happen by adding more observations or reducing the number we currently have? How can this inform future sampling strategies?
- How can uncertainty be quantified and included in the final product that you deliver?
- What is the impact of marine heatwaves on O2 concentrations? 
