# Pallet Segmentation & Detection Pipeline
Deep Learning Models for Autonomous Warehouse Robotics

This repository contains the full pipeline for evaluating ground segmentation and pallet detection models using the EuroPalletSeg dataset.
The project compares four architectures:

U-Net – baseline segmentation

DeepLabV3+ (MobileNetV3) – lightweight segmentation

YOLOv8 – high-performance pallet detector

EfficientDet-D0 – compact detector model

All results, preprocessing scripts, inference pipelines, and comparison notebooks are included.

##  Repository Structure

pallet-segmentation-detection-pipeline/
│
├── Code/
│   ├── Comparing_Models_Seg_ObjDet.ipynb
│   ├── GROUND_SEGMENTATION_EFFICIENTNETB3_*.ipynb
│   ├── TWO_PALLET_DETECTION_YOLOv8.ipynb
│   └── deeplab_efficientdet_pipeline.py
│
├── Documents/
│   ├── CIS583_Deep_Learning_Project_Report.pdf
│   ├── CIS583_Deep_Learning_Project_Slides.pdf
│   ├── Additional_Project_Notes.pdf
│   └── Any_other_supporting_docs.pdf
│
└── README.md

##  Clone repository:
git clone https://github.com/1Mike-e/pallet-segmentation-detection-pipeline.git

##  Authors

Aksheya Kannan Subramanian

Michael Acquah

Faten Alshohatee

### Project completed for CIS 583 – Deep Learning
