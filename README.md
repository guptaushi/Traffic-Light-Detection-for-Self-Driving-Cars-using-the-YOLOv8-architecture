# Traffic-Light-Detection-for-Self-Driving-Cars-using-the-YOLOv8-architecture
Overview
This repository contains the code and documentation for our project on traffic light detection for self-driving cars using the YOLOv8 architecture. 

Abstract
Traffic light violations are a significant cause of traffic accidents, and developing reliable and efficient traffic light detection systems is crucial for autonomous vehicle safety. This study evaluates the performance of YOLOv8, a state-of-the-art object detection model, against other YOLO models (YOLOv3 and YOLOv7) using a dataset of 100,000 images captured in various weather and lighting conditions. Our goal is to create a data-driven system that achieves high detection accuracy and performance during both training and real-time detection. This study is the first to comprehensively evaluate YOLOv8 for traffic light detection in autonomous vehicles.

Introduction
Advanced Driver Assistance Systems (ADAS) aim to provide drivers with crucial information about traffic signs and signals. An accurate traffic signal detection system can significantly enhance driving safety and comfort by warning drivers of approaching signals. The main challenges in traffic signal recognition (TSR) include low resolution, poor picture quality, adverse weather conditions, and constrained memory and computing power in real-world applications like ADAS.

Dataset
The dataset comprises 100,000 images captured under various conditions. It includes roughly 700 green light images, 1000 red light images, and 150 yellow light images. The dataset accurately represents real-world scenarios where yellow lights are less frequent than red and green lights.

Model and Training
We used the YOLOv8 architecture for this project, leveraging its efficiency in speed and precision due to recent advancements in deep learning and computer vision. The YOLOv8 model is compared with YOLOv3 and YOLOv7 to evaluate performance. The training and validation processes are iterated until a stable loss function is achieved, followed by performance evaluation on a testing dataset.

Performance Evaluation
Precision: 96.22%
Recall: 81.42%
mAP50: 93.93%
Inference Speed: 4.5 milliseconds per image

Results and Observations
The YOLOv8 model demonstrated superior performance in terms of inference speed and accuracy, making it well-suited for real-time applications like autonomous driving. The model's high precision and recall rates suggest excellent accuracy in detecting traffic lights.
