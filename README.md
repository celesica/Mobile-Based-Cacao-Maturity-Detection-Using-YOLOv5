<div align="center">

# Mobile-Based Nondestructive Identification of<br>Cacao's Maturity Using Object Detection

![Static Badge](https://img.shields.io/badge/yolov5-v7.0-024ff5) ![Static Badge](https://img.shields.io/badge/pytorch-2.0.1%2Bcu118-ee4d24) ![Static Badge](https://img.shields.io/badge/tensorflow-v2.12.0-ff8601) ![Static Badge](https://img.shields.io/badge/roboflow-annotation-812cdb) ![Static Badge](https://img.shields.io/badge/android_studio-Giraffe%20%7C%202022.3.1-9cbe45)

</div>
This project was developed as part of the author's Computer Science thesis and introduces a mobile-based solution to identify the maturity of UF18 cacao pods nondestructively using the YOLOv5 object detection algorithm. After training, the model was exported to TensorFlow Lite to be incorporated into an Android-based mobile app.

## Features:
- Nondestructive Real-time detection and identification of Cacao's Maturity via mobile app
- Maturity categorization: Ripe, Unripe, and Infected

![cacao-pods](https://github.com/celesica/Mobile-Based-Cacao-Maturity-Detection-Using-YOLOv5/assets/10039521/27a43ada-a05f-4717-9532-ed924dfc5f0f)


## Development Environment:
- Google Colab
  - GPU: Tesla V100-SXM2-16GB
  - High-RAM with CUDA 11.8
- YOLOv5 Algorithm
- PyTorch 2.0.1+cu118
- Tensorflow  v2.12.0
- Android Studio Giraffe 2022.3.1
- Comet ML for Visualization

## UF 18 Cacao Dataset
Download the Dataset here: [UF18 Cacao Maturity Computer Vision Project](https://universe.roboflow.com/thesiscacaov1/uf18-cacao-maturity)

**Dataset's Health and Class Balance**

![health-check](https://github.com/celesica/Mobile-Based-Cacao-Maturity-Detection-Using-YOLOv5/assets/10039521/618d61b6-fa9e-4216-890a-28933e20ae9a)


## Repository Contents:
- YOLOv5 custom training notebook tutorial integrated with Google Colab.
- Mobile app Android source code modified from this [GitHub Repository](https://github.com/AarohiSingla/TFLite-Object-Detection-Android-App-Tutorial-Using-YOLOv5/tree/main).

## Metrics
View the training metrics via Comet ML here: [Cacao Maturity Detection Experiment](https://www.comet.com/celesica/cacao-maturity-detection/view/new/experiments)

![image](https://github.com/celesica/Mobile-Based-Cacao-Maturity-Detection-Using-YOLOv5/assets/10039521/a0d1f30b-0725-4e3a-8c5d-00a5e06c9c6f) 




## Detection Sample
![detection-sample](https://github.com/celesica/Mobile-Based-Cacao-Maturity-Detection-Using-YOLOv5/assets/10039521/57e88c88-9e4f-47f4-98bd-a50f398eb894)

