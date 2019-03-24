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
    <img src="/_pages/pics/iros2019-unet.png" alt="drawing" width="800"/>
    <img src="/_pages/pics/iros2019-ouster.gif" alt="drawing" width="400"/> <img src="/_pages/pics/iros2019-vlp16.gif" alt="drawing" width="400"/>
</p>

Traversability Mapping
======
We propose a new approach for traversability mapping with sparse lidar scans collected by ground vehicles, which leverages probabilistic inference to build descriptive terrain maps. Enabled by recent developments in sparse kernels, Bayesian generalized kernel inference is applied sequentially to the related problems of terrain elevation and traversability inference. The first inference step allows sparse data to support descriptive terrain modeling, and the second inference step relieves the burden typically associated with traversability computation. We explore the capabilities of the approach over a variety of data and terrain, demonstrating its suitability for online use in real-world applications.

<p align='center'>
    <img src="/_pages/pics/corl2018-bgk-1.gif" alt="drawing" width="400"/> <img src="/_pages/pics/corl2018-bgk-2.gif" alt="drawing" width="400"/>
    <img src="/_pages/pics/corl2018-bgk-3.gif" alt="drawing" width="400"/> <img src="/_pages/pics/corl2018-bgk-4.gif" alt="drawing" width="400"/>
</p>