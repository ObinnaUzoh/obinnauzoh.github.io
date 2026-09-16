---
layout: page
title: Deep Learning for Computer Vision
description: A semantic segmentation project using deep learning and the Mapillary Vistas dataset.
img: assets/img/semantic-segmentation-cover.png
importance: 1
category: machine learning

github: https://github.com/ObinnaUzoh/mapillary-semantic-segmentation

related_publications: false
---

## Overview

This project documents my journey into semantic segmentation, a computer vision task that assigns a class label to every pixel in an image. Unlike image classification or object detection, semantic segmentation produces a dense pixel-level understanding of a scene, making it useful for applications such as autonomous driving, medical imaging, and geospatial analysis. :contentReference[oaicite:0]{index=0}

The project focuses on understanding semantic segmentation workflows, dataset preparation, model training, evaluation, and visualization using the Mapillary Vistas dataset.

## Motivation

My goal was to gain hands-on experience with modern computer vision techniques and understand how deep learning models can perform scene understanding at the pixel level.

Key objectives included:

- Learning semantic segmentation fundamentals
- Working with large-scale annotated datasets
- Building and training segmentation models
- Evaluating segmentation quality using standard metrics
- Visualizing predictions and model outputs

## Dataset

The project uses the Mapillary Vistas dataset, which contains street-level imagery with detailed pixel-wise annotations across multiple semantic classes.

## Methodology

The workflow consisted of:

1. Data preprocessing and label preparation
2. Model architecture selection
3. Training and hyperparameter tuning
4. Validation and performance evaluation
5. Visualization of segmentation outputs

Semantic segmentation models typically use encoder-decoder architectures that combine contextual understanding with fine-grained spatial information. :contentReference[oaicite:1]{index=1}

## Results

The trained model successfully learned pixel-level scene understanding and produced segmentation masks for roads, buildings, vegetation, vehicles, and other scene elements.

Key outcomes:

- End-to-end semantic segmentation pipeline
- Automated data processing workflow
- Model training and evaluation framework
- Visualization tools for prediction analysis

## Lessons Learned

This project provided practical experience in:

- Deep learning for computer vision
- Dataset engineering
- Model debugging and optimization
- Evaluation metrics for segmentation
- Scientific project development

## Links

- Medium Article: https://medium.com/@uzohchinedu/deep-learning-for-computer-vision-my-journey-into-semantic-segmentation-45b9d0491d0f
- GitHub Repository: https://github.com/ObinnaUzoh/mapillary-semantic-segmentation
