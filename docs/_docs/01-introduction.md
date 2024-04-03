---
title: "Introduction"
permalink: /docs/introduction/
excerpt: "Large-scale dataset for grasp detection."
redirect_from:
  - /theme-setup/
toc: true
---
Welcome to the official webpage of the Grasp-Anything research project, where we explore the frontier of robotic grasp detection through the lens of advanced foundation models. Our project represents a pivotal shift in how large-scale grasp datasets are synthesized and utilized in the realm of robotics.

## Comparison with Related Datasets
![Dataset summarization](https://github.com/airvlab/grasp-anything/assets/140178004/ed30e350-d2ec-49ca-90bd-13471a46d3b9)

Our Grasp-Anything dataset uniquely offers *universality*, featuring a wide range of everyday objects in natural arrangements, unlike other benchmarks limited by object selection and controlled settings. To assess the diversity of object categories in our dataset, we leverage 300 categories of LVIS [1] dataset and identify 300 candidate objects from Grasp-Anything for each category using a pretrained classification model [2], a process we replicate with other datasets. It surpasses competitors in *number of objects* and *number of samples*.

<p align="center">
  <img src="https://github.com/airvlab/grasp-anything/assets/140178004/308e508d-1d5e-4324-81b4-c5428f345c9b" alt="number_of_objects" style="width: 48%;" />
</p>

In a log-scale graph comparing object counts, the Grasp-Anything dataset stands out for its significantly larger diversity of objects than seen in other datasets.

## Grasp-Anything Statistics

<p align="center">
  <img src="https://github.com/airvlab/grasp-anything/assets/140178004/0bceae02-b2b3-46b4-976e-ba533118aba5" alt="pos-tags" style="width: 50%;" />
  <img src="https://github.com/airvlab/grasp-anything/assets/140178004/c6d13578-10c0-4928-8255-3bdf16ec824a" alt="num_cats" style="width: 48%;" />
</p>

To categorize words in a text according to their grammatical roles and syntactic functions, we extract the POS tags in our dataset and visualize them in the above figure. Our scene descriptions corpus utilizes a wide range of words to describe scene arrangements. In addition, we also compare object shape distributions between Grasp-Anything and Jacquard. The outcome implies that objects in Grasp-Anything span over a greater area than Jacquard's, indicating a greater degree of shape diversity.

![shape_visualization](https://github.com/airvlab/grasp-anything/assets/140178004/2af94fd9-8672-4956-867c-499d4bebfa97)

## Stay Updated

As our research progresses, this website will be continuously updated with the latest papers, datasets, and tools. We encourage you to bookmark this page and check back regularly for updates.

We believe in the power of collaboration to push the boundaries of what's possible in robotic grasp detection. If you're interested in contributing to our research, utilizing our datasets, or simply learning more about our work, we'd love to hear from you.

Thank you for visiting the Grasp-Anything research project.

## References
[1] Gupta, A., Dollar, P., & Girshick, R. (2019). Lvis: A dataset for large vocabulary instance segmentation. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 5356-5364).

[2] Zhong, Y., Yang, J., Zhang, P., Li, C., Codella, N., Li, L. H., ... & Gao, J. (2022). Regionclip: Region-based language-image pretraining. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 16793-16803).
