---
title: "Publications"
permalink: /publications/
author_profile: true
description: "Jiahao Wang’s selected publications on generative world models, 3D vision, and autonomous driving sensor simulation."
---

I study generative world models and 3D vision for embodied systems. My work includes generating camera and LiDAR data from real driving videos, maintaining 3D consistency during long-horizon video generation, and evaluating world models on open-loop and closed-loop tasks. Full list of publications can be found on [Google Scholar](https://scholar.google.com/citations?user=dKHE3qgAAAAJ).

## Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving {#sensor2sensor}

**Jiahao Wang**, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
*CVPR 2026*

Sensor2Sensor converts in-the-wild monocular footage from dashcams, online driving videos, phones, and other vehicle platforms into high-fidelity sensor logs with eight synchronized camera streams and LiDAR point clouds for a target autonomous vehicle. It uses 4D Gaussian Splatting to render synthetic dashcam footage from real vehicle logs, then pairs the footage with the original sensor recordings to train a joint camera–LiDAR diffusion model. The paper evaluates generation quality and visualizes camera–LiDAR alignment. It assesses simulation fidelity through LiDAR vehicle detection and image segmentation.

[CVPR paper (CVF)](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Sensor2Sensor_Cross-Embodiment_Sensor_Conversion_for_Autonomous_Driving_CVPR_2026_paper.html) · [arXiv:2605.22809](https://arxiv.org/abs/2605.22809) · [Waymo Research](https://waymo.com/research/sensor-2-sensor-cross-embodiment-sensor/)

<details>
<summary>Sensor2Sensor CVPR BibTeX</summary>
<pre><code>{% raw %}@inproceedings{Wang_2026_CVPR,
  author    = {Wang, Jiahao and Sun, Bo and Bai, Yijing and Casser, Vincent and Peng, Songyou and Zhu, Zehao and Shih, Meng-Li and Masotto, Xander and Su, Shih-Yang and Parvate, Kanaad and Ge, Tiancheng and Bieske, Linn and Anguelov, Dragomir and Tan, Mingxing and Jiang, Chiyu Max},
  title     = {{Sensor2Sensor}: Cross-Embodiment Sensor Conversion for Autonomous Driving},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2026},
  pages     = {32093--32102}
}{% endraw %}</code></pre>
</details>

## Captain Safari: A World Engine with Pose-Aligned 3D Memory {#captain-safari}

Yu-Cheng Chou, Xingrui Wang, Yitong Li, **Jiahao Wang**, Hanting Liu, Cihang Xie, Alan Yuille, Junfei Xiao  
*CVPR 2026*

Captain Safari retrieves pose-aligned tokens from persistent 3D memory to generate long videos along user-specified 6-DoF camera trajectories. The paper introduces OpenSafari, a benchmark of real first-person drone videos with validated camera paths, to evaluate trajectory following and 3D consistency during fast camera motion.

[CVPR paper (CVF)](https://openaccess.thecvf.com/content/CVPR2026/html/Chou_Captain_Safari_A_World_Engine_with_Pose-Aligned_3D_Memory_CVPR_2026_paper.html) · [arXiv](https://arxiv.org/abs/2511.22815) · [Project and OpenSafari](https://johnson111788.github.io/open-safari/)

## World-In-World: World Models in a Closed-Loop World {#world-in-world}

Jiahan Zhang, Muqing Jiang, Nanru Dai, Taiming Lu, Arda Uzunoglu, Shunchi Zhang, Yana Wei, **Jiahao Wang**, Vishal M. Patel, Paul Pu Liang, Daniel Khashabi, Cheng Peng, Rama Chellappa, Tianmin Shu, Alan Yuille, Yilun Du, Jieneng Chen  
*ICLR 2026 (Oral)*

World-In-World evaluates whether generative video world models help embodied agents make decisions in closed loop. A shared action interface connects world models to online planning, and the benchmark measures task success across settings that include visual navigation and robotic manipulation.

[ICLR proceedings](https://proceedings.iclr.cc/paper_files/paper/2026/hash/5b4263be85820683d78675cc18d2efc7-Abstract-Conference.html) · [arXiv](https://arxiv.org/abs/2510.18135) · [Project](https://world-in-world.github.io/)

## Drive&Gen: Co-Evaluating End-to-End Driving and Video Generation Models {#drive-and-gen}

**Jiahao Wang**, Zhenpei Yang, Yijing Bai, Yingwei Li, Yuliang Zou, Bo Sun, Abhijit Kundu, Jose Lezama, Luna Yue Huang, Zehao Zhu, Jyh-Jing Hwang, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
*IROS 2025 (Oral)*

Drive&Gen uses end-to-end driving planners to assess generated videos and uses controllable video generation to probe planner behavior. By varying weather and time of day, it isolates factors that affect planning and tests whether synthetic video can improve planner generalization beyond the training conditions.

[IROS paper (IEEE Xplore)](https://ieeexplore.ieee.org/document/11247678) · [arXiv](https://arxiv.org/abs/2510.06209) · [Waymo Research](https://waymo.com/research/drive-gen-co-evaluating/)

## EvoWorld: Evolving Panoramic World Generation with Explicit 3D Memory {#evoworld}

**Jiahao Wang**\*, Luoxin Ye\*, TaiMing Lu, Junfei Xiao, Jiahan Zhang, Yuxiang Guo, Xijun Liu, Rama Chellappa, Cheng Peng, Alan Yuille, Jieneng Chen  
\* Equal contribution.  
*arXiv 2025 · ICLR 2026 Workshop on World Models*

EvoWorld starts from a single 360° panorama and generates egocentric video along a camera trajectory. It updates an explicit 3D reconstruction and reprojects it into future views to preserve scene geometry when the camera revisits an area. Spatial360 evaluates long-horizon panoramic generation across indoor, outdoor, synthetic, and real scenes.

[arXiv](https://arxiv.org/abs/2510.01183) · [Workshop on OpenReview](https://openreview.net/forum?id=YjRjKjfjoC) · [Code](https://github.com/JiahaoPlus/EvoWorld)

## SceneCrafter: Controllable Multi-View Driving Scene Editing {#scenecrafter}

Zehao Zhu, Yuliang Zou, Chiyu Max Jiang, Bo Sun, Vincent Casser, Xiukun Huang, **Jiahao Wang**, Zhenpei Yang, Ruiqi Gao, Leonidas Guibas, Mingxing Tan, Dragomir Anguelov  
*CVPR 2025*

SceneCrafter edits real driving logs across multiple cameras with a multi-view diffusion model. It changes weather, time of day, and traffic-agent placement while preserving cross-camera geometry, using paired training examples for both global appearance changes and local object edits.

[CVPR paper (CVF)](https://openaccess.thecvf.com/content/CVPR2025/html/Zhu_SceneCrafter_Controllable_Multi-View_Driving_Scene_Editing_CVPR_2025_paper.html)

## Generating Images with 3D Annotations Using Diffusion Models {#3d-dst}

Wufei Ma\*, Qihao Liu\*, **Jiahao Wang**\*, Angtian Wang, Xiaoding Yuan, Yi Zhang, Zihao Xiao, Guofeng Zhang, Beijia Lu, Ruxiao Duan, Yongrui Qi, Adam Kortylewski, Yaoyao Liu, Alan Yuille  
\* Equal contribution.  
*ICLR 2024 (Spotlight)*

3D Diffusion Style Transfer (3D-DST) conditions image generation on edges rendered from 3D assets, so the resulting synthetic images come with known object poses and 3D annotations. The paper evaluates the resulting training data for image classification and 3D pose estimation under in-distribution and out-of-distribution conditions.

Earlier preprint title: *Adding 3D Geometry Control to Diffusion Models*.

[ICLR](https://proceedings.iclr.cc/paper_files/paper/2024/hash/c39578c86423df5f9e8834ce1cd456e4-Abstract-Conference.html) · [arXiv](https://arxiv.org/abs/2306.08103) · [Project](https://ccvl.jhu.edu/3D-DST/)

## Structure-Aware Sparse-View X-ray 3D Reconstruction {#sax-nerf}

Yuanhao Cai, **Jiahao Wang**, Alan Yuille\*, Zongwei Zhou\*, Angtian Wang  
\* Corresponding authors (CVPR version).  
*CVPR 2024*

SAX-NeRF reconstructs 3D radiodensity from sparse X-ray projections. Its Lineformer models structure along X-ray paths, and the X3D dataset supports evaluation of sparse-view CT reconstruction and novel-view X-ray synthesis.

[CVPR paper (CVF)](https://openaccess.thecvf.com/content/CVPR2024/html/Cai_Structure-Aware_Sparse-View_X-ray_3D_Reconstruction_CVPR_2024_paper.html) · [Code](https://github.com/caiyuanhao1998/SAX-NeRF)

## OOD-CV-v2: An Extended Benchmark for Robustness to Out-of-Distribution Shifts of Individual Nuisances in Natural Images {#ood-cv-v2}

Bingchen Zhao, **Jiahao Wang**, Wufei Ma, Artur Jesslen, Siwei Yang, Shaozuo Yu, Oliver Zendel, Christian Theobalt, Alan Yuille, Adam Kortylewski  
*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2024*

OOD-CV-v2 benchmarks robustness to specific changes in object pose, shape, texture, scene context, and weather. It measures how each shift affects image classification, object detection, and 3D pose estimation across ten object categories in natural images.

[Journal article](https://doi.org/10.1109/TPAMI.2024.3462293) · [arXiv](https://arxiv.org/abs/2304.10266)

## Animal3D: A Comprehensive Dataset of 3D Animal Pose and Shape {#animal3d}

Jiacong Xu, Yi Zhang, Jiawei Peng, Wufei Ma, Artur Jesslen, Pengliang Ji, Qixin Hu, Jiehua Zhang, Qihao Liu, **Jiahao Wang**, Wei Ji, Chen Wang, Xiaoding Yuan, Prakhar Kaushik, Guofeng Zhang, Jie Liu, Yushan Xie, Yawen Cui, Alan Yuille, Adam Kortylewski  
*ICCV 2023*

Animal3D provides 3,379 images from 40 mammal species, with 26 annotated keypoints and fitted SMAL pose and shape parameters. It benchmarks 3D animal pose and shape estimation across species, including transfer from synthetic data and human pose models.

[ICCV paper (CVF)](https://openaccess.thecvf.com/content/ICCV2023/html/Xu_Animal3D_A_Comprehensive_Dataset_of_3D_Animal_Pose_and_Shape_ICCV_2023_paper.html) · [Project and dataset](https://xujiacong.github.io/Animal3D/)

## SAGA: Stochastic Whole-Body Grasping with Contact {#saga}

Yan Wu\*, **Jiahao Wang**\*, Yan Zhang, Siwei Zhang, Otmar Hilliges, Fisher Yu, Siyu Tang  
\* Equal contribution.  
*ECCV 2022*

SAGA generates diverse 3D human motions that approach and grasp a target object from a given initial pose. It jointly predicts a whole-body grasp pose and human–object contacts, then uses contact-aware motion infilling to generate the approach and grasp.

[ECCV](https://link.springer.com/chapter/10.1007/978-3-031-20068-7_15) · [arXiv](https://arxiv.org/abs/2112.10103) · [Project](https://jiahaoplus.github.io/SAGA/saga.html)

## Gaussian Field Estimator with Manifold Regularization for Retinal Image Registration {#retinal-image-registration}

**Jiahao Wang**, Jun Chen, Huihui Xu, Shuaibin Zhang, Xiaoguang Mei, Jun Huang, Jiayi Ma  
*Signal Processing, 2019*

This method aligns retinal images by matching local feature points with a Gaussian field estimator. Manifold regularization preserves the underlying geometry of the feature points during registration, addressing noise, mismatches, and limited overlap.

[Journal article](https://www.sciencedirect.com/science/article/abs/pii/S0165168418303955)

<!--
<b><a href="https://ieeexplore.ieee.org/document/8089726">Robust Image Feature Matching via Progressive Sparse Spatial Consensus</a></b><br>
Yong Ma, <b>Jiahao Wang</b>, Huihui Xu, Shuaibin Zhang, Xiaoguang Mei, and Jiayi Ma<br>
<i>IEEE Access, vol. 5, pp. 24568-24579, 2017.</i>
-->
