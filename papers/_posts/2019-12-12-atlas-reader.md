---
layout: paper
title: "AtlasReader: A Python package to generate coordinate tables, region labels, and informative figures from statistical MRI images"
nickname:
authors: "Notter M, Gale D, Herholz P, Markello R, Notter-Bielser ML, Whitaker K"
year: "2019"
journal: "Journal of Open Source Software"
volume: 4
issue: 34
pages: 1257
is_published: true
image: /images/pubpic/nibetaseries.png
projects: []
tags: []

# Text
fulltext: https://doi.org/10.21105/joss.01295
pdf:
pdflink: https://www.theoj.org/joss-papers/joss.01257/10.21105.joss.01257.pdf
pmcid:
preprint:
supplement:

# Links
doi: "10.21105/joss.01295"
pmid:

# Data and code
github: https://github.com/miykael/atlasreader
neurovault:
openneuro:
osf:
---
{% include JB/setup %}

# Abstract

A major advantage of magnetic resonance imaging (MRI) over other neuroimaging methods is its capability to non-invasively locate a region of interest (ROI) in the human brain.For example, using functional MRI, we are able to pinpoint where in the brain a cognitive task elicits higher activation relative to a control. But just knowing the Cartesian coordinate of such a ROI is not useful if we cannot assign it a neuroanatomical label. Forthis reason, MRI images are usually normalized into a common template space (Fonov etal., 2011), where well-established atlases can be used to associate a given coordinate with the label of a brain region. Most major neuroimaging software packages provide some functionality to locate the main peaks of an ROI but this functionality is often restricted to a few atlases, frequently requires manual intervention, does not give the user much flexibility in the output creation process, and never considers the full extent of the ROI.To tackle those shortcomings, we created AtlasReader, a Python interface for generating coordinate tables and region labels from statistical MRI images. With AtlasReader, users can use any of the freely and publicly available neuroimaging atlases, without any restriction to their preferred software package, to create publication-ready output figures and tables that contain relevant information about the peaks and clusters extent of each ROI.To our knowledge, providing atlas information about the full extent of a cluster, i.e. over which atlas regions does a ROI extent, is a new feature that is not available in any other,comparable neuroimaging software package
