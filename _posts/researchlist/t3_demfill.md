---
layout: article
title: "DEM filling"
categories: research
excerpt: "Topographic knowledge-guided DL method for DEM void filling"
tags: [research, DEM, Knowledge-guided DL]
modified: 2023-03-27
image:
  feature: DF_result1.png
  teaser: DF_Intro.png
ads: false
share: false
---



## Deep learning-based approach for landform classification from integrated data sources of digital elevation model and imagery

  In this paper, we proposed a topographic knowledge-guided DL method for DEM filling in mountainous areas. This work deal with the generation of steep terrains such as ridge and valley areas that have the inconsistent topographic form to neighboring surface.
  
## Publication

  [Li, S.J., Hu, G.H., Cheng, X.H., Xiong, L.Y., Tang, G.A., & Strobl, J., 2022. Integrating topographic knowledge into deep learning for the void-filling of digital elevation models. Remote Sensing of Environment, 269, 112818.](https://www.sciencedirect.com/science/article/abs/pii/S0034425721005381?via%3Dihub)

## Abstract

  Digital elevation models (DEMs) contain some of the most important data for providing terrain information and supporting environmental analyses. However, the applications of DEMs are significantly limited by data voids, which are commonly found in regions with rugged terrain. We propose a novel deep learning-based strategy called a topographic knowledge-constrained conditional generative adversarial network (TKCGAN) to fill data voids in DEMs. Shuttle Radar Topography Mission (SRTM) data with spatial resolutions of 3 and 1 arc-seconds are used in experiments to demonstrate the applicability of the TKCGAN. Qualitative topographic knowledge of valleys and ridges is transformed into new loss functions that can be applied in deep learning-based algorithms and constrain the training process. The results show that the TKCGAN outperforms other common methods in filling voids and improves the elevation and surface slope accuracy of the reconstruction results. The performance of the TKCGAN is stable in the test areas and reduces the error in the regions with medium and high surface slopes. Furthermore, the analysis of profiles indicates that the TKCGAN achieves better performance according to a visual inspection and quantitative comparison. In addition, the proposed strategy can be applied to DEMs with different resolutions. This work is an endeavour to transform topographic knowledge into computer-processable rules and benefits future research related to terrain reconstruction and modelling.
