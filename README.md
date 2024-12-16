# Mango Classifier using Machine Learning Model (YOLOv11)

This repository contains a machine learning project for classifying mango types using image data. The project employs YOLOv11 for object detection and classification, enabling efficient and accurate identification of 8 mango varieties.

This solution can be extended to other fruit classification tasks or serve as a baseline for agricultural applications involving image-based object detection.

## Project Overview

This project aims to classify mangoes into 8 different types using computer vision techniques. It leverages YOLOv11, a state-of-the-art object detection model, which has been fine-tuned on a dataset of mango images.

The system is capable of performing:

- Accurate identification of mango types from images.
- YOLO being a real-time object detection and classification algorithm, this model can be further implemented on a real-time basis.
- This project showcases the potential of machine learning in agriculture and can be adapted to other classification tasks.

## Features

- Multi-class Classification: Differentiates between 8 unique mango varieties.
- Efficient Preprocessing: The dataset was prepared with image orientation correction and manual labeling for accuracy.
- Real-time Inference: Optimized for quick classification on test images.
- Customizable: The pipeline can be extended to other datasets or models.

## Dataset

The dataset consists of high-quality images of mangoes, split into 8 classes:

Classes: Alphonso, Kesar, Dasheri, Himsagar, Banganapalli, Langra, Totapuri, Neelam
Images per Class: 200 (total 1,600 images)
Source: Images were collected from Kaggle(https://kaggle.com/) and labeled manually using Roboflow(https://roboflow.com/), ensuring balanced class distribution.
Preprocessing:
- Labeling: Images were labeled using a tool like LabelImg.
- Orientation Adjustment: Ensured all images are properly oriented to improve classification accuracy.

## Model Architecture

- Base Model: YOLOv11 (You Only Look Once, Version 11), fine-tuned for multi-class mango classification.

- Input Shape: Resized to 416x416 for YOLO compatibility.

- Loss Function: Combines classification and localization loss.

- Training on 100 Epochs

- Output: Bounding boxes and class probabilities for mango types.

- The model has been trained to detect and classify mangoes with high precision.

## Results
![results](https://github.com/user-attachments/assets/dc9f73cf-967e-49c1-9e31-aa022504c6ed)
![confusion_matrix](https://github.com/user-attachments/assets/a1f53198-1064-42c5-9d5e-f6a5a061b9a2)
![train_batch1](https://github.com/user-attachments/assets/b9a26af3-be91-4258-83dc-b2ae9ac4b76e)

## Contributors

1. Sanchit Pahurkar : [Github](https://github.com/sanchitpahurkar) [LinkedIn](https://www.linkedin.com/in/sanchit-pahurkar/)
2. Tanmay Talekar : [Github](https://github.com/tanmay-37) [LinkedIn](https://www.linkedin.com/in/talekar-tanmay/)
3. Rohit Garg : [Github](https://github.com/rohitgargRG) [LinkedIn](https://www.linkedin.com/in/rohit-garg-377b97244/)

## Conclusion

This project demonstrates the application of machine learning and computer vision in agriculture, specifically for the classification of mango types. By leveraging YOLOv11, we achieved a robust and efficient solution capable of distinguishing between 8 mango varieties with high accuracy.

The workflow—from dataset preprocessing to model training and evaluation—showcases a practical approach to solving real-world classification problems. The results highlight the potential of using image-based machine learning techniques in areas like quality control, inventory management, and automated sorting systems in the agricultural domain.

This project lays a strong foundation for future improvements, such as expanding the dataset, optimizing the model for edge devices, and integrating the system into mobile or web-based applications. By continuing this effort, we can further bridge the gap between AI research and its practical application in agriculture and beyond.
