---
title: 'Synthetic image-assisted deep learning framework for detecting defects during composite sheet layup'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Junyan Cheng
  - Reuben Levine
  - Vihan Krishnan
  - Jernej Barbic
  - Satyandra K. Gupta

# Author notes (optional)
author_notes: ''

date: '2022-11-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ASME IDETC Computers and Information in Engineering Conference 2022*
publication_short: In *ASME IDETC-CIE 2022*

abstract: Automation of high-performance manufacturing processes such as prepreg composite layup has been gaining a lot of interest lately. Reliable and accurate defect detection methods play a crucial role in the automation of such processes to maintain the desired quality. The composite prepreg layup process involves manipulation of sheet-like material. Traditional machine vision-based defect detection techniques are inept in detecting defects for such complex processes due to the nature of the defects. Advanced defect detection techniques enabled by deep learning are the key for such applications. However, Deep learning usually requires an enormous amount of physical images of the process which is infeasible in high-mix manufacturing applications. In this paper, we resolve the data generation problem for deep learning by presenting an approach where with a combination of finite element-based simulation and advanced graphics techniques we generate a dataset of photorealistic images of the defects. Approximately, 10000 synthetic images are generated and combined with around 1000 images of real sheets to train a ResNeSt-based deep learning model. We have also devised an efficient 2-stage methodology for training the deep learning network to detect wrinkle-like defects. With the trained model and data augmentation techniques, our method can achieve a mean Average Precision (mAP) of 0.98 on actual production data for detecting defects. The code and the entire dataset are available at: https://github.com/RROS-Lab/DeepSynthDefectDetector.

# Summary. An optional shortened abstract.
summary: ''.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/360722986_Synthetic_Image_Assisted_Deep_Learning_Framework_for_Detecting_Defects_During_Composite_Sheet_Layup'
url_code: 'https://github.com/RROS-Lab/DeepSynthDefectDetector'
url_dataset: 'https://drive.google.com/drive/u/3/folders/191EgISHWs6FH6FCKOSBTKoLQjo29bWh0'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
