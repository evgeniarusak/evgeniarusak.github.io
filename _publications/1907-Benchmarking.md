---
title: "Benchmarking robustness in object detection: Autonomous driving when winter is coming."
collection: publications
permalink: /publication/1907-Benchmarking
date: 2019-12-12
venue: 'The Machine Learning for Autonomous Driving Workshop, NeurIPS'
---
The ability to detect objects regardless of image distortions or weather conditions is crucial for real-world applications of deep learning like autonomous driving. We here provide an easy-to-use benchmark to assess how object detection models perform when image quality degrades. The three resulting benchmark datasets, termed Pascal-C, Coco-C and Cityscapes-C, contain a large variety of image corruptions. We show that a range of standard object detection models suffer a severe performance loss on corrupted images (down to 30--60% of the original performance). However, a simple data augmentation trick---stylizing the training images---leads to a substantial increase in robustness across corruption type, severity and dataset. We envision our comprehensive benchmark to track future progress towards building robust object detection models. Benchmark, code and data are publicly available.

[Access the paper](https://arxiv.org/abs/1907.07484)

[Access the code](https://github.com/bethgelab/robust-detection-benchmark)

```
@article{michaelis2019dragon,
  title={Benchmarking Robustness in Object Detection: 
    Autonomous Driving when Winter is Coming},
  author={Michaelis, Claudio and Mitzkus, Benjamin and 
    Geirhos, Robert and Rusak, Evgenia and 
    Bringmann, Oliver and Ecker, Alexander S. and 
    Bethge, Matthias and Brendel, Wieland},
  journal={arXiv preprint arXiv:1907.07484},
  year={2019}
}
```