---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Introducing Inter-Relatedness between Wikipedia Articles in Explicit Semantic Analysis"
summary: "Course: Natural Language Processing​ | ​Advisor: Dr. Sutanu Chakraborti, CSE, IIT Madras"
authors: []
tags: ["NLP","ML"]
categories: []
date: 2020-05-15T01:00:00+05:30

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
- name: Paper
  url: https://arxiv.org/pdf/2012.00398.pdf
  # icon_pack: fab
  # icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Explicit Semantic Analysis (ESA) is a technique used to rep-resent a piece of text as a vector in the space of concepts, such as Articlesfound in Wikipedia. We propose a methodology to incorporate knowledgeof Inter-relatedness between Wikipedia Articles to the vectors obtainedfrom ESA using a technique called Retrofitting to improve the perfor-mance  of  subsequent  tasks  that  use  ESA  to  form  vector  embeddings.Especially we use an undirected Graph to represent this knowledge withnodes as Articles and edges as inter relations between two Articles. Here,we also emphasize how the ESA step could be seen as a predominantlybottom-up approach using a corpus to come up with vector representa-tions and the incorporation of top-down knowledge which is the relationsbetween Articles to further improve it. We test our hypothesis on sev-eral smaller subsets of the Wikipedia corpus and show that our proposedmethodology leads to decent improvements in performance measures in-cluding Spearman’s Rank correlation coefficient in most cases.