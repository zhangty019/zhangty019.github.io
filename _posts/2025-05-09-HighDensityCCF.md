---
layout: post
title: High-Density Toolpath Generation for Continuous Carbon Fiber 3D Printing
subtitle: Composites Part B
thumbnail-img: /assets/img/HighDensityCCF/teaser.jpg
author: Tianyu Zhang
---


#### Overview

Continuous carbon fiber reinforced thermoplastic composites (CFRTPs) offer excellent mechanical performance for aerospace, automotive, and structural applications. However, 3D printing such materials with high fiber alignment and density remains a major challenge—especially in complex geometries.

Our team at the University of Manchester (UoM) presents a new toolpath generation method that significantly improves fiber alignment and placement density in multi-axis 3D printing of CFRTPs.
![pipeline](/assets/img/HighDensityCCF/pipeline.jpg)

----------

#### The Problem

Conventional fiber toolpaths often suffer from:

-   **Direction inconsistency**: Stress-based paths are hard to align due to vector ambiguity.
-   **Sparse fiber coverage**: Limited fiber density reduces reinforcement effects.
-   **Poor handling of complex regions**: Around holes or curved surfaces, paths break or misalign.

These issues limit mechanical performance and print reliability.

----------
![pipeline](/assets/img/HighDensityCCF/bladeRst.jpg)
#### Our Solution

We developed a **stress-guided, high-density toolpath algorithm** with three key features:

1.  **2-RoSy Direction Field**: Removes directional ambiguity, ensuring smooth, consistent fiber alignment along principal stresses.
2.  **Periodic Scalar Field**: Generates evenly spaced fiber paths for dense and uniform coverage.
3.  **Hole and Geometry Compatibility**: Supports complex structures by maintaining layer continuity and enabling fiber wrapping around holes.

##### [Source Code](https://github.com/zhangty019/HighDensity_ToolpathGene4CFRTP) is available!
----------

#### Results

We validated our method on various printed structures using an 8-DoF robotic 3D printer:

-   **Fiber coverage**: Up to **87.5%**, compared to 26% in previous methods.
-   **Tensile strength**: Increased by **84.6%**.
-   **Stiffness**: Improved by **54.4%**.
-   **Bending load capacity**: Boosted by **140.8%**.
    
Microscopy confirmed denser fiber layout and better bonding. All parts were printed with smooth, manufacturable toolpaths.
![pipeline](/assets/img/HighDensityCCF/experimentalRst.jpg)

----------

#### Applications & Outlook

This method enables more efficient and reliable 3D printing of CFRTPs—especially for parts with curved layers, holes, and stress-sensitive zones. It's ready for use in aerospace brackets, structural joints, and lightweight load-bearing designs.

Further improvements will focus on real-time sensing and adaptive path control to push fiber performance even further.

#### Contact:
Tianyu Zhang (zhangty019@gmail.com) 
