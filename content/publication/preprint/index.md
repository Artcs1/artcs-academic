---
title: "Gaussian Bounding Boxes and Probabilistic Intersection-over-Union for Object Detection"
authors:
- admin
- Luis Felipe de Araujo Zeni
- Lucas N. Kristen
- Claudio R. Jung
date: "2021-10-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Most object detection methods use bounding boxes to encode and represent the object shape and location. In this work, we explore a fuzzy representation of object regions using Gaussian distributions, which provides an implicit binary representation as (potentially rotated) ellipses. We also present a similarity measure for the Gaussian distributions based on the Hellinger Distance, which can be viewed as a Probabilistic Intersection-over-Union (ProbIoU). Our experimental results show that the proposed Gaussian representations are closer to annotated segmentation masks in publicly available datasets, and that loss functions based on ProbIoU can be successfully used to regress the parameters of the Gaussian representation. Furthermore, we present a simple mapping scheme from traditional (or rotated) bounding boxes to Gaussian representations, allowing the proposed ProbIoU-based losses to be seamlessly integrated into any object detector.

# Summary. An optional shortened abstract.
summary: Most object detection methods use bounding boxes to encode and represent the object shape and location. In this work, we explore a fuzzy representation of object regions using Gaussian distributions, which provides an implicit binary representation as (potentially rotated) ellipses. We also present a similarity measure for the Gaussian distributions based on the Hellinger Distance, which can be viewed as a Probabilistic Intersection-over-Union (ProbIoU). Our experimental results show that the proposed Gaussian representations are closer to annotated segmentation masks in publicly available datasets, and that loss functions based on ProbIoU can be successfully used to regress the parameters of the Gaussian representation. Furthermore, we present a simple mapping scheme from traditional (or rotated) bounding boxes to Gaussian representations, allowing the proposed ProbIoU-based losses to be seamlessly integrated into any object detector.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: https://arxiv.org/abs/2106.06072
url_pdf: https://arxiv.org/pdf/2106.06072.pdf
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
