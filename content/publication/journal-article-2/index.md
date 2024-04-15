---
title: "YTLR: Extracting yeast transcription factor-gene associations from the literature using automated literature readers"
authors:
- Tzu-Hsien Yang
- admin
- Hsiu-Chun Tsai
- Ya-Chiao Yang
- Cheng-Tse Liu
author_notes:
date: "2022-08-27T00:00:00Z"
doi: "https://doi.org/10.1016/j.csbj.2022.08.041"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computational and Structural Biotechnology Journal*"
publication_short: ""

abstract: 'Cells adapt to environmental stresses mainly via transcription reprogramming. Correct transcription control is mediated by the interactions between transcription factors (TF) and their target genes. These TF-gene associations can be probed by chromatin immunoprecipitation techniques and knockout experiments, revealing TF binding (TFB) and regulatory (TFR) evidence, respectively. Nevertheless, most evidence is still fragmentary in the literature and requires tremendous human resources to curate. We developed the first pipeline called YTLR (Yeast Transcription-regulation Literature Reader) to automate TF-gene relation extraction from the literature. YTLR first identifies articles with TFB and TFR information. Then TF-gene binding pairs are extracted from the TFB articles, and TF-gene regulatory associations are recognized from the TFR papers. On gathered test sets, YTLR achieves an AUC value of 98.8% in identifying articles with TFB evidence and AUC = 83.4% in extracting the detailed TF-gene binding pairs. And similarly, YTLR also obtains an AUC value of 98.2% in identifying TFR articles and AUC = 80.4% in extracting the detailed TF-gene regulatory associations. Furthermore, YTLR outperforms previous methods in both tasks. To facilitate researchers in extracting TF-gene transcriptional relations from large-scale queried articles, an automated and easy-to-use software tool based on the YTLR pipeline is constructed. In summary, YTLR aims to provide easier literature pre-screening for curators and help researchers gather yeast TF-gene transcriptional relation conclusions from articles in a high-throughput fashion. The YTLR pipeline software tool can be downloaded at https://github.com/cobisLab/YTLR/.'

# Summary. An optional shortened abstract.
summary: 

tags:

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/J28Nn-CDbII)'
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
# slides: 
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
