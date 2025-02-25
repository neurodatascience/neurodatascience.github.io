---
title: Benchmarking federated learning approaches against siloed and mega-analysis regimes
# subtitle:
status: active
image: img/projects/fl_overview.png
layout: project
people:
  - Michelle
  - Nikhil
---

Although neuroimaging is seeing a growing number of datasets, the international adoption of strong data privacy frameworks ([Marelli & Testa, 2018](https://doi.org/10.1126/science.aar5419)) has led to many of these datasets remaining in so-called “silos”. When data cannot readily be shared, it becomes imperative to develop distributed data processing tools and federated analysis methods to enable large-scale multi-site studies.

In this project, we compare a simple federated analysis setup (i.e. sharing only fitted model parameters) with two traditional experimental setups:

- Siloed analysis (no sharing of data or model parameters)
- Mega-analysis (sharing data)

We evaluate the performance of machine learning (ML) models on several neuroimaging datasets of Parkinson’s (PD) and Alzheimer’s disease (AD) on two common prediction tasks in neurodegenerative diseases: 1) brain age and 2) cognitive decline. We hypothesize that model performance improves as we go from siloed to federated to mega-analysis setups.

<p align="center">
   <img src="/img/projects/fl_setups.jpg" alt="Machine learning setups" width="400">
</p>
