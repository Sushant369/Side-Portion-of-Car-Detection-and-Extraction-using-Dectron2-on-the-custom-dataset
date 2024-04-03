# Side Portion of Car Detection Using Detectron2

![Output - Detection and Mask](https://github.com/Sushant369/Side-Portion-of-Car-Detection-and-Extraction-using-Dectron2-on-the-custom-dataset/assets/72655705/72619101-13ca-4214-85ce-141c33537c65)

## Overview
This project focuses on the detection of the side portions of cars using the Detectron2 framework, a state-of-the-art object detection and segmentation library by Facebook AI Research (FAIR). Designed to demonstrate advanced vehicle detection techniques, this project applies deep learning models to accurately identify car side profiles in various environments.

## Features
- Advanced Car Detection: Implements Detectron2 to detect the side portions of cars, showcasing the application of cutting-edge object detection methodologies.
- Deep Learning Models: Utilizes pre-trained models within Detectron2, fine-tuned for the specific task of car side detection, ensuring high accuracy and efficiency.
- Real-World Application: Aims to enhance automotive safety and surveillance systems by improving vehicle detection under diverse conditions.

## Prerequisites
- Python 3.7+
- Detectron2
- PyTorch
- CUDA-compatible GPU for model training and inference acceleration

## Technical Details
### Model Training and Segmentation
This project extends Detectron2’s capabilities to not only detect but also segment the side portions of cars, enabling precise extraction of these parts for further analysis. Training and fine-tuning are conducted on a carefully curated dataset, emphasizing the side profiles of vehicles with advanced data augmentation and CUDA acceleration for efficiency.

## Challenges Addressed
A significant challenge was ensuring the model's robustness against variations in lighting and background conditions, critical for accurate segmentation. This was systematically addressed through extensive dataset enhancement and model refinement.
