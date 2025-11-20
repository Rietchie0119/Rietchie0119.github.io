---
title: "Location classification"
excerpt: "Location classification using different methods" # 간략한 설명
collection: projects
image: portfolio-1.jpg # 표시할 이미지 파일명
date: 2023-12-01
---

## Project Description
This work focuses on image recognition of different locations using feature descriptors and a Support Vector Machine (SVM) classifier. The entire scheme is divided into four main parts: feature extraction, Principle Component Analysis (PCA) for vocabulary, Bag of Words (BoW)/Spatial Pyramid representation, and multi-class SVM classification. The system was trained on 1500 images across 15 categories (100 images per category).

![Hybrid_Image]( /images/projects/pca_projection.png )

*Dimensions with high variance (high eigenvalues) are chosen to form the final, lower-dimensional features (e.g., 2D or 3D for visualization)*

![performance]( /images/projects/performance_comparison.png )

*Performance between different methods*