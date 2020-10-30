---
title: How to handle dataset shifts when applying machine learning to biomedical data
status: active
layout: project
people:
  - Jerome
---

Machine learning can be applied to large datasets of biomedical measurements and electronic health records for diagnostic, prognostic, screening, etc. However medical research datasets often fail to faithfully represent the target population -- the population that could benefit from the deployment of a machine learning model in production -- for example due to sample selection biases. When training and test examples are drawn from different distributions we say there exists a dataset shift. In this project we aim to:

1. Investigate to what extend dataset shifts degrade the prediction performance of machine learning models on the UKBiobank dataset.

2.Eevaluate methods that can detect or correct dataset shifts. In particular, we plan to leverage recent advances in the field of distributionally robust optimization.


