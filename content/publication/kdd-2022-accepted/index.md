---
title: 'Connecting the Hosts: Street-Level IP Geolocation with Graph Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiyuan Wang
  - admin
  - Fan Zhou
  - Goce Trajcevski
  - Chunjing Xiao
  - Yong Wang
  - Kai Chen

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-08-15T00:00:00Z'
doi: '10.1145/3534678.3539049'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining
publication_short: KDD 2022

abstract: Pinpointing the geographic location of an IP address is important for a range of location-aware applications spanning from targeted advertising to fraud prevention. The majority of traditional measurement-based and recent learning-based methods either focus on the efficient employment of topology or utilize data mining to find clues of the target IP in publicly available sources. Motivated by the limitations in existing works, we propose a novel framework named GraphGeo, which provides a complete processing methodology for street-level IP geolocation with the application of graph neural networks. It incorporates IP hosts knowledge and kinds of neighborhood relationships into the graph to infer spatial topology for high-quality geolocation prediction. We explicitly consider and alleviate the negative impact of uncertainty caused by network jitter and congestion, which are pervasive in complicated network environments. Extensive evaluations across three large-scale real-world datasets demonstrate that GraphGeo significantly reduces the geolocation errors compared to the state-of-the-art methods. Moreover, the proposed framework has been deployed on the web platform as an online service for 6 months.

# Summary. An optional shortened abstract.
summary: We propose a novel framework named GraphGeo, which provides a complete processing methodology for street-level IP geolocation with the application of graph neural networks.

tags: [Data Mining, IP Geolocation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3534678.3539049'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://dl.acm.org/doi/abs/10.1145/3534678.3539049'

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
