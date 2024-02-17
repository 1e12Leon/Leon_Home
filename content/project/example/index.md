---
title: ProbDet
summary: 基于概率决策融合的多模态目标检测
tags:
  - Object Detection
date: '2022-10-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: ProbDet
    url: https://github.com/1e12Leon/ProbDet
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
    

**基于概率决策融合的多模态目标检测**
本项目借鉴了Bayes规则和假设条件独立性的基本原理，设计了一种类似集成学习的检测器决策融合技术，不需要大量成对的多模态数据进行训练，仅利用在大规模单模态数据集上训练的高度调谐的单模态检测器即可拥有强大的检测性能；此外，本方法还通过概率边缘化处理特定模态的缺失检测，显著改善了检测效果。具体而言，通过匈牙利算法匹配不同模态检测器的输出结果，对匹配成功的目标框进行置信度与目标框融合，以基于贝叶斯先验实现置信度的有效提升；对匹配失败的目标框，将概率归一化的多模态后验直接与单模态后验进行比较，以实现跨模态的信息互补。
