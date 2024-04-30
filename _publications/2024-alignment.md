---
title: "Removing High Frequency Information Improves DNN Behavioral Alignment"
collection: publications
permalink: /publication/2024-alignment
date: 2024-06-05
venue: 'ICLR 2024 Workshop Re-Align'
---
Despite their increasingly impressive performance and capabilities, to date there still exists a significant misalignment between Deep Neural Networks (DNNs) and human behavior. A large body of research exists identifying misalignments and exploring where they arise from, with some work attributing it to the fact that humans and DNNs use the frequency spectrum of images differently. In this paper, we show that removing high-frequency information by applying blur and resize transformations to images before being fed to a DNN dramatically improves its alignment with humans according to shape-bias and error-consistency. Specifically, a ViT-H-14 OpenCLIP model tested on blurred images achieves an error-consistency with humans of 0.37, halving the current gap between DNN-human and human-human error-consistency. While these operations do affect a model's accuracy, we present preliminary evidence for an alignment-accuracy tradeoff, and note that moving forward, practitioners may have to choose between having a model with superhuman accuracy and one that behaves like a human.

[access the paper](https://openreview.net/forum?id=Ho0x9DgdZw)