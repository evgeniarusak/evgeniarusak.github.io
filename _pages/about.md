---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a PhD Student at the [University of Tübingen](https://uni-tuebingen.de/en/) and the [International Max Planck Research School (IMPRS) for Intelligent Systems (IS)](https://imprs.is.mpg.de/). I am co-supervised by [Oliver Bringmann](https://www.embedded.uni-tuebingen.de/team/oliver-bringmann/) and [Wieland Brendel](https://scholar.google.de/citations?user=v-JL-hsAAAAJ). Before my PhD, I have obtained a B.Sc. and a M.Sc. in Physics at the [Karlsruhe Institute of Technology](https://www.kit.edu/english/index.php). During my Master's, I have participated in several research projects centered around numerical optics, and my Master thesis has been published at [Nature Communications](https://www.nature.com/articles/s41467-019-13748-4).

During my PhD, I have been working on improving the **generalization capabilities of Deep Neural Networks** beyond their training distribution. I have explored how we can make vision models more robust to input corruptions, such as various noise types or blurs and other **distribution shifts**. Beyond investigating different robustification methods, I have also analyzed the benefits of **continual learning** when the model is allowed to adapt to the encountered distribution shifts.

With the increasing availability of web-scale training data, the boundary between the training distribution and the conventionally used test sets becomes blurry. In my recent works, I am trying to understand how the OOD generalization capabilities of popular foundation models trained on large-scale datasets can be benchmarked. I also find it intriguing to investigate how **multi-modality** affects the learned representations and their generalizability.


Latest publications (ICLR 2024)
======

[**Effective pruning of web-scale datasets based on complexity of concept clusters**](https://openreview.net/forum?id=CtOA9aN8fr)\
Amro Abbas\*, <ins>Evgenia Rusak</ins>\*, Kushal Tirumala, Wieland Brendel, Kamalika Chaudhuri, Ari S. Morcos, *ICLR 2024*

How much data is needed to learn a certain concept? Some classes or concepts are easier than others: Distinguishing zebra stripes is a simple pattern matching task, while understanding more high-level concepts is more challenging. In this work, we take the complexity of different concepts into account for pruning large-scale multimodal datasets in order to improve the efficiency of training machine learning models. We have successfully reduced the training cost to a quarter of regular training. On DataComp Medium, we have achieved competitive performance on 38 evaluation tasks. This project has also been presented as an **oral** contribution at the [DataComp Workshop at ICCV 2024](https://www.datacomp.ai/workshop.html). I have worked on this project during my internship at [FAIR](https://ai.meta.com/research/) under the supervision of [Ari Morcos](https://www.arimorcos.com/) and [Kamalika Chaudhuri](https://cseweb.ucsd.edu/~kamalika/).


[**Does CLIP’s generalization performance mainly stem from high train-test similarity?**](https://openreview.net/forum?id=tnBaiidobu)\
Prasanna Mayilvahanan\*, Thaddäus Wiedemer\*, <ins>Evgenia Rusak</ins>, Matthias Bethge, Wieland Brendel, *ICLR 2024*

Can we trust OOD benchmark results when testing foundation models such as CLIP? Given the huge datasets CLIP models have been trained on, could it be that CLIP's training data simply contains most of our conventional OOD benchmarks? In that case, claims about CLIP's OOD generalization capabilities would become meaningless and unfounded. To test this hypothesis, we retrain CLIP on pruned LAION splits that replicate ImageNet’s train-test similarity with respect to common OOD benchmarks. While we observe a performance drop on some benchmarks, surprisingly, CLIP’s overall performance remains high. This shows that high train-test similarity is insufficient to explain CLIP’s OOD performance, and other properties of the training data must drive CLIP to learn more generalizable representations. Additionally, by pruning data points that are dissimilar to the OOD benchmarks, we uncover a 100M split of LAION (¼ of its original size) on which CLIP can be trained to match its original OOD performance. This project has also been presented as an **oral** contribution at the [Workshop on Distribution Shifts (DistShift) at NeurIPS 2023](https://sites.google.com/view/distshift2023).


[**Removing High Frequency Information Improves DNN Behavioral Alignment**](https://openreview.net/forum?id=Ho0x9DgdZw)\
Max Wolff,  <ins>Evgenia Rusak</ins>, Wieland Brendel, *Workshop on Representational Alignment, ICLR 2024*

Despite their increasingly impressive performance and capabilities, to date there still exists a significant misalignment between Deep Neural Networks (DNNs) and human behavior. A large body of research exists identifying misalignments and exploring where they arise from, with some work attributing it to the fact that humans and DNNs use the frequency spectrum of images differently. In this paper, we show that removing high-frequency information by applying blur and resize transformations to images before being fed to a DNN dramatically improves its alignment with humans according to shape-bias and error-consistency. While these operations do affect a model's accuracy, we present preliminary evidence for an alignment-accuracy tradeoff, and note that moving forward, practitioners may have to choose between having a model with superhuman accuracy and one that behaves like a human.

[More publications](https://evgeniarusak.github.io/publications)


