---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Checkpointing in Practice for Memory-Efficient Training on the Edge"
authors: ["Naveen E", "Pratyush Kumar"]
date: 2019-08-12T00:00:00Z
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-03T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *2019 IEEE 21st International Conference on High Performance Computing and Communications; IEEE 17th International Conference on Smart City; IEEE 5th International Conference on Data Science and Systems (HPCC/SmartCity/DSS)* (pp. 2759-2766). IEEE."
publication_short: "In *2019 IEEE HPCC/SmartCity/DSS*"

abstract: "Training deep neural networks has large memory requirements to store the activation maps for the forward pass of all layers to be able to compute the gradients during the backward pass. When training networks on the edge, large models may either not fit in the memory or may run with very small batch sizes. Checkpointing has been proposed as a solution, whereby during the forward pass the activation maps from only some of the layers are stored as checkpoints, and the rest are recomputed during the backward pass starting from the closest checkpoint. However, checkpointing in practice requires a careful choice of the set of layers to checkpoint. In this paper we empirically evaluate checkpointing for different networks. We then establish an analytical approach to estimate the memory requirement of each layer (using a linear regression model) in a network and thereby identify the layers which have to be checkpointed. Through this method we were able to reduce memory consumption of MobileNet and ResNet-18 architectures by a factor of 2.6 and 1.8 respectively. Finally, the networks are tested on a Raspberry Pi 3 Model B board. For MobileNet using our approach for checkpointing, we could increase the batch-size from 4 to 12."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: IEEE Website
  url: https://ieeexplore.ieee.org/abstract/document/8855345
  # icon_pack: fab
  # icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides: https://drive.google.com/file/d/15YciTEH3GTfgy3RJlJmdY4RC0_L0jDIt/view?usp=sharing
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
