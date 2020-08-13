---
title: "Accurate cell tracking and lineage construction in live-cell imaging experiments with deep learning"
authors:
- E Moen
- E Borba
- G Miller
- M Schwartz
- D Bannon
- N Koe
- I Camplisson
- D Kyme
- C Pavelcheck
- T Price
- T Kudo
- E Pao
- W Graf
- D Van Valen
date: "2019-10-04"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-04"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: Live-cell imaging experiments have opened an exciting window into the behavior of living systems. While these experiments can produce rich data, the computational analysis of these datasets is challenging. Single-cell analysis requires that cells be accurately identified in each image and subsequently tracked over time. Increasingly, deep learning is being used to interpret microscopy image with single cell resolution. In this work, we apply deep learning to the problem of tracking single cells in live-cell imaging data. Using crowdsourcing and a human-in-the-loop approach to data annotation, we constructed a dataset of over 11,000 trajectories of cell nuclei that includes lineage information. Using this dataset, we successfully trained a deep learning model to perform cell tracking within a linear programming framework. Benchmarking tests demonstrate that our method achieves state-of-the-art performance on the task of cell tracking with respect to multiple accuracy metrics. Further, we show that our deep learning-based method generalizes to perform cell tracking for both fluorescent and brightfield images of the cell cytoplasm, despite having never been trained on those data types. This enables analysis of live-cell imaging data collected across imaging modalities. A persistent cloud deployment of our cell tracker is available at http://www.deepcell.org.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: false

links:
- name: Deepcell
  url: https://www.deepcell.org
url_pdf: https://doi.org/10.1101/803205
url_code: 'https://github.com/vanvalenlab/deepcell-tracking'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---