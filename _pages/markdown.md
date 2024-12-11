---
permalink: /markdown/
title: ""
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Research Projects
### [Semi-Supervised Object Detection with CAGE Pseudo-Labeling](https://github.com/JayGC/Semi-Supervised-Object-Detection-with-CAGE-Pseudo-Labeling)
Research project with [Prof. Ganesh Ramkrishnan](https://www.cse.iitb.ac.in/~ganesh/)

Object detection models heavily rely on large, labeled datasets, which are often expensive and time-consuming to create. This dependence limits their scalability and effectiveness, particularly in domains where labeled data is scarce or unavailable. Without sufficient labeled data, these models struggle to achieve the accuracy and generalizability needed for real-world applications.

To address the reliance on labeled data, our project employs a semi-supervised learning framework using CAGE (Continuous and Quality-Guided Labeling Functions) and pseudo-labeling techniques. CAGE integrates predictions from multiple deep learning models, such as ResNet and VGG-16, to generate robust and accurate pseudo-labels. These pseudo-labels allow us to train object detection frameworks like Faster R-CNN on unlabeled data. By leveraging joint learning, we optimize the pseudo-labeling process and the detection model simultaneously. This approach enhances scalability, improves accuracy, and enables effective object detection in scenarios where labeled datasets are scarce or unavailable.

### Threshold-Based Optimal Arm Selection in Structured Bandit Problems
B.Tech thesis project with [Prof. Prasanna Chaporkar](https://www.ee.iitb.ac.in/web/people/prasanna-chaporkar/)

In communication systems, ensuring efficient resource allocation while maintaining performance is a critical challenge. The problem lies in determining the optimal amount of resources required to guarantee that the average loss remains below a specified threshold. Striking this balance is essential to optimize system performance without over-provisioning.

To address the resource allocation challenge, we model the problem as a multi-armed bandit framework, where each CQI (Channel Quality Indicator) value (0-15) represents an arm. We designed an algorithm to identify the optimal arm—the one that achieves an average loss just below the specified threshold. Additionally, we are working on proving the optimality of the algorithm.

### 3D Reconstruction of Oral Cavity from Intraoral Camera Images
I am currently working with [Prof. Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/) on developing a system for 3D reconstruction of intraoral videos for medical applications. The project aims to create detailed 3D models of the oral cavity from video data captured during examinations. By addressing challenges such as motion artifacts and lighting variations, we strive to enable accurate reconstructions that can enhance diagnostics and treatment planning in dentistry and oral healthcare.

## Internships

### ML intern @ Atomberg

During my winter internship at Atomberg Technologies Private Limited, Pune, I worked on an advanced machine learning project focused on fan detection and classification. I implemented YOLO for high-precision fan detection, optimizing parameters for real-time performance, and extensively tested YOLOv5 and YOLOv7 to achieve excellent detection metrics. For classification, I utilized Vision Transformers (ViT), fine-tuning the model on a large dataset to improve accuracy. I also developed an integrated pipeline combining YOLO and ViT, incorporating data preprocessing and augmentation techniques to enhance workflow efficiency.

### Research Intern @ A*star Research Agency, Singapore


During the summer of my third year, I was a research intern at A*STAR Research, Singapore, under the guidance of [Dr. J. Senthilnath](https://research.a-star.edu.sg/researcher/j-senthilnath/), focusing on implementing advanced methodologies for 3D molecule generation and multi-property optimization. While my primary contributions were on the implementation side—extending single-property geometric diffusion techniques to multi-property optimization and integrating spectral normalization and molecular constraints for training stability—I also contributed conceptually by designing a novel loss function to enforce chemical validity, which significantly improved model performance. Additionally, I developed an architecture incorporating GNNShap for ante-hoc explainable AI, ensuring interpretability and transparency during training and predictions.

Our work, **“XMOL: Explainable Multi-property Optimization of Molecules”** is currently under review at ICASSP 2025.


