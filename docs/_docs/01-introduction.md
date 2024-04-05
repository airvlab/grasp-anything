---
title: "Introduction"
permalink: /docs/introduction/
excerpt: "Large-scale dataset for grasp detection."
redirect_from:
  - /theme-setup/
toc: true
---
Welcome to Grasp-Anything project! We tackle grasp detection by utilizing foundation models. Our project represents a <strong>data centric</strong> approach for grasp detection.

## Dataset Comparison
<p align="center">
  <img src="../../assets/images/intro-dataset-comparison.png" alt="dataset_comparison" style="width: 100%;" />
</p>

Grasp-Anything offers *universality*, featuring a wide range of everyday objects in natural arrangements, unlike other benchmarks limited by object selection and controlled settings.

## Statistics

<p align="center">
  <img src="../../assets/images/homepage-num-samples.png" alt="num-samples" style="width: 50%;" />
  <img src="../../assets/images/homepage-num-objects.png" alt="num-objects" style="width: 49%;" />
</p>

Grasp-Anything contains over four times as many samples as related datasets and has a greater degree of object diversity, which is evidenced by the number of objects and coverage of nearly double the LVIS categories [[1]](#references) compared to other datasets.

<p align="center">
  <img src="../../assets/images/pos-tags.png" alt="pos-tags" style="width: 50%;" />
  <img src="../../assets/images/num_cats.png" alt="num-cats" style="width: 48%;" />
</p>

We study the text's grammatical roles and syntactic functions by extracting the POS tags in our dataset, which is visualized in the figure above, highlighting a diverse vocabulary in scene descriptions. In addition, by comparing the object shape distributions between Grasp-Anything and Jacquard, we demonstrate that Grasp-Anything covers a wider area, suggesting a higher level of shape diversity.

<p align="center">
  <img src="../../assets/images/shape_visualization.png" alt="shape_visualization" style="width: 80%;" />
</p>


## Stay Updated

This website will be continuously updated with the latest papers, datasets, and code. We encourage you to check back regularly for updates.



## References
<a name="references"></a>
- [1] Gupta, A., Dollar, P., & Girshick, R. Lvis: A dataset for large vocabulary instance segmentation. In CVPR, 2019.
