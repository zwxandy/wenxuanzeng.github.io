---
title: 'MPCViT: Searching for Accurate and Efficient MPC-Friendly Vision Transformer with Heterogeneous Attention'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Meng Li
  - Wenjie Xiong
  - Tong Tong
  - Wen-jie Lu
  - Jin Tan
  - Runsheng Wang
  - Ru Huang

# Author notes (optional)
author_notes:
  -
  - Corresponding author

date: '2023-08-15'
doi: '10.48550/arXiv.2211.13955'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-15'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2023
publication_short: ICCV 2023

abstract: Secure multi-party computation (MPC) enables computation directly on encrypted data and protects both data and model privacy in deep learning inference. However, existing neural network architectures, including Vision Transformers (ViTs), are not designed or optimized for MPC and incur significant latency overhead. We observe Softmax accounts for the major latency bottleneck due to a high communication complexity, but can be selectively replaced or linearized without compromising the model accuracy. Hence, in this paper, we propose an MPC-friendly ViT, dubbed MPCViT, to enable accurate yet efficient ViT inference in MPC. Based on a systematic latency and accuracy evaluation of the Softmax attention and other attention variants, we propose a heterogeneous attention optimization space. We also develop a simple yet effective MPC-aware neural architecture search algorithm for fast Pareto optimization. To further boost the inference efficiency, we propose MPCViT+, to jointly optimize the Softmax attention and other network components, including GeLU, matrix multiplication, etc. With extensive experiments, we demonstrate that MPCViT achieves 1.9%, 1.3% and 3.6% higher accuracy with 6.2x, 2.9x and 1.9x latency reduction compared with baseline ViT, MPCFormer and THE-X on the Tiny-ImageNet dataset, respectively. MPCViT+ further achieves a better Pareto front compared with MPCViT. The code and models for evaluation are available at https://github.com/PKU-SEC-Lab/mpcvit.

# Summary. An optional shortened abstract.
# summary: We propose a novel framework named GraphGeo, which provides a complete processing methodology for street-level IP geolocation with the application of graph neural networks.

tags: [Multi-party Computation, Vision Transformer, Attention Mechanism]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2023/papers/Zeng_MPCViT_Searching_for_Accurate_and_Efficient_MPC-Friendly_Vision_Transformer_with_ICCV_2023_paper.pdf'
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
