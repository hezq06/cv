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
url_pdf: 'https://watermark.silverchair.com/neco_a_01542.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAzowggM2BgkqhkiG9w0BBwagggMnMIIDIwIBADCCAxwGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMvNsAy7OBYYzS-z3DAgEQgIIC7ThSfBQ2X31rHkjjWWSC3xRx7Kl0PeZxXmT5IvuOQOXnGdAlOMBuK9s-eG90rjmHHnWMsrnqe-usIipPDwVfgb41aKgmAurrYI03in5-rtsWT4rQWFaCwamf9GQl9_U2MbCWCbaeGh8B_jwwkAPPxRXMSlf42ptJ0Cx44gvL1QX84Z5mFdeBrNwBZtJ85OkvQ6GCH9lLpsDnIpXjbQwBsMLL2ZV3vyR1CA6ci0nlyRAtm1QVhu5Yid1XgnULTOd50jnBxbXn86fBti-obcIGKJl2OrvnibnOY3aWdPK96RjR856KEAHZZBUH7FRhH-ao9gUdfgdC3zN44ml_wfXwcAzE3sLQbfS4dIUmJgt4dfh01JQZ-_Rv0auBr1Fy1651oT5yDF5AzCltcyJYwVT6sSOmLqyTQug_j9lgFRiTCStnJ7767QjPOEKrjmtg6Dz-BqZDz-zfYS9Vr9cD9jARkRnBpilChYgEk3xkjKqhKFdzzqpJPRuKf5WCOtXqnfxTFx3KdJoxBMzw9dautZNMONvp72-Iv-42NJrXeRU7U4t-5-k_Yg_rVc-iV3p7CVKmLSeJhA4tVJK_3XURl3xb9QIInjV9gdDEV4Nrv0lMj7Hc2DLU_UTG9gxLMDdhRdEMrREpFtv_ToTHnkKRouANqBZy_ejIcTaN4zDF5s04__oKVv6QWihihH0BMpF4jUXfok6dTnqBIcB-Ozndj6yuCl3x-8g0VEd2xAODPfpPpSJV48RqAHOAigsZGWXhblqaCyDl-cvtxF0FUF0QmNaCvwpo868cHisIusoj2KLHKkinTeHMFo7vNJQujcgMlTI0kzhGdTb2DGM435ZeXq93DusGFmxXH8Agqg4kSwIUqJYFPwC1kjMIYUasuQzp7FhQiD0i2mvhgT7cabToAlytKdeg3MFZD0krSus-Wyc8mgzcfznAhlVkx5H3FbJ8-zYU9PSfnWD1J1FzTYgtwktUBMm6ZPHyo-82FVHETdGr'
url_code: 'https://github.com/hezq06/progressive_interpretation'
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
