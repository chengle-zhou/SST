#### SST | IEEE JSTARS 2025 | SSR from MSI to HSI
---
## A Selective Semantic Transformer for Spectral Super-Resolution of Multispectral Imagery

***Chengle Zhou, Zhi He, Guanglin Lai, and Antonio Plaza***

*[IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing](https://ieeexplore.ieee.org/document/10902158), 2025, doi: 10.1109/JSTARS.2025.3545039.*

---

![framework](https://github.com/chengle-zhou/MY-IMAGE/blob/2decde97242d9c80ae56aff79f60b835866ce33f/SST/framwork.png)

Fig. 1. Overview of our newly proposed SST method for spectral super-resolution.


## Abstract

Spectral super-resolution (SSR) is an important research area. It amounts at increasing the spectral resolution of a multispectral image (MSI) with a few spectral bands to obtain a hyperspectral image (HSI) with hundreds of narrow spectral bands. State-of-the-art SSR methods typically use the transformer (or its variants) to learn the spectral mapping from the MSI to the HSI. However, these methods tend to suffer from the interference of dissimilar structures due to the constraints imposed by patch-level operations. Besides, model interpretability is attributed to prior information (from data pre-processing) rather than from an end-to-end \textit{a priori} learning paradigm. To address these limitations, we propose a new selective semantic transformer (SST) for SSR. Our newly developed approach first characterizes contextual semantics within homogeneous regions and realizes information interaction from heterogeneous regions. Specifically, a superpixel-based spectral learning (SSL) strategy is designed to take into account excitated-transformer spatial and spectral semantic learning, including intra- and inter-superpixel relations, as well as superpixel edge details. Moreover, multi-scale and dense residual connection mechanisms are employed to model SSL modules into an end-to-end interpretable deep network for SSR. We first conducted experiments using three well-known airborne and satellite-based datasets and then evaluated the SSR performance of our method using satellite data collected from Sentinel-2 (MSI) and GF-5 (HSI) satellites.


## Kind Reminder

<span style="color:green;"> ***We are preparing the relevant code and will release it soon.*** </span>


## Citation Information
Please cite our new paper:

**Plain Text:**

Chengle Zhou, Zhi He, Guanglin Lai and Antonio Plaza. "[A Selective Semantic Transformer for Spectral Super-Resolution of Multispectral Imagery](https://ieeexplore.ieee.org/document/10902158)," ***IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing***, 2025, doi: 10.1109/JSTARS.2025.3545039.

**BibTex:**

```latex
@ARTICLE{10902158,
  author={Zhou, Chengle and He, Zhi and Lai, Guanglin and Plaza, Antonio},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={A Selective Semantic Transformer for Spectral Super-Resolution of Multispectral Imagery}, 
  year={2025},
  volume={},
  number={},
  pages={1-14},
  keywords={Multispectral images (MSIs);hyperspectral images (HSIs);spectral semantics;spectral super-resolution (SSR);transformer},
  doi={10.1109/JSTARS.2025.3545039}}
```
