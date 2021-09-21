---
title: "Whole-cell segmentation of tissue images with human-level performance using large-scale data annotation and deep learning"
authors:
- N Greenwald
- G Miller
- E Moen
- A Kong
- A Kagel
- C Fullaway
- B McIntosh
- K Leow
- M Schwartz
- T Dougherty
- C Pavelchek
- S Cui
- I Camplisson
- O Bar-Tal
- J Singh
- M Fong
- G Chaudhry
- Z Abraham
- J Moseley
- S Warshawsky
- E Soon
- S Greenbaum
- T Risom
- T Hollmann
- L Keren
- W Graf
- M Angelo
- D Van Valen
date: "2021"
doi: " https://doi.org/10.1101/2021.03.01.431313"

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

abstract: Understanding the spatial organization of tissues is of critical importance for both basic and translational research. While recent advances in tissue imaging are opening an exciting new window into the biology of human tissues, interpreting the data that they create is a significant computational challenge. Cell segmentation, the task of uniquely identifying each cell in an image, remains a substantial barrier for tissue imaging, as existing approaches are inaccurate or require a substantial amount of manual curation to yield useful results. Here, we addressed the problem of cell segmentation in tissue imaging data through large-scale data annotation and deep learning. We constructed TissueNet, an image dataset containing >1 million paired whole-cell and nuclear annotations for tissue images from nine organs and six imaging platforms. We created Mesmer, a deep learning-enabled segmentation algorithm trained on TissueNet that performs nuclear and whole-cell segmentation in tissue imaging data. We demonstrated that Mesmer has better speed and accuracy than previous methods, generalizes to the full diversity of tissue types and imaging platforms in TissueNet, and achieves human-level performance for whole-cell segmentation. Mesmer enabled the automated extraction of key cellular features, such as subcellular localization of protein signal, which was challenging with previous approaches. We further showed that Mesmer could be adapted to harness cell lineage information present in highly multiplexed datasets. We used this enhanced version to quantify cell morphology changes during human gestation. All underlying code and models are released with permissive licenses as a community resource.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: false


url_pdf: 'https://doi.org/10.1101/2021.03.01.431313'
url_code: ''
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