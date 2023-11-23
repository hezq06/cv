---
title: "Progressive Interpretation Synthesis: Interpreting Task Solving by Quantifying Previously Used and Unused Information"
authors:
- admin
- Taro Toyoizumi
date: "2023-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Neural Computation (2023) 35*(1)38-57"
publication: ""
publication_short: ""

abstract: A deep neural network is a good task solver, but it is difficult to make sense of its operation. People have different ideas about how to form the interpretation about its operation. We look at this problem from a new perspective where the interpretation of task solving is synthesized by quantifying how much and what previously unused information is exploited in addition to the information used to solve previous tasks. First, after learning several tasks, the network acquires several information partitions related to each task. We propose that the network, then, learns the minimal information partition that supplements previously learned information partitions to more accurately represent the input. This extra partition is associated with un-conceptualized information that has not been used in previous tasks. We manage to identify what un-conceptualized information is used and quantify the amount. To interpret how the network solves a new task, we quantify as meta-information how much information from each partition is extracted. We implement this framework with the variational information bottleneck technique. We test the framework with the MNIST and the CLEVR dataset. The framework is shown to be able to compose information partitions and synthesize experience-dependent interpretation in the form of meta-information. This system progressively improves the resolution of interpretation upon new experience by converting a part of the un-conceptualized information partition to a task-related partition. It can also provide a visual interpretation by imaging what is the part of previously un-conceptualized information that is needed to solve a new task.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- CBS
- Cognition
featured: True

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://direct.mit.edu/neco/article/35/1/38/113811/Progressive-Interpretation-Synthesis-Interpreting'
url_code: 'https://github.com/hezq06/progressive_interpretation'
# url_dataset: '#'
url_poster: 'https://drive.google.com/file/d/1cUIWVPNVdWPVB7UPOD4MHnx4IvQt_9RF/view?usp=sharing'
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
slides: ""
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
