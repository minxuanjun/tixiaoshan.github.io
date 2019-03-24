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

![](/_pages/pics/iros2019-unet.png){:height="50%" width="50%"}
*image_caption*

Education
======