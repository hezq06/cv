---
title: "Performance Optimization of Multi-particle Beam Dynamics Code IMPACT-Z on NVidia GPGPU"
authors:
- admin
- G. Shen
- Y. Yamazaki
- X. Wang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2016-05-01"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2016-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*7th Int. Particle Accelerator Conf.*"
publication_short: "IPAC'16"

abstract: Facility for Rare Isotope Beams is designed using a multiparticle tracking code IMPACT-Z. IMPACT-Z is originally for the purpose of accelerator design, so it is precise, however, quite time consuming, therefore usually not suitable for on-line beam tuning applications. IMPACT-Z is originally boosted using Message Passing Interface (MPI) technology. For single node mode, performance of IMPACT-Z is usually bounded by CPU performance, and for multinode mode, communication between MPI processes would become bottleneck. However, new emerging High Performance Computing (HPC) technology, like general-purpose graphics processing unit (GPGPU), brings new possibility in accelerating IMPACT-Z, so that the speed of IMPACT-Z satisfies for on-line beam tuning applications. This paper presents the efforts in exploring the capability of Nvidia GPGPU and the results of speed up of IMPACT-Z.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- FRIB
- Online Application
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://s3.cern.ch/inspire-prod-files-4/4cb22c1bc424038a8f74df7bfe914dc0'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**OpenAI**](https://https://chat.openai.com/auth/login)'
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
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
