---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Checkpointing in Practice for Memory-Efficient Training on the Edge"
summary: "Published In 2019 IEEE HPCC/SmartCity/DSS"
authors: []
tags: ["DL","ML","Systems"]
categories: []
date: 2019-03-15T00:00:00+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: IEEE Website
  url: https://ieeexplore.ieee.org/abstract/document/8855345
  # icon_pack: fab
  # icon: twitter

url_code: ""
url_pdf: ""
url_slides: "https://drive.google.com/file/d/15YciTEH3GTfgy3RJlJmdY4RC0_L0jDIt/view?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
- The research involved developing a novel and systematic method to enable the training of Deep Neural Networks such as ResNet, MobileNet, VGG, DenseNet, etc. on memory-constrained Edge devices.
- Performed experiments with training Deep Neural Networks in devices with 1GB RAM and was successfully able to run such Architectures in a Raspberry Pi Board, which was otherwise not possible.
- Optimized training of MobileNet and ResNet-18 architectures and thereby reduced memory consumption by a factor of 2.6 and 1.8 respectively without loss in predictive power.