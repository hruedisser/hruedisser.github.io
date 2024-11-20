---
layout: page
title: Flux Rope Modeling
description: Advancing CME Forecast using the 3D Coronal Rope Ejection Model
img: /assets/img/project2/3dcore_visual_en.png
importance: 2
category: science
related_publications: true
---

At the <a href="https://helioforecast.space/" target="_blank">Austrian Space Weather Office</a>, I am working with the semiempirical 3D flux rope model **3DCORE**  introduced by **Andreas Weiss** in <a href="https://iopscience.iop.org/article/10.3847/1538-4365/abc9bd" target="_blank">Weiss et al. 2021a</a>, <a href="https://www.aanda.org/articles/aa/abs/2021/12/aa40919-21/aa40919-21.html" target="_blank">2021b</a>.

<h2>Flux Rope Modeling and 3DCORE</h2>

Flux ropes are coherent magnetic structures embedded in **coronal mass ejections (CMEs)**. These structures are typically modeled as coherent magnetic flux ropes, allowing to reconstruct and predict their magnetic field configurations and trajectories through space. Understanding their behavior is key to predicting the impacts of solar eruptions. 

**3DCORE** builds on this concept by assuming:
- A **toroidal shape** with a Gold-Hoyle-like magnetic field.
- Self-similar expansion during propagation.
- Interaction with the solar wind modeled via a simple drag model.

The model includes parameters such as the CME’s launch velocity, magnetic decay rate, and aspect ratio to simulate complex effects like the flattening of flux ropes during propagation. While its simplicity enables real-time applications and large ensemble runs, limitations like a fixed flux rope width and constant solar wind speed require careful interpretation.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img src="/assets/img/project2/3dcore_insitu_en.png" alt="In Situ Reconstruction" class="img-fluid rounded z-depth-1" style="height: 180px; width: auto;">
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        <img src="/assets/img/project2/3dcore_visual_en.png" alt="3D Reconstruction" class="img-fluid rounded z-depth-1 small-img" style="height: 180px; width: auto;">
    </div>
</div>
<div class="caption">
    3DCORE Flux Rope Modeling
</div>
