---
title: "One Ring to Bring Them All: Towards Open-Set Recognition under Domain Shift"
abstract: "In this paper, we investigate open-set recognition with domain shift,
  where the final goal is to achieve Source-free Universal Domain Adaptation
  (SF-UNDA), which addresses the situation where there exist both domain and
  category shifts between source and target domains. Under the SF-UNDA setting,
  the model cannot access source data anymore during target adaptation, which
  aims to address data privacy concerns. We propose a novel training scheme to
  learn a (n+1)-way classifier to predict the n source classes and the unknown
  class, where samples of only known source categories are available for
  training. Furthermore, for target adaptation, we simply adopt a weighted
  entropy minimization to adapt the source pretrained model to the unlabeled
  target domain without source data. In experiments, we show: 1) After source
  training, the resulting source model can get excellent performance for
  open-set single domain generalization and also open-set recognition tasks; 2)
  After target adaptation, our method surpasses current UNDA approaches which
  demand source data during adaptation on several benchmarks. The versatility to
  several different tasks strongly proves the efficacy and generalization
  ability of our method. 3) When augmented with a closed-set domain adaptation
  approach during target adaptation, our source-free method further outperforms
  the current state-of-the-art UNDA method by 2.5%, 7.2% and 13% on Office-31,
  Office-Home and VisDA respectively."
slides: null
url_pdf: https://proceedings.neurips.cc/paper/2021/file/f5deaeeae1538fb6c45901d524ee2f98-Paper.pdf
publication_types:
  - "1"
authors:
  - Shiqi Yang
  - Yaxing Wang
  - Kai Wang
  - Shangling Jui
  - Joost van de Weijer
publication: Arxiv
featured: true
tags:
  - Source Themes
projects:
  - internal-project
summary: ""
url_dataset: "#"
url_project: ""
publication_short: Arxiv
url_source: "#"
url_video: "#"
date: 2022-06-13T06:34:50.123Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
  filename: featured.png
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: https://github.com/Albert0147/SFDA_neighbors
doi: ""
---
Code: https:<https://github.com/Albert0147/OneRing_SF-UNDA>[](https://github.com/Albert0147/AaD_SFDA)[](https://github.com/Albert0147/SFDA_neighbors).