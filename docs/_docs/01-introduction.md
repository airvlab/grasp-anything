---
title: "Introduction"
permalink: /docs/introduction/
excerpt: "Large-scale dataset for grasp detection."
redirect_from:
  - /theme-setup/
toc: true
---
Welcome to the official webpage of the Grasp-Anything research project, where we explore the frontier of robotic grasp detection through the lens of advanced foundation models. Our project represents a pivotal shift in how large-scale grasp datasets are synthesized and utilized in the realm of robotics.

## Dataset Comparison
<p align="center">
  <img src="../../assets/images/intro-dataset-comparison.png" alt="dataset_comparison" style="width: 100%;" />
</p>

Our Grasp-Anything dataset uniquely offers *universality*, featuring a wide range of everyday objects in natural arrangements, unlike other benchmarks limited by object selection and controlled settings. To assess the diversity of object categories in our dataset, we leverage 300 categories of LVIS [1] dataset and identify 300 candidate objects from Grasp-Anything for each category using a pretrained classification model [2], a process we replicate with other datasets. It surpasses competitors in *number of objects* and *number of samples*.

## Grasp-Anything Statistics

<p align="center">
  <img src="../../assets/images/pos-tags.png" alt="pos-tags" style="width: 50%;" />
  <img src="../../assets/images/num_cats.png" alt="num_cats" style="width: 48%;" />
</p>

To categorize words in a text according to their grammatical roles and syntactic functions, we extract the POS tags in our dataset and visualize them in the above figure. Our scene descriptions corpus utilizes a wide range of words to describe scene arrangements. In addition, we also compare object shape distributions between Grasp-Anything and Jacquard. The outcome implies that objects in Grasp-Anything span over a greater area than Jacquard's, indicating a greater degree of shape diversity.

<p align="center">
  <img src="../../assets/images/shape_visualization.png" alt="shape_visualization" style="width: 80%;" />
</p>


## Stay Updated

As our research progresses, this website will be continuously updated with the latest papers, datasets, and tools. We encourage you to bookmark this page and check back regularly for updates.

We believe in the power of collaboration to push the boundaries of what's possible in robotic grasp detection. If you're interested in contributing to our research, utilizing our datasets, or simply learning more about our work, we'd love to hear from you.

Thank you for visiting the Grasp-Anything research project.

## References
[1] Gupta, A., Dollar, P., & Girshick, R. (2019). Lvis: A dataset for large vocabulary instance segmentation. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 5356-5364).

[2] Zhong, Y., Yang, J., Zhang, P., Li, C., Codella, N., Li, L. H., ... & Gao, J. (2022). Regionclip: Region-based language-image pretraining. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 16793-16803).
