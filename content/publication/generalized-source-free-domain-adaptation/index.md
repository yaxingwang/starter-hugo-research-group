---
title: Generalized Source-free Domain Adaptation
abstract: Domain adaptation (DA) aims to transfer the knowledge learned from
  source domain to an unlabeled target domain. Some recent works tackle
  source-free domain adaptation (SFDA) where only source pre-trained model is
  available for adaptation to target domain. However those methods does not
  consider keeping source performance which is of high practical value in real
  world application. In this paper, we propose a new domain adaptation paradigm
  denoted as Generalized Source-free Domain Adaptation (G-SFDA), where the
  learned model needs to perform well on both target and source domains, with
  only access to current unlabeled target data during adaptation. First, we
  propose local structure clustering (LSC), aiming to cluster the target
  features with its semantically similar neighbors, which successfully adapts
  the model to target domain in absence of source data. Second, we propose
  randomly generated domain attention (RGDA), it produces binary domain specific
  attention to activate different feature channels for different domains,
  meanwhile the domain attention will be utilized to regularize the gradient
  during adaptation to keep source information. In the experiments, for target
  performance our method is on par with or better than existing DA and SFDA
  methods, specifically achieves state-of-the-art performance (85.4%) on VisDA,
  and our method works well for all domains after adapting to single or multiple
  target domains.
slides: null
url_pdf: https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_TransferI2I_Transfer_Learning_for_Image-to-Image_Translation_From_Small_Datasets_ICCV_2021_paper.pdf
publication_types:
  - "1"
authors:
  - Shiqi Yang
  - Yaxing Wang
  - Joost van de Weijer
  - Luis Herranz
  - Shangling Jui
publication: In *Proceedings of the IEEE/CVF International Conference on
  Computer Vision (ICCV)*
featured: true
tags:
  - Source Themes
projects:
  - internal-project
summary: ""
url_dataset: "#"
url_project: ""
publication_short: In *ICCV2021*
url_source: "#"
url_video: "#"
date: 2021-10-10T14:02:13.258Z
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
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Code: \[](<https://github.com/Albert0147/G-SFDA>)\[https://github.com/Albert0147/G-SFDA](<https://github.com/Albert0147/G-SFDA>).