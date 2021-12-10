# AI Powered Unmanned Aerial Vehicle (Autonomous-UAV-visual-navigation)

This project contains deep neural networks, computer vision and control code, hardware instructions and other artifacts that allow users to build a drone or a ground vehicle which can autonomously navigate through highly unstructured environments like forest trails, sidewalks, etc. Our TrailNet DNN for visual navigation is running on NVIDIA's Jetson embedded platform. The project's deep neural networks (DNNs) can be trained from scratch using publicly available data. 

A few [pre-trained DNNs](../master/models/pretrained/) are also available as a part of this project. In case you want to train TrailNet DNN from scratch, follow the steps on [this page](../../wiki/Models).

The project also contains [Stereo DNN](../master/stereoDNN/) models and runtime which allow to estimate depth from stereo camera on NVIDIA platforms.
