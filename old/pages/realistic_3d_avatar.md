# Realistic 3D Avatar Pipeline

Exploring a realistic 3D Avatar Pipeline combining state-of-the-art Neural Networks PIFu - Pixel Aligned Implicit Functions and RigNet - Neural Rigging of Articulated Characters and combining them with Pose Estimation and Mixamo Animations to create a realistic 3D duplicates/Avatars from Single Image and enabling rigging and animation capabilities.

Code [GitHub](https://github.com/codesavory/3d_avatar_pipeline) </br>

## Libraries Used - 
1. [PIFuHD](https://github.com/facebookresearch/pifuhd) - Takes a single Photo and produces a predicted 3D Mesh
2. [RigNet](https://github.com/zhan-xu/RigNet) - Takes a input mesh and predicts skeleton(joints and bones) and skinning
3. [OpenPose](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch) - Lightweight implementation of OpenPose for Pose Estimation
4. [Mixamo](https://www.mixamo.com/#/?page=1&type=Motion%2CMotionPack) - Adobe Mixamos Character Animations Kit
