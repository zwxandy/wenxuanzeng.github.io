---
title: 'Converge to the truth: Factual error correction via iterative constrained editing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiangjie Chen
  - Rui Xu
  - admin
  - Changzhi Sun
  - Lei Li
  - Yanghua Xiao

# Author notes (optional)
author_notes:
  - Equal contribution
  - Equal contribution
  - 
  - Corresponding author
  - 
  - Corresponding author

date: '2023-06-26'
doi: 'https://doi.org/10.1609/aaai.v37i11.26485'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-26'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the AAAI Conference on Artificial Intelligence, 2023
publication_short: AAAI 2023

abstract: Given a possibly false claim sentence, how can we automatically correct it with minimal editing? Existing methods either require a large number of pairs of false and corrected claims for supervised training or do not handle well errors spanning over multiple tokens within an utterance. In this paper, we propose VENCE, a novel method for factual error correction (FEC) with minimal edits. VENCE formulates the FEC problem as iterative sampling editing actions with respect to a target density function. We carefully design the target function with predicted truthfulness scores from an offline trained fact verification model. VENCE samples the most probable editing positions based on back-calculated gradients of the truthfulness score concerning input tokens and the editing actions using a distantly-supervised language model (T5). Experiments on a public dataset show that VENCE improves the well-adopted SARI metric by 5.3 (or a relative improvement of 11.8%) over the previous best distantly-supervised methods.

# Summary. An optional shortened abstract.
# summary: We propose a novel framework named GraphGeo, which provides a complete processing methodology for street-level IP geolocation with the application of graph neural networks.

tags: [Natural Language Processing, Factual Error Correction, Text Editing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/26485'
url_code: 'https://github.com/jiangjiechen/VENCE'
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
