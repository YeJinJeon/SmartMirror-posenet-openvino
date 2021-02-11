# SmartMirror-posenet-openvino
뇌졸중 가정재활을 보조하는 AI 스마트 미러 프로젝트

## Installation
1. Tensorflow 3.7
2. Django
> python -m pip install Django
3. Picamera module
> easy_install -U picamera
4. [openvino for Window 10](https://docs.openvinotoolkit.org/latest/openvino_docs_install_guides_installing_openvino_windows.html#Using-Demo-Scripts, "install openvino for window 10")

## Hardware Design
![raspberry](https://user-images.githubusercontent.com/46892916/107644232-866ded00-6cba-11eb-906b-02e4053565b3.png)
![smart-mirror](https://user-images.githubusercontent.com/46892916/107644265-8ff75500-6cba-11eb-96bf-50b5046e01b3.png)

## Running
> python manage.py runserver

## Demo
<img src="https://user-images.githubusercontent.com/46892916/107648003-275ea700-6cbf-11eb-8779-43e14b174520.PNG" width="680px" height="500px" alt="Demo-video"></img><br/>
![Demo Video](https://user-images.githubusercontent.com/46892916/107647493-8d96fa00-6cbe-11eb-9d9c-d01e2d1d79bb.mp4)

## reference
* [Posenet-python Github repository](https://github.com/rwightman/posenet-python)
* [Github repository to run inference on RPi](https://github.com/Oviyum/openvino-posenet)
* [Real-time Pose-estimation on the Rpi with Movidius NCS and Openvino](https://medium.com/@oviyum/real-time-human-pose-estimation-on-the-edge-with-movidius-ncs-and-openvino-ac3b13536)
