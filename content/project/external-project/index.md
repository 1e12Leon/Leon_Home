---
title: UAV-LODBoost
summary: A User-Friendly Toolkit for UAV Light-weighting Object Detection.
tags:
  - UAV Object Detection
date: "2023-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Toa Heftiba on Unsplash
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: UAV-LODBoost
    url: https://github.com/1e12Leon/UAV-LODBoost
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

一个通用的工程级别目标检测框架，包含但不限于：

一套目标检测数据增强与扩充代码。它将是一个一直在持续维护的代码库，将不断添加有效的特殊数据增强方法。

一种样本筛选方法。它将通过深度特征来有效聚类，用于剔除数据增强后的无效样本。

一套目标检测与跟踪模型。它使用较为热门的yolov7以及ByteTrack，能够胜任工程中常见的检测与跟踪任务。

一套模型压缩框架。它将有效集成剪枝、蒸馏、量化的方法压缩目标检测模型，提升推理速度的同时尽可能减少精度损失。

一个模型部署示例。它将演示如何部署模型至嵌入式开发板，可有效应用于无人机等小型设备。
