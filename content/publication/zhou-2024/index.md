---
title: 'Revisiting the Adversarial Robustness of Vision Language Models: a Multimodal
  Perspective'
authors:
- Wanqi Zhou
- Shuanghao Bai
- Qibin Zhao
- Badong Chen
date: '2024-04-01'
publishDate: '2024-05-18T14:37:43.347806Z'
publication_types:
- article-journal
abstract: Pretrained vision-language models (VLMs) like CLIP have shown impressive
  generalization performance across various downstream tasks, yet they remain vulnerable
  to adversarial attacks. While prior research has primarily concentrated on improving
  the adversarial robustness of image encoders to guard against attacks on images,
  the exploration of text-based and multimodal attacks has largely been overlooked.
  In this work, we initiate the first known and comprehensive effort to study adapting
  vision-language models for adversarial robustness under the multimodal attack. Firstly,
  we introduce a multimodal attack strategy and investigate the impact of different
  attacks. We then propose a multimodal contrastive adversarial training loss, aligning
  the clean and adversarial text embeddings with the adversarial and clean visual
  features, to enhance the adversarial robustness of both image and text encoders
  of CLIP. Extensive experiments on 15 datasets across two tasks demonstrate that
  our method significantly improves the adversarial robustness of CLIP. Interestingly,
  we find that the model fine-tuned against multimodal adversarial attacks exhibits
  greater robustness than its counterpart fine-tuned solely against image-based attacks,
  even in the context of image attacks, which may open up new possibilities for enhancing
  the security of VLMs.
links:
- name: URL
  url: http://arxiv.org/abs/2404.19287
---
