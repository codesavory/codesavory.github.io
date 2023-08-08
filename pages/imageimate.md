# IMAGEimate - An end-to-end pipeline to create realistic animatable 3D Avatars from a Single Image using Neural Networks

This work presents an end-to-end pipeline that coverts a single RGB image into realistic animatable 3D avatar which can be used to easily create virtual humans in VR and AR applications such as Adobe AERO. This project stiches together existing neural networks techniques to solve the subproblems in this domain - 1. Image to Mesh, 2. Mesh Rigging and Skinning and 3. applies them to re-pose meshes and apply animations.

[Paper at VRST ’21 Conference](https://dl.acm.org/doi/10.1145/3489849.3489922) <br />
[GitHub Code](https://github.com/codesavory/IMAGEimate) <br />
[Project Slides](https://docs.google.com/presentation/d/e/2PACX-1vQjt8FaWkltp1aldvHQCR8yImoDDxsk62-xEmip2vNbMrb4zetaYLo4_h3FirjTTnzbRny9xYJUCnLt/pub?start=false&loop=false&delayms=3000) <br />
<!--[Project Poster submitted to VRST,'21](https://drive.google.com/file/d/11WOzRYf7ykGX25FbR1K_0fOE4qRjq8ru/view)-->

## Showing the stages of IMAGEimate Pipeline
![Teaset_pipeline_with_Aero](https://user-images.githubusercontent.com/5894273/131004242-79263b6f-b09d-4b79-900b-a348f9dd9085.png)
Results of each stage in the pipeline: A) Input RGB image <br/>
B) Predicted 3D mesh using PIFuHD<sup>1</sup> <br/>
C) Parametric model fit using IPNet<sup>2</sup>  <br/>
D) Reposed mesh from AIST++<sup>3</sup> Pose <br/>
E) Augmented using [Adobe Aero](https://www.adobe.com/products/aero.html) and textured using [Substance Painter](https://www.substance3d.com/) <br/>

### References
1: PIFuHD : Multi-Level Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization (CVPR 2020) - [https://shunsukesaito.github.io/PIFuHD/](https://shunsukesaito.github.io/PIFuHD/) <br />
2: IPNet : Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction (ECCV 2020) - [https://virtualhumans.mpi-inf.mpg.de/ipnet/](https://virtualhumans.mpi-inf.mpg.de/ipnet/) <br />
3: AIST++ : Learn to Dance with AIST++: Music Conditioned 3D Dance Generation (CVPR 2021）- [https://google.github.io/aichoreographer/](https://google.github.io/aichoreographer/) <br />
