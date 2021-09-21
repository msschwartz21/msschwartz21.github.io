---
title: "DeepCell Foundry: Machine Learning Infrastructure for Single-Cell Biology"
authors:
- E Moen
- M Schwartz
- G Miller
- N Greenwald
- T Dougherty
- W Graf
- E Pao
- D Van Valen
date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-15"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "OpenReview"
publication_short: ""

abstract: Advances in imaging and genomics are rapidly improving our ability to profile changes within biological matter. When paired with deep learning, these new technologies could revolutionize our ability to study changes at the single-cell level. However, there is a fundamental disconnect between the two communities that need to interact in service of this revolution. Biologists generate unique data to answer a specific question and need bespoke analysis software to spur discovery. Meanwhile, researchers in machine learning need well-formatted, real-world data to develop and test theories and algorithms that apply generally. Taking the highly-variable data generated in the former paradigm and assembling it into standardized training data for the latter in a scalable, reproducible fashion remains a considerable barrier to necessary advancement in both fields. In this work, we hope to provide the architecture to bridge the gap between the two and describe how the sometimes tedious, but absolutely necessary, data management tasks can be automated or minimized. We show that human-in-the-loop (HITL) AI systems accelerate single-cell data annotation when paired with an automated framework for data management and report on the development of a new machine learning infrastructure for biology. To demonstrate the efficacy of our approach, we discuss lessons learned from the construction of two datasets, one involving highly-multiplexed tissue data and the other live-cell imaging. The first dataset, TissueNet, is currently publicly available. It contains over 1 million paired whole-cell and nuclear annotations for tissue images from nine organs and six imaging platforms - making it the largest collection compiled to-date. The second, LiveCellNet, contains over 750 thousand annotations (nuclear and whole-cell) across seven cell lines and two imaging modalities (phase and fluorescent) and growing. In both cases, our system seamlessly integrates data collected by our lab and collaborators with publicly available datasets while maintaining key pieces of metadata. This integration encodes our ontology into the metadata for every annotation. The metadata allows us to engage in domain-aware data preparation and augmentation - allowing us to select as narrow or broad a set of data as required for the task at hand. Ultimately, the value of our infrastructure depends not just on the data but the models and investigations we enable. We demonstrate the utility of our infrastructure by reporting on the creation of performant models of segmentation and cell tracking. Our infrastructure ensures that these models are automatically versioned alongside the data. These models are then hosted for use on DeepCell.org. In addition to the datasets and models that have resulted from this investigation, we report on the annotation tools, ontology, data versioning systems, and best practices we have developed to house and manage these collections of data. We believe the HITL machine learning infrastructure we have developed holds significant promise not only for the challenge of single-cell analysis with deep learning but for solving image analysis problems across the various domains of life.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: false


url_pdf: 'https://openreview.net/forum?id=rjYOX6y1HF'
url_code: ''
url_dataset: 'https://datasets.deepcell.org/'
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