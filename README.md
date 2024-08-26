# human_intervention_detection_on_tracks
A computer vision project using YOLO architecture

## Overview
This project focuses on developing a real-time object detection system to identify human presence on railway tracks. The system is built using the YOLO (You Only Look Once) model and a custom dataset. The goal is to enhance railway safety by enabling timely alerts when humans are detected on tracks, thereby preventing accidents. This work has been published in an IEEE conference.

## Features
- Real-Time Detection: Detects human intervention on railway tracks with minimal latency.
- Custom Dataset: Utilizes a dataset specifically collected and annotated for this task.

## Dataset
The dataset consists of images of railway tracks with and without human presence, annotated with bounding boxes. It includes a variety of weather conditions, angles, and lighting situations to ensure robust detection.
This dataset is also available on Kaggle.
<br>https://www.kaggle.com/datasets/ravikiranaithal/human-intervention-detection-on-tracks<\br>

## Model
The project leverages the YOLOv8 architecture for real-time object detection. The model was trained on the custom dataset using transfer learning, starting from pre-trained weights on the COCO dataset.
