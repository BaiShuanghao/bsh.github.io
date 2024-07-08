---
title: "Soft Prompt Generation for Domain Generalization"

authors:
  - Admin
  - Yuedi Zhang
  - Wanqi Zhou
  - Zhirong Luan
  - Badong Chen

author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "arXiv: 2404.19286"

abstract: Large pre-trained vision language models (VLMs) have shown impressive zero-shot ability on downstream tasks with manually designed prompt, which are not optimal for specific domains. To further adapt VLMs to downstream tasks, soft prompt is proposed to replace manually designed prompt, which acts as a learning vector that undergoes fine-tuning based on specific domain data. Prior prompt learning methods primarily learn a fixed prompt and residuled prompt from training samples. However, the learned prompts lack diversity and ignore information about unseen domains, potentially compromising the transferability of the prompts. In this paper, we reframe the prompt learning framework from a generative perspective and propose a simple yet efficient method for the Domain Generalization (DG) task, namely \textbf{S}oft \textbf{P}rompt \textbf{G}eneration (SPG). To the best of our knowledge, we are the first to introduce the generative model into prompt learning in VLMs and explore its potential for producing soft prompts by relying solely on the generative model, ensuring the diversity of prompts. Specifically, SPG consists of a two-stage training phase and an inference phase. During the training phase, we introduce soft prompt labels for each domain, aiming to incorporate the generative model domain knowledge. During the inference phase, the generator of the generative model is employed to obtain instance-specific soft prompts for the unseen target domain. Extensive experiments on five domain generalization benchmarks of three DG tasks demonstrate that our proposed SPG achieves state-of-the-art performance. The code will be available soon.

# Summary. An optional shortened abstract.
summary: 

tags: ['Domain Generalization', 'Vision Language Models', 'Prompt Tuning', 'Generalization']

featured: false

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

links:
  - name: Paper
    url: https://arxiv.org/pdf/2404.19286

# - name: Code
#   url: https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Framework'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
