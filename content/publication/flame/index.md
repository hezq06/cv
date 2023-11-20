---
title: "The fast linear accelerator modeling engine for FRIB online model service"
authors:
- admin
- M. Davidsaver
- K. Fukushima
- G. Shen
- J. Bengtsson
- M. Ikegami
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Physics Communications, 234*(167-178)"
publication_short: ""

abstract: Commissioning of a large accelerator facility like FRIB needs support from an online beam dynamics model. Considering the new physics challenges of FRIB such as modeling of non-axisymmetric superconducting RF cavities and multicharge state acceleration, there is no readily available online beam tuning code. The design code of FRIB super-conducting linac, IMPACT-Z, is not suitable for online tuning because of its code design and running speed. Therefore, the Fast Linear Accelerator Modeling Engine (FLAME), specifically designed to fulfill FRIB’s online modeling challenges, is proposed. The physics model of FLAME, especially its novel way of modeling non-axisymmetric superconducting RF cavities using a multipole expansion based thin-lens kick model, is discussed in detail, and the benchmark results against FRIB design code is presented, after which the software design strategy of FLAME and its execution speed is presented.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- FRIB
- FLAME
- Online Application
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://pdf.sciencedirectassets.com/271575/1-s2.0-S0010465518X00113/1-s2.0-S0010465518302662/am.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQDtmup0d%2FcDHTdyDWqA9fT56SrRGBn7mlpteqQti%2Fq5gAIgS3DhMuMKwKe%2F0ZdWxYx0NuNaKLqphr0NirsYFWc5LDYqvAUI7v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDJiAT2iZ5z5XLp1VrSqQBbH5u%2Bnpea1dA5eDnBJNH4CQkTlmRc%2FNj4153ljMm3dKrfBlnPwBoi3seSwAc%2B%2F8z0r5nbuOoeos%2B2pDeKXSRZyXwsCgADBLt80rIOgDAXpw2lBc%2FxfCrE2VhZDgdJ0WA8s2HSEq98KCS9oRJCBAmx3pf2JCmxEmgoal0Axw%2FmxTk4SuDpqyGP%2BbH%2BGmKmSK2IrxtwaQ0Mz5EZQjB%2Fc9i6MoFhZIyCN5TdFKM7KEvxHQuhnYmlWNegOmHzTjHAaRLE9IUV60ud5vv0eqmE0PuubkVNaJq4bPFYKP%2BdV1YL7K0XEzD0XsRLLYR5WL0gHS9ZieCtc6l9tCqgiXhPel130dUfGMl9t%2F9JdTcDmj51DXXuHI33knJxCEQ072jNkMdOF%2Fplvz3kbp3dQR1crNByguEwpxXhAGtd7K6vMB9cRFpN9qdk8P0yO5QeOpVy98Lo7C6Tisx6oEgEeUO10cPDFEVhd6cag8teUMCvY6uKeHPIjNsye7z2uQYaErADIsHL5ZXSEc%2BjnIL0Gtl8KKdh5K4hjR5bpT9gn71TSKSApP8zV2nTekcZM8Wv6WeA%2F3cvbGENFh6m5fAQ5anrCUGW7DPEWhM9vIGcW72%2B374ppUfm9MUO3pTZnLXkas1Aqv9kQ51uZBm%2BzZwjJz%2FCVY3wx%2Fsi4SwcMXssaqUjL8o3Fw0NjExarHsvJ9Y9lSzpt9iPDx14%2BSmyPCAmV6tWI1NhvJVuDvHsdZMaI4pYyeG7lGPZSI%2BBEhxKmgUyAco0sZ8KKfLs0Cru2PyWOsCOcmXuvdPB031RqqCvdPuUnOLi5n9%2BYJYs1ulZ1Y9RpezvNFoZpBoilJ0MqNJ9EJr38hqtJa2a9I8FBPNJkITyb7h4tuMNSm7aoGOrEBbXE%2FREkQifbcsFLKu6bcgE2HOz35c9WFmQv8EVnQuOLQNYs2JQKIw9iXt9O%2Fy8YIDYD%2Bxbuf0zJYdxVQf%2FOq5jF7XOe60POIs7a828wJYzOJktwNPPmY%2FlHjE6wwIp73KwwsWQl8UR8NncUjy5LmtOMfuiCaPAzcscaFwHwCdC%2BFMZ27SfZedqVYbj3Zgf7r%2Fj9OEY88EGb1sqoXeemZ6Iy0hkdbM8rcITe31upZfnt7&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231120T133605Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYSMOHXYNF%2F20231120%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=815f5c3fe7d864bed1c7abf92cc6f18c0059c8dff209f66f55ecdb8b9ffd53e8&hash=5a59889dc7e9cacbbe2b41a87a976da62c987dc812284b73666512775d5c6276&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0010465518302662&tid=pdf-424f1aa4-f3d0-4b07-a1c9-381a95071e66&sid=3f3f7e9c434a624be92b9f36da877cacd559gxrqa&type=client'
url_code: 'https://github.com/frib-high-level-controls/FLAME'
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
