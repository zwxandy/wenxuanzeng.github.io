---
title: 'CoPriv: Network/Protocol Co-Optimization for Communication-Efficient Private Inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Meng Li
  - Haichuan Yang
  - Wen-jie Lu
  - Runsheng Wang
  - Ru Huang

# Author notes (optional)
author_notes:
  - 
  - Corresponding author


date: '2023-09-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-22'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Thirty-seventh Conference on Neural Information Processing Systems, 2023
publication_short: NeurIPS 2023

abstract: Deep neural network (DNN) inference based on secure 2-party computation (2PC) can offer cryptographically-secure privacy protection but suffers from orders of magnitude latency overhead due to enormous communication. Previous works heavily rely on a proxy metric of ReLU counts to approximate the communication overhead and focus on reducing the ReLUs to improve the communication efficiency. However, we observe these works achieve limited communication reduction for state-of-the-art (SOTA) 2PC protocols due to the ignorance of other linear and non-linear operations, which now contribute to the majority of communication. In this work, we present CoPriv, a framework that jointly optimizes the 2PC inference protocol and the DNN architecture. CoPriv features a new 2PC protocol for convolution based on Winograd transformation and develops DNN-aware optimization to significantly reduce the inference communication. CoPriv further develops a 2PC-aware network optimization algorithm that is compatible with the proposed protocol and simultaneously reduces the communication for all the linear and non-linear operations. We compare CoPriv with the SOTA 2PC protocol, CrypTFlow2, and demonstrate 2.1× communication reduction for both ResNet-18 and ResNet-32 on CIFAR-100. We also compare CoPriv with SOTA network optimization methods, including SNL, MetaPruning, etc. CoPriv achieves 9.98× and 3.88× online and total communication reduction with a higher accuracy compare to SNL, respectively. CoPriv also achieves 3.87× online communication reduction with more than 3% higher accuracy compared to MetaPruning.

# Summary. An optional shortened abstract.
# summary: We propose a novel framework named GraphGeo, which provides a complete processing methodology for street-level IP geolocation with the application of graph neural networks.

tags: [Private Inference, Network/Protocol Co-Optimization, Winograd Convolution, Structural Re-parameterization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=qVeDwgYsho'
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
  caption: ''
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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
