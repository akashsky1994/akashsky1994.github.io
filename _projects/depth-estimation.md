---
title: "Depth Estimation using Self-Supervised Learning from Monocular Images"
collection: projects
# permalink: /projects/depth-estimation
excerpt: 'Depth Estimation using Self-Supervised Learning from Monocular Images'
paperurl: 'http://akashsky1994.github.io/files/ssl-monocular-depth-estimation.pdf'
---
Researched and trained a self-supervised learning model for depth estimation on KITTI dataset by experimenting with various
iterations of UNet Architecture involving Encoders (ResNet, ConvNext ) and Up-sampling decoders like ESPCN achieving a rms of 3.7

Enhanced our model using Mask R-CNN pretrained on COCO Dataset to get semantic map which helped us reduce artifact problem
in the disparity map and consequently reducing the overall loss for the model to 3.485

[Download paper here](http://akashsky1994.github.io/files/ssl-monocular-depth-estimation.pdf)