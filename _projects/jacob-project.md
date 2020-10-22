---
title: Continuous testing of neuroimaging results across pipelines and datasets
subtitle: Application to hearing loss associations with brain structure
status: active
layout: project
people:
  - Jacob
---

Given the ongoing reproducibility crisis in Neuroimaging, the goal of this project is to evaluate the variability of results across a range of processing pipelines and datasets. The use case to demonstrate the functionality of the project is hearing loss associations with brain structure.

In order to achieve this goal, a computational platform must be constructed that is able to iteratively evaluate and update associations between the hippocampal volume and hearing loss as new data and pipelines or processing conditions are added, meeting the following specifications:

-Dynamically updated computation of results across 2 axes: datasets and processing pipelines.

-Continuous Integration across the 2 aforementioned axes.

-Transparent computation: Public tracking of the exact steps taken to produce each result.

-Publicly accessible and dynamically updated visualizations and statistical summaries of results.

-Leveraging existing Big Data and Neuroimaging infrastructure and resources (CONP, CBRAIN, DataLad, Boutiques, LORIS, Compute Canada).

-Inbuilt platform quality control in the form of automatic unit and integration testing.

-Open source, version-controlled, scalable, organized, and well-documented code, which is simple to setup, maintain, and use.

-Should be able to generalize to other Neuro domains with minimal modifications.

Check out the code on my [GitHub](https://github.com/jacobsanz97/NDR-CI)

