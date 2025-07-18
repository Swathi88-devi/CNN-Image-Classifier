# CNN Performance Comparison on CIFAR-10 
This project compares two convolutional neural network (CNN) architectures — VGG16 and MobileNetV2 — using the CIFAR-10 dataset. 
It focuses on analyzing accuracy versus inference time and includes a lightweight Gradio app for real-time image classification (Dog vs Cat). 
# Overview:
Dataset used: CIFAR-10 (60,000 images in 10 classes) 
Models implemented: - VGG16 (trained from scratch on resized CIFAR-10 images) - MobileNetV2 (pretrained on ImageNet, used only for inference) 
Libraries and tools used: TensorFlow, Keras, Gradio, Matplotlib 
# Key Features: 
Mixed precision training used to improve speed and reduce memory usage. 
Data augmentation techniques applied to prevent overfitting. -
Accuracy and inference time compared between two models. -
A simple Gradio app was developed to classify dog/cat images using rotation-based testing for better real-world performance. 
# How to Run: 
1. Install dependencies
2. pip install tensorflow gradio matplotlib
3.Run the Python file: python major_2.py
4. Gradio interface will open in the browser for testing.
# Results: 
VGG16 achieved 86.63 percent test accuracy and took around 0.90 seconds to process 100 images.
MobileNetV2 achieved approximately 86.62 percent accuracy and took about 1.77 seconds to process 100 images. 
The MobileNetV2 model was faster on GPU, while VGG16 performed slightly better in accuracy. 
The trade-off between speed and performance is highlighted clearly. 
# Author: 
Project by P. Swathi Naga Devi
Under the guidance of Mr. Kanakata Venkateswara Rao 
Department of Electronics and Communication Engineering


