---
title: Synthetic image-assisted deep learning framework for detecting defects
  during composite sheet layup
publication_types:
  - "1"
authors:
  - admin
  - Junyan Cheng
  - Reuben Levine
  - Vihan Krishnan
  - Jernej Barbic and Satyandra K. Gupta
featured: true
image:
  filename: featured.png

abstract: Automation of high-performance manufacturing processes such as prepreg composite layup has been gaining a lot of interest lately. Reliable and accurate defect detection methods play a crucial role in the automation of such processes to maintain the desired quality. The composite prepreg layup process involves manipulation of sheet-like material. Traditional machine vision-based defect detection techniques are inept in detecting defects for such complex processes due to the nature of the defects. Advanced defect detection techniques enabled by deep learning are the key for such applications. However, Deep learning usually requires an enormous amount of physical images of the process which is infeasible in high-mix manufacturing applications. In this paper, we resolve the data generation problem for deep learning by presenting an approach where with a combination of finite element-based simulation and advanced graphics techniques we generate a dataset of photorealistic images of the defects. Approximately, 10000 synthetic images are generated and combined with around 1000 images of real sheets to train a ResNeSt-based deep learning model. We have also devised an efficient 2-stage methodology for training the deep learning network to detect wrinkle-like defects. With the trained model and data augmentation techniques, our method can achieve a mean Average Precision (mAP) of 0.98 on actual production data for detecting defects. The code and the entire dataset are available at https://github.com/RROS-Lab/DeepSynthDefectDetector.

weight: 10
url_pdf: 'https://www.researchgate.net/publication/360722986_Synthetic_Image_Assisted_Deep_Learning_Framework_for_Detecting_Defects_During_Composite_Sheet_Layup'
url_code: 'https://github.com/RROS-Lab/DeepSynthDefectDetector'
url_dataset: 'https://drive.google.com/drive/u/3/folders/191EgISHWs6FH6FCKOSBTKoLQjo29bWh0'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
date: 2022-08-14T05:46:26.756Z
---
