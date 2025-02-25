---
title: "Nipoppy: A framework for the reproducible organization and processing neuroimaging-clinical datasets"
subtitle: A Neurobagel complement project
image: img/projects/nipoppy_protocol.png
status: active
layout: project
repository: https://github.com/nipoppy/nipoppy/tree/main
documentation: https://nipoppy.readthedocs.io/en/latest
people:
  - Michelle
  - Nikhil
  - Mathieu
  - Brent
  - Mohammad
  - Jacob
  - Julia
  - Remi
  - Vincent
  - Ines
---

# Nipoppy

Nipoppy is a lightweight framework for standardized organization and processing of datasets that have magnetic resonance imaging (MRI) and clinical data.

The framework consists of the following:

1. A **standardized workflow process (i.e., protocol)** covering the following:
   - Curation and organization of MRI and tabular data
     - E.g., conversion of DICOM data to BIDS
   - Standardized processing of imaging data using existing or custom pipelines
     - E.g., [fMRIPrep](https://fmriprep.org/en/stable/), [MRIQC](https://mriqc.readthedocs.io/en/stable/)
     - The [Boutiques framework](https://boutiques.github.io/) is used to flexibly execute and add new pipelines
   - Tracking of availability status for raw and processed data
     - We also develop an interactive [dashboard](https://digest.neurobagel.org/) for easy visualization of tracker results
   - Extraction of imaging-derived phenotypes (IDPs) into files ready for downstream analysis

2. A **data organization specification** for both imaging and non-imaging data

   - Whenever possible, we follow the [Brain Imaging Data Structure (BIDS) standard](https://bids.neuroimaging.io/)
   - We provide additional specifications for cases not (yet) covered by BIDS, such as phenotypic data and imaging derivatives

<p align="center">
   <img src="/img/projects/nipoppy_specification.jpg" alt="Nipoppy dataset layout" width="400">
</p>

3. A [software package](https://github.com/nipoppy/nipoppy/tree/main) with tools to help work within the framework

Nipoppy can also provide metadata to [Neurobagel](https://www.neurobagel.org/documentation/) tools to allow for data harmonization and federated search of participants across multiple studies.
