---
title: "Autonomous robotic screwdriving for high-mix manufacturing"
authors:
- admin
- Rutvik Patel
- Satyandra K. Gupta

date: "2025-22-10T00:00:00Z"
doi: "https://doi.org/10.1016/j.rcim.2025.103172"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Robotics and Computer-Integrated Manufacturing*"
publication_short: ""

abstract: Screwdriving is a crucial task routinely performed during assembly, yet most of the current automation techniques are focused on mass manufacturing environments where there is typically low part variability. However, a substantial portion of manufacturing falls under high-mix production that entails significant uncertainties due to limited fixtures and cost constraints on tooling, making them predominantly manual. In this paper, we present an autonomous mobile robotic screwdriving system suitable for high-mix, low-volume manufacturing applications and designed to operate under semi-structured conditions, handling hole pose uncertainties of up to 4 mm/3°in the hole pose. To enhance decision-making and operational efficiency, we develop a physics-informed machine-learning model that predicts nonlinear screw-tip dynamics in Cartesian space. Additionally, we propose a decision tree-based failure detection framework that identifies four distinct failure modes using force signals from the robot’s end effector. We further introduce a novel fifth failure mode, a time-based threshold for unsuccessful insertions, where our dynamics model is used to determine when to reattempt screwdriving. This integration of predictive modeling, real-time failure detection, and alert generation for human-in-the-loop decision-making improves system resilience. Our failure detection method achieves an F1-score of 0.94 on validation data and a perfect recall of 1.0 on testing. We validate our approach through screwdriving experiments on 10 real-world industrial parts using three different screw types, demonstrating the system’s robustness and adaptability in a high-mix setting.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.researchgate.net/publication/397427698_Autonomous_Robotic_Screwdriving_for_High-Mix_Manufacturing'
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
  filename: featured.jpg
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