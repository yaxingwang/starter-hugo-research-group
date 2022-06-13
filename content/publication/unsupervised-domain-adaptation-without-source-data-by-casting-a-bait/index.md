---
title: Unsupervised domain adaptation without source data by casting a bait
abstract: "We address the source-free domain adaptation (SFDA) problem, where
  only the source model is available during adaptation to the target domain. We
  consider two settings: the offline setting where all target data can be
  visited multiple times (epochs) to arrive at a prediction for each target
  sample, and the online setting where the target data needs to be directly
  classified upon arrival. Inspired by diverse classifier based domain
  adaptation methods, in this paper we introduce a second classifier, but with
  another classifier head fixed. When adapting to the target domain, the
  additional classifier initialized from source classifier is expected to find
  misclassified features. Next, when updating the feature extractor, those
  features will be pushed towards the right side of the source decision
  boundary, thus achieving source-free domain adaptation. Experimental results
  show that the proposed method achieves competitive results for offline SFDA on
  several benchmark datasets compared with existing DA and SFDA methods, and our
  method surpasses by a large margin other SFDA methods under online source-free
  domain adaptation setting."
slides: null
url_pdf: https://arxiv.org/pdf/2112.02219.pdf
publication_types:
  - "1"
authors:
  - Shiqi Yang
  - Yaxing Wang
  - Joost van de Weijer
  - Luis Herranz
  - Shangling Jui
publication: In *Arxiv libary*
featured: true
tags:
  - Source Themes
projects:
  - internal-project
summary: We explore first the setting from unconditional GANs to conditional GANs.
url_dataset: "#"
url_project: ""
publication_short: In *arxiv*
url_source: "#"
url_video: "#"
date: 2020-10-01T14:22:19.468Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: "#"
doi: ""
---
Code: <https://github.com/Albert0147/BAIT_SFUDA>[](https://sourcethemes.com/academic/docs/writing-markdown-latex/)