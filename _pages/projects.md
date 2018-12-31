---
<!-- layout: archive -->
title: "Projects"
permalink: /projects/
author_profile: true
---
## Retinal Image Registration [[paper]](https://authors.elsevier.com/c/1YDGYbZX4vg-J)
<img width="390" height="150" src="https://JiahaoPlus.github.io/images/gfemr_our_m.jpg"/>  <img width="192" height="150" src="https://JiahaoPlus.github.io/images/gfemr_our_r.jpg"/> <br>
Retinal image registration plays an important role in diagnosing and treating many eye diseases. In this work, we propose an efficient algorithm called Gaussian field estimator with manifold regularization (GFEMR). We formulate the registration problem as a probabilistic model, that is, a Gaussian field estimator, to achieve a robust estimation, associated with a prior involving manifold regularization to preserve the intrinsic geometry of input data. A sparse approximation is applied to the non-rigid transformation for a fast implementation. Extensive experiments show that our approach can yield superior results compared with other state-of-the-art methods, especially in the case of severely degraded data.

## Robust Feature Matching [[paper]](https://ieeexplore.ieee.org/document/8089726), [[code]](https://github.com/JiahaoPlus/PSSC)
<img width="800" height="286" src="https://JiahaoPlus.github.io/images/PSSC.PNG"/> <br>
Feature matching is a key problem in computer vision, graphics, robot location, and medical image registration. The features are often salient points with associated descriptors extracted by detectors, and the goal is to find point correspondences according to their positions and descriptors. However, in real-world matching problems, the putative matches typically contain a large proportion of outliers. Thus, we introduce a progressive framework, which uses matching results on a small putative set with high inlier ratio to guide the matching on a large putative set. The spatial consensus is modeled by a non-parametric thinplate spline kernel and a sparse approximation is applied to accelerate the optimization. The quantitative results on various experimental data demonstrate that our method can achieve better matching accuracy and can generate more good matches compared to several state-of-the-art methods.

## Medical Image Segmentation [[poster]](https://JiahaoPlus.github.io/files/UCLA_Poster.pdf)
<img width="800" height="435" src="https://JiahaoPlus.github.io/images/HaN.jpg"/> <br>
Accurate segmentation of organs at risks (OARs) is an essential step for the planning of radiation therapy for head and neck (H&N) cancer treatment. However, this procedure is mostly carried out manually in the clinic, and the average physician's time to fully contour a single head and neck case is approximately 2.7 hours. Automatic segmentation of OARs is a challenging task due to the low contrast of soft tissue, artifacts in CT images, and limited labeled slices for training. To deal with the problems, we propose a conditional generative adversarial network (cGAN) based algorithm for automatic segmentation of OARs in H&N CT images.

## Olfactory Bulb Volume Measurement Using MRI Scans
<img width="800" height="322" src="https://JiahaoPlus.github.io/images/OB.png"/><br>
The olfactory bulb is a nerve structure located on the inferior side of the brain, whose size is a reliable indicator of several neurodegenerative diseases. However, olfactory bulbs are minuscule in MRI scans and, therefore, difficult to detect. Also, the number of scans in the dataset is limited. For this project, I used the center of gravity to infer rough bounding boxes of olfactory bulbs, and combined machine learning with morphological operations to accurately separate olfactory bulbs from other noise regions, which is of great value in clinical use.

## Customer Support Request Alerting System
<img width="800" height="420" src="https://JiahaoPlus.github.io/images/SR.png"/><br>
Based on text mining, machine learning, and domain knowledge, I built an intelligent alerting system to help the global support services deal with customer requests. This system can identify the severity of requests and accordingly dispatch engineers. The precision and recall of the identification was close to 90%, and this model improved response times by an average of 37%. Our project was awarded as the “Best Idea Award” at VMware China Borathon (hackathon, 36 teams, more than 100 engineers participated).