---
layout: archive
title: ""
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

Lidar Super-resolution 
======
We propose a methodology for lidar super-resolution with ground vehicles driving on roadways, which relies completely on a driving simulator to enhance, via deep learning, the apparent resolution of a physical lidar. To increase the resolution of the point cloud captured by a sparse 3D lidar, we convert this problem from 3D Euclidean space into an image super-resolution problem in 2D image space, which is solved using a deep convolutional neural network. By applying Monte-Carlo dropout in the network and removing the predictions with high uncertainty, our method produces high accuracy point clouds comparable with the observations of a real high resolution lidar. We give the results of quantitative and qualitative tests using several real-world data-sets, which feature three different vehicle-mounted 3D lidars driven on urban and suburban roadways. We argue for the method's potential benefits in real-world robotics applications such as occupancy mapping and terrain modeling.

<p align='center'>
    <img src="/_pages/pics/iros2019-unet.png" alt="drawing" width="900"/>
    <img src="/_pages/pics/iros2019-ouster.gif" alt="drawing" width="450"/> <img src="/_pages/pics/iros2019-vlp16.gif" alt="drawing" width="450"/>
</p>

LeGO-LOAM
======
We propose a lightweight and ground-optimized lidar odometry and mapping method, LeGO-LOAM, for real-time six degree-of-freedom pose estimation with ground vehicles. LeGO-LOAM is lightweight, as it can achieve real-time pose estimation on a low-power embedded system. LeGO-LOAM is ground-optimized, as it leverages the presence of a ground plane in its segmentation and optimization steps. We first apply point cloud segmentation to filter out noise, and feature extraction to obtain distinctive planar and edge features. A two-step Levenberg-Marquardt optimization method then uses the planar and edge features to solve different components of the six degree-of-freedom transformation across consecutive scans. We compare the performance of LeGO-LOAM with a state-of-the-art method, LOAM, using datasets gathered from variable-terrain environments with ground vehicles, and show that LeGO-LOAM achieves similar or better accuracy with reduced computational expense. %The runtime of the proposed system is greatly reduced to enable its application on en embedded system. 
We also integrate LeGO-LOAM into a SLAM framework to eliminate the pose estimation error caused by drift, which is tested using the KITTI dataset.

<p align='center'>
    <img src="/_pages/pics/iros2018-demo.gif" alt="drawing" width="450"/> <img src="/_pages/pics/iros2018-stevens.gif" alt="drawing" width="450"/>
</p>

Traversability Mapping
======
We propose a new approach for traversability mapping with sparse lidar scans collected by ground vehicles, which leverages probabilistic inference to build descriptive terrain maps. Enabled by recent developments in sparse kernels, Bayesian generalized kernel inference is applied sequentially to the related problems of terrain elevation and traversability inference. The first inference step allows sparse data to support descriptive terrain modeling, and the second inference step relieves the burden typically associated with traversability computation. We explore the capabilities of the approach over a variety of data and terrain, demonstrating its suitability for online use in real-world applications.

<p align='center'>
    <img src="/_pages/pics/corl2018-bgk-1.gif" alt="drawing" width="450"/> <img src="/_pages/pics/corl2018-bgk-2.gif" alt="drawing" width="450"/>
    <img src="/_pages/pics/corl2018-bgk-3.gif" alt="drawing" width="450"/> <img src="/_pages/pics/corl2018-bgk-4.gif" alt="drawing" width="450"/>
</p>

Belief Roadmap Search
======
