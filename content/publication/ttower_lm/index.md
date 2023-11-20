---
title: "Spontaneous Emerging Preference in Two-tower Language Model"
authors:
- admin
- Taro Toyoizumi
date: "2022-10-01"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Recent advances in the development of large language models have led to substantial enhancements in performance across an array of downstream tasks. Remarkably, these models, trained with straightforward end-to-end objectives, have demonstrated an inherent ability to manage language tasks. Not long ago, tackling language tasks heavily depended on our in-depth understanding of language. The convergence of these trends provides an excellent opportunity to delve into their relationship. Specifically, we pose the question, can contemporary deep neural network (DNN) based end-to-end language modeling paradigms provide us with insights into language? In this paper, we focus on a long-standing linguistic debate, can syntax and semantics be separated? We argue that by incorporating an inductive bias for labor division, the separation between syntax and semantics naturally emerges in the English language. To demonstrate this, we employ a two-tower language model setup. Here, two language models with identical configurations are trained collaboratively in parallel. Intriguingly, this configuration results in a spontaneously emerging preference where specific tokens are consistently better predicted by one tower, while others by the second tower. This pattern remains qualitatively consistent across different model structures and reflects separation of syntax and semantics. Our findings show the potential of DNN-based end-to-end trained language models in deepening our comprehension of the properties of natural language.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- CBS
- Language
featured: True

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2210.07041.pdf'
url_code: 'https://github.com/hezq06/twotower_lm'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
