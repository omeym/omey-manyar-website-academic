---
title: "An adaptive framework for robotic polishing based on impedance control"
authors:
- Srinivasan Lakshminarayanan
- Sreekanth Kana
- Dhanya Menoth Mohan
- admin
- David Jin Hong Then
- Domenico Campolo

date: "2021-01-11T00:00:00Z"
doi: "10.1007/s00170-020-06270-1"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*The International Journal of Advanced Manufacturing Technology*"
publication_short: ""

abstract: Precise finishing operations such as chamfering and filleting are characterized by relatively low contact forces and low material removal. For such processes, conventional automation approaches like pre-programmed position or force control without adaptations are not suitable to obtain fine surface finishing with high profile accuracy. As a result, polishing tasks are still mainly carried out manually by skilled operators. In this paper, we propose an adaptive framework capable of polishing a wide range of materials including hard metals like titanium using a collaborative robot. We propose an iterative learning controller based on impedance control that adapts both position and forces simultaneously in each iteration to regulate the polishing process. The proposed controller can track the desired profile without any a priori knowledge of the forces required to polish different materials. In addition, we introduce a novel mathematical model to generate the complex filleting toolpath based on Lissajous curves. Trials are carried out in finishing tasks such as chamfering and filleting using a collaborative industrial robot to validate the novel framework. Surface roughness and profile measurements show that our adaptive controller can obtain fine polishing output in various materials such as titanium, aluminum, and wood

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://link.springer.com/article/10.1007/s00170-020-06270-1'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  filename: featured.png
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---