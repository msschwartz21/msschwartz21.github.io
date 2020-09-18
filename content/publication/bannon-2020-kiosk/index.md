---
title: "Dynamic allocation of computational resources for deep learning-enabled cellular image analysis with Kubernetes"
authors:
- D Bannon
- E Moen
- M Schwartz
- E Borba
- S Cui
- K Huang
- I Camplisson
- N Koe
- D Kyme
- T Kudo
- B Chang
- E Pao
- E Osterman
- W Graf
- D Van Valen
date: "2020-09-16"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-15"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: Deep learning is transforming the ability of life scientists to extract information from images. These techniques have better accuracy than conventional approaches and enable previously impossible analyses. As the capability of deep learning methods expands, they are increasingly being applied to large imaging datasets. The computational demands of deep learning present a significant barrier to large-scale image analysis. To meet this challenge, we have developed DeepCell 2.0, a platform for deploying deep learning models on large imaging datasets (>105-megapixel images) in the cloud. This software enables the turnkey deployment of a Kubernetes cluster on all commonly used operating systems. By using a microservice architecture, our platform matches computational operations with their hardware requirements to reduce operating costs. Further, it scales computational resources to meet demand, drastically reducing the time necessary for analysis of large datasets. A thorough analysis of costs demonstrates that cloud computing is economically competitive for this application. By treating hardware infrastructure as software, this work foreshadows a new generation of software packages for biology in which computational resources are a dynamically allocated resource.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: false

links:
- name: Deepcell.org
  url: https://www.deepcell.org
url_pdf: https://doi.org/10.1101/505032
url_code: 'https://github.com/vanvalenlab/kiosk'
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