---
layout: post
title: Support Generation for Robot-Assisted 3D Printing with Curved Layers
subtitle: IEEE International Conference on Robotics and Automation (ICRA), London, UK
# cover-img: /assets/img/curvedSupport/teaser.jpg
thumbnail-img: /assets/img/curvedSupport/teaser.jpg
# share-img: /assets/img/path.jpg
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
# tags: [test]
# comments: true
author: Tianyu Zhang
---

Robot-assisted 3D printing has drawn a lot of attention because of its capability to fabricate curved layers that are optimized according to different objectives. However, **the support generation algorithm based on a fixed printing direction for planar layers cannot be directly applied to curved layers** as the orientation of material accumulation is dynamically varied. In this project, we propose **a skeleton-based support generation method for robot-assisted 3D printing with curved layers**. 

##### [Source Code](https://github.com/zhangty019/Support_Generation_for_Curved_RoboFDM) is available!

![printing_result](/assets/img/curvedSupport/printing_result.gif)

##### Pipeline
1. Computational domain generation from support envelop hull;
2. Compatible curved support layers generation;
3. Tree-like support skeleton calculation;  
4. Implicit solid construction;
5. Support region extraction; 

![pipeline](/assets/img/curvedSupport/pipeline.jpg){: .mx-auto.d-block :}

##### Dual-material Robot-assisted 3D Printing System.
A **2-in-1** extruder is installed on the end-effector of the robot arm, different filaments can be controlled to pass through the Y-shape structure alternatively. A **router** is employed as the core of communication between
the controller of UR5e, Duet3D, and the laptop PC.

![hardware](/assets/img/curvedSupport/hardware.jpg){: .mx-auto.d-block :}

##### Contact:
Tianyu Zhang (tianyu.zhang-10@postgrad.manchester.ac.uk)
Charlie C.L. Wang (changling.wang@manchester.ac.uk)
