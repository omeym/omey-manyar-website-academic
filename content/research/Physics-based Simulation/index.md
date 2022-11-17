---
title: Physics-based Simulation
summary: Simulating deformable objects is a challenging problem. However, Physics-based differentiable simulators are powerful tools in robot motion planning. A differentiable simulator can be used to perform material parameter estimation for accurate simulation of objects under external forces and constraints.
tags:
  - Simulation
date: '2022-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  filename: featured.png
  caption: A proposed architecture for material parameter estimation for a deformable object to train a Physics-based differentiable simulator.
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This research focuses on developing differentiable simulators for deformable objects such as sheets. Once we train a model to accurately estimate the material parameters of the simulated object, we can leverage this simulation to perform robust robot motion planning and object manipulation.