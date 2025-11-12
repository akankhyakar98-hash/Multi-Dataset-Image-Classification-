# Multi-Dataset-Image-Classification-
A TensorFlow-based Convolutional Neural Network (CNN) built for highly accurate classification across 10 perfectly balanced and stratified animal image classes.
## Project Overview
This repository hosts a Convolutional Neural Network (CNN) designed to classify images of 10 distinct animal classes. The project focuses on building a highly optimized and balanced data pipeline using TensorFlow and a custom-defined CNN architecture. The core challenge addressed was creating a well-stratified dataset from a large source to ensure fair and accurate model training across all categories.
## Dataset Description :
The original source dataset was pre-processed using a custom Python script to achieve perfect class balance and a robust Train/Validation/Test split.
###1. Classes(10total)**
The model is trained to classify the following 10 classes: Canadagoose, RainbowLorikeets, blackswan, crane, echidnas, hummingbird,jacamar, koala, merganser,toucan
## 2. Dataset Split

| Split     | Image per class    |    Total Image |           Purpose                     |

|---------------------------------------------------------------------------------------  |

| Train     |    300             |    3000        |   Model training                      |

| Valid     |    100             |    1000        |Hyperparameter tuning and checkpointing|  

| Test      |     50             |    500         |Final, unbiased performance evaluation |                                                    


