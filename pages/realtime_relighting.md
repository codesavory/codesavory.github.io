# Realtime Relighting Project

Exploring real-time relighting solutions combines techniques from graphics and augmented reality. Propose a real-time pipeline that captures an image and reconstructs the face in real-time and adds lighting solutions to give desired appearance.

Project [Website](https://docs.google.com/document/d/e/2PACX-1vQryCLg0MJVZhnu19qQ1SakHQMn0BWfSIRSxXwK9lXiuQUnomwxPcVkbjFj8jlJFKFXTN9U0i5lVvGa/pub) <br />
Code [GitHub](https://github.com/codesavory/mixed_and_augmented_reality/tree/main/realtime_face_relighting) <br />
Demo [Video](https://drive.google.com/file/d/1jw-2ubdyJqP-6OWHa0CNFCjAXUQYvmfa/view)

## Libraries Used
1. [MediaPipe](https://mediapipe.dev/) - 3D feature extraction of face mesh 
2. [Open3D](http://www.open3d.org/docs/release/introduction.html) - 3D point cloud to mesh reconstruction
3. [OpenCV](https://docs.opencv.org/master/index.html) - Computer Vision based image processing
4. [OpenGL](http://pyopengl.sourceforge.net/documentation/index.html) - Real-time graphics pipeline

## Screenshots

Feature extraction 3D cloud creation:
<img src="../images/realtime_relighting/Facemesh Relighting 15-03-2021 10_39_47 AM.png">

Point Cloud Visualization in OpenGL:
<img src="../images/realtime_relighting/Facemesh Relighting 15-03-2021 10_42_59 AM.png">

Surface Reconstruction using Open3D:
<img src="../images/realtime_relighting/Facemesh Relighting 15-03-2021 11_13_21 AM.png">

Relighting and overlay in OpenGL:
<img src="../images/realtime_relighting/Facemesh Relighting 14-03-2021 10_19_00 PM.png">
