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
publication: In *European Conference onComputer Vision*
publication_short: In *ECCV 2024*

abstract: Large pre-trained vision language models (VLMs) have shown impressive zero-shot ability on downstream tasks with manually designed prompt. To further adapt VLMs to downstream tasks, soft prompt is proposed to replace manually designed prompt, which undergoes fine-tuning based on specific domain data. Prior prompt learning methods primarily learn a fixed prompt and residuled prompt from training samples. However, the learned prompts lack diversity and ignore information about unseen domains. In this paper, we reframe the prompt learning framework from a generative perspective and propose a simple yet efficient method for the Domain Generalization (DG) task, namely Soft Prompt Generation (SPG). Specifically, SPG consists of a two-stage training phase and an inference phase. During the training phase, we introduce soft prompt label for each domain, aiming to incorporate the generative model domain knowledge. During the inference phase, the generator of the generative model is employed to obtain instance-specific soft prompts for the unseen target domain. Extensive experiments on five domain generalization benchmarks of three DG tasks demonstrate that SPG achieves state-of-the-art performance. The code is available at https://github.com/renytek13/Soft-Prompt-Generation-with-CGAN.

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

  - name: Code
    url: https://github.com/renytek13/Soft-Prompt-Generation-with-CGAN


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
