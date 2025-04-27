---
layout: page
title: Sparse Supervision for Remote Sensing Segmentation
description: Semantic segmentation of satellite images with minimal labeled data.
img:  # no image for now
importance: 1
category: work
giscus_comments: false
---

Developed a semantic segmentation model for satellite imagery under sparse supervision.

- Built a DeepLabV3+ model with ResNet-50 as the backbone.
- Trained using Partial Cross-Entropy Loss to handle sparse point annotations.
- Achieved 0.43 mean Intersection over Union (mIoU) with only 1% labeled data.
- Conducted experiments at multiple label densities (1%, 5%, 10%) to assess performance scaling.
- Used DeepGlobe dataset and visualized segmentation outputs under low annotation settings.

➡️ [View Project on GitHub](https://github.com/mahmoudmokhiamar/Sparse-Remote-Sensing-Images-Semantic-Segmentation)