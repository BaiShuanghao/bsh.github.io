---
title: 'Jacobian Regularizer-based Neural Granger Causality'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wanqi Zhou 
  - Admin 
  - Shujian Yu
  - Qibin Zhao
  - Badong Chen

# Author notes (optional)
author_notes:
  - 
  - 

date: '2024-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML 2024*

abstract: With the advancement of neural networks, diverse methods for neural Granger causality have emerged, which demonstrate proficiency in handling complex data, and nonlinear relationships. However, the existing framework of neural Granger causality has several limitations. It requires the construction of separate predictive models for each target variable, and the relationship depends on the sparsity on the weights of the first layer, resulting in challenges in effectively modeling complex relationships between variables as well as unsatisfied estimation accuracy of Granger causality. Moreover, most of them cannot grasp full-time Granger causality. To address these drawbacks, we propose a Jacobian Regularizer-based Neural Granger Causality (JRNGC) approach, a straightforward yet highly effective method for learning multivariate summary Granger causality and full-time Granger causality by constructing a single model for all target variables. Specifically, our method eliminates the sparsity constraints of weights by leveraging an input-output Jacobian matrix regularizer, which can be subsequently represented as the weighted causal matrix in the post-hoc analysis. Extensive experiments show that our proposed approach achieves competitive performance with the state-of-the-art methods for learning summary Granger causality and full-time Granger causality while maintaining lower model complexity and high scalability.

# Summary. An optional shortened abstract.
summary: 

tags: ['Granger Causality', 'Jacobian Regularizer', 'Generalization']

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://arxiv.org/pdf/2312.09553'
# url_code: 'https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

links:
- name: Paper
  url: https://arxiv.org/pdf/2405.08779

- name: Code
  url: https://github.com/ElleZWQ/JRNGC

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Framework'
  focal_point: ''
  preview_only: False

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
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
