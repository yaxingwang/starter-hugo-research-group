---
abstract: This paper addresses the problem of inferring unseen cross-modal
  image-to-image translations between multiple modalities. We assume that only
  some of the pairwise translations have been seen (i.e. trained) and infer the
  remaining unseen translations (where training pairs are not available). We
  propose mix and match networks, an approach where multiple encoders and
  decoders are aligned in such a way that the desired translation can be
  obtained by simply cascading the source encoder and the target decoder, even
  when they have not interacted during the training stage (i.e. unseen). The
  main challenge lies in the alignment of the latent representations at the
  bottlenecks of encoder–decoder pairs. We propose an architecture with several
  tools to encourage alignment, including autoencoders and robust side
  information and latent consistency losses. We show the benefits of our
  approach in terms of effectiveness and scalability compared with other
  pairwise image-to-image translation approaches. We also propose zero-pair
  cross-modal image translation, a challenging setting where the objective is
  inferring semantic segmentation from depth (and vice-versa) without explicit
  segmentation-depth pairs, and only from two (disjoint) segmentation-RGB and
  depth-RGB training sets. We observe that a certain part of the shared
  information between unseen modalities might not be reachable, so we further
  propose a variant that leverages pseudo-pairs which allows us to exploit this
  shared information between the unseen modalities.
slides: null
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - admin
  - Robert Ford
author_notes:
  - Equal contribution
  - Equal contribution
publication: "*International Journal of Computer Vision*"
summary: We investigate multi-domain translation
url_dataset: ""
url_project: ""
publication_short: IJCV
url_source: ""
url_video: ""
title: "Mix and match networks: cross-modal alignment for zero-pair
  image-to-image translation"
doi: ""
featured: false
tags:
  - Source Themes
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2020-01-15T14:14:06.528Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
