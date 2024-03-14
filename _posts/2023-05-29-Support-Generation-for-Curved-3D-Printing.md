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

![printing_result](/assets/img/curvedSupport/printing_result.gif)


## Pipeline
### Computational domain generation from support envelop hull;
### Compatible curved support layers generation;
### Tree-like support skeleton calculation;  
### Implicit solid construction;
### Support region extraction; 

![pipeline](/assets/img/curvedSupport/pipeline.jpg){: .mx-auto.d-block :}

## Dual-material Robot-assisted 3D Printing System.
### Filaments alternately pass through Y-shape structure.

![hardware](/assets/img/curvedSupport/hardware.jpg){: .mx-auto.d-block :}



If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
