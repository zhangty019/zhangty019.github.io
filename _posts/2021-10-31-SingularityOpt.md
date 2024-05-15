---
layout: post
title: Singularity-aware motion Planning for multi-axis additive Manufacturing
subtitle:  IEEE International Conference on Automation Science and Engineering (CASE), Lyon, France
# cover-img: /assets/img/curvedSupport/teaser.jpg
thumbnail-img: /assets/img/SingularityOpt/teaser.jpg
# share-img: /assets/img/path.jpg
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
# tags: [test]
# comments: true
author: Tianyu Zhang
---

Multi-axis additive manufacturing enables high flexibility of material deposition along dynamically varied directions. The Cartesian motion platforms of these machines include three parallel axes and two rotational axes. Singularity on rotational axes is a critical issue to be tackled in motion planning to ensure high-quality manufacturing results. The highly nonlinear mapping in the singular region can convert a smooth toolpath with uniformly sampled waypoints defined in the model coordinate system into a highly discontinuous motion in the machine coordinate system, which leads to over-extrusion / under-extrusion of materials in filament-based additive manufacturing. The problem is challenging as both the maximal and the minimal speeds at the tip of a printer head must be controlled in motion. Moreover, a collision may occur when sampling-based collision avoidance is employed. In this paper, we present a motion planning method to support the manufacturing realization of designed toolpaths for multi-axis additive manufacturing. Problems of singularity and collision are considered in an integrated manner to improve the motion and, therefore, the quality of fabrication.
##### [Source Code](https://github.com/zhangty019/MultiAxis_3DP_MotionPlanning) is available!

![printing_result](/assets/img/SingularityOpt/printing_result.gif)

##### This method can be extended to multiple CNC configurations and print quality optimization effects

![pipeline](/assets/img/SingularityOpt/configs_printingQuality.jpg)

##### Printing clips

![hardware](/assets/img/SingularityOpt/printing_video.gif)

##### Contact:
Tianyu Zhang (tianyu.zhang-10@postgrad.manchester.ac.uk) 
