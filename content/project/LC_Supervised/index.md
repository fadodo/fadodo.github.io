---
title: Supervised Landcover Classification of Sentinel2 imagery over Corse region
date: 2025-05-10
external_link: https://troopl.com/fadodo/supervised-landcover-classification-of-sentinel2-imagery-over-corse-region
tags: 
  - Google Colab, Google Earth Engine, Python, Random Forest, Remote sensing, Sentinel-2 imagery, Supervised classification algorithm, Support Vector Machine(SVM)
---

# Supervised landcover classification

Comparison of 2 supervised models for Land cover use classification from Sentinel 2 imagery over Corse region. 

- ee.Classifier.smileRandomForest() - An ensemble learning method that builds multiple decision trees and aggregates their predictions through majority voting.

- ee.Classifier.libsvm() - Support Vector Machine (SVM) using LIBSVM library : A powerful supervised learning algorithm that finds the optimal hyperplane to separate different classes in a high-dimensional feature space. It can use various kernel functions (e.g., linear, radial basis function (RBF), polynomial) to handle non-linear relationships.


In many geospatial land cover classification studies, Random Forest has become a popular and often highly effective choice due to its balance of accuracy, efficiency, and ease of use. 
However, SVM can also be a strong contender, especially when dealing with complex spectral signatures and with careful parameter optimization.

Core techs skills:
- Platform: Google Earth Engine (GEE)
- Imagery Data: Sentinel-2
- Primary Programming Language: Python 
- Python : geemap, ee
Development Environment: google colab

## Results:
In this project, model evaluation has shows that the Random Forest model provides the best perfomance of 73% over SVM (66%).

<!--more-->
