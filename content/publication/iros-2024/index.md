---
title: Simulation-Assisted Learning for Efficient Bin-Packing of Deformable Packages in a Bimanual Robotic Cell
publication_types:
  - "1"
authors:
  - admin
  - Hantao Ye
  - Meghana Sagare
  - Siddharth Mayya
  - Fan Wang
  - Satyandra K.Gupta

publication: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
draft: false
featured: true
doi: ""
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false

abstract: Bin-packing is an important problem in the robotic warehouse domain. Traditionally, this problem has been studied only for rigid packages (e.g., boxes or rigid objects). In this work, we tackle the problem of bin-packing with deformable packages that have become a popular choice for fulfillment needs. We present a system that incorporates a dual robot arm bimanual setup, uniquely combining suction and sweeping motions to stably and reliably pack deformable packages in a bin. Additionally, we propose a comprehensive action prediction framework to optimize for bin-packing efficiency by predicting optimal actions for both robots involved. Our methodology leverages a two-pronged learning strategy, where initially, we train a model in a self-supervised manner to predict a scoring metric indicative of bin-packing efficiency and then leverage an online optimization scheme to compute optimal actions in real time. The model is pre-trained in simulation in MuJoCo and fine-tuned on small-scale real-world data. Our packing score prediction model predicts bin-packing score with an MSE of 0.003. Real-world experiments validate our method's adaptability to novel scenarios and its effectiveness in packing operations. 

url_pdf: 'https://sites.google.com/usc.edu/bimanual-binpacking/paper'

date: 2024-6-15T06:11:25.994Z
---
