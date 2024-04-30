---
title: "Robust deep learning object recognition models rely on low frequency information in natural images"
collection: publications
permalink: /publication/2023-Robust
date: 2023-03-27
venue: 'PLOS Computational Biology'
---
Machine learning models have difficulty generalizing to data outside of the distribution they were trained on. In particular, vision models are usually vulnerable to adversarial attacks or common corruptions, to which the human visual system is robust. Recent studies have found that regularizing machine learning models to favor brain-like representations can improve model robustness, but it is unclear why. We hypothesize that the increased model robustness is partly due to the low spatial frequency preference inherited from the neural representation. We tested this simple hypothesis with several frequency-oriented analyses, including the design and use of hybrid images to probe model frequency sensitivity directly. We also examined many other publicly available robust models that were trained on adversarial images or with data augmentation, and found that all these robust models showed a greater preference to low spatial frequency information. We show that preprocessing by blurring can serve as a defense mechanism against both adversarial attacks and common corruptions, further confirming our hypothesis and demonstrating the utility of low spatial frequency information in robust object recognition.

[access the paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010932)

[access the code](https://github.com/lizhe07/blur-net)

```
@article{li2023robust,
  title={Robust deep learning object recognition models rely on low frequency information in natural images},
  author={Li, Zhe and Ortega Caro, Josue and Rusak, Evgenia and Brendel, Wieland and Bethge, Matthias and Anselmi, Fabio and Patel, Ankit B and Tolias, Andreas S and Pitkow, Xaq},
  journal={PLOS Computational Biology},
  volume={19},
  number={3},
  pages={e1010932},
  year={2023},
  publisher={Public Library of Science San Francisco, CA USA}
}
```

