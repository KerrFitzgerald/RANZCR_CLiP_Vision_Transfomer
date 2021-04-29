# RANZCR_CLiP_Vision_Transfomer
Kaggle RANZCR CLiP - Catheter and Line Position Challenge: Vision Transformer Results

This repository contains my Kaggle notebooks for the Kaggle RANZCR (Royal Australian and New Zealand College of Radiologists) Challenge: https://www.kaggle.com/c/ranzcr-clip-catheter-line-classification

The aim of the challenge was to detect the presence and position of catheters and lines on chest x-rays and use machine learning to train and test models on 40,000 images to categorize whether one or multiple tubes need from an image need repostioning.

PyTorch was used to enable pre-trained (on ImageNet) Vision Transformer (ViT) networks and hybrid ViT-ResNet networks to perform multi-label classification on chest X-ray images. The pre-trained models are available at: https://github.com/rwightman/pytorch-image-models

The implemented ViT networks used image patch sizes of 16x16 pixels with the overall image size being set at 384x384 pixels. My team acheived 82.7% classification accuracy.

![kaggle](https://user-images.githubusercontent.com/60627318/116559405-5668da00-a8f8-11eb-9b32-81f38e534b6e.png)
