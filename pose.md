## 3D Pose estimation for lymphedema patient therapy

**Project description:** In this on-going project (as part of [the Optimal Lymph Flow](https://optimallymph.org/) system), we are looking into the possibility to develop an monocular camera based human pose estiamtion system for automatic evaluation of patients' after surgery therapy exercises, which was previously realized with a [Mircrosoft Kinect](https://developer.microsoft.com/en-us/windows/kinect).

#### Preliminary evaluation with the [VideoPose3D](https://github.com/facebookresearch/VideoPose3D) models by FAIR

We evaluated the performance of the temporal convolution model introduced in [3D human pose estimation in video with temporal convolutions and semi-supervised training](https://arxiv.org/abs/1811.11742) on our pre-recorded lymphflow exercises. Some visualizations based on the VideoPose3D model are as followed. We modify the visualization codes to show the estiamted pose from 3 different angles:

<img src="images/3D-pose.png?raw=true"/>

<img src="images/3D-pose2.png?raw=true"/>

<img src="images/3D-pose3.png?raw=true"/>