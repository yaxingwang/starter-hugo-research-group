---
title: "MineGAN: effective knowledge transfer from GANs to target domains with
  few images"
abstract: GANs largely increases the potential impact of generative models.
  Therefore, we propose a novel knowledge transfer method for generative models
  based on mining the knowledge that is most beneficial to a specific target
  domain, either from a single or multiple pretrained GANs. This is done using a
  miner network that identifies which part of the generative distribution of
  each pretrained GAN outputs samples closest to the target domain. Mining
  effectively steers GAN sampling towards suitable regions of the latent space,
  which facilitates the posterior finetuning and avoids pathologies of other
  methods, such as mode collapse and lack of flexibility. Furthermore, to
  prevent overfitting on small target domains, we introduce sparse subnetwork
  selection, that restricts the set of trainable neurons to those that are
  relevant for the target dataset. We perform comprehensive experiments on
  several challenging datasets using various GAN architectures (BigGAN,
  Progressive GAN, and StyleGAN) and show that the proposed method, called
  MineGAN, effectively transfers knowledge to domains with few target images,
  outperforming existing methods. In addition, MineGAN can successfully transfer
  knowledge from multiple pretrained GANs.
slides: null
url_pdf: https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_TransferI2I_Transfer_Learning_for_Image-to-Image_Translation_From_Small_Datasets_ICCV_2021_paper.pdf
publication_types:
  - "1"
authors:
  - Yaxing Wang
  - Abel Gonzalez-Garcia
  - David Berga
  - Luis Herranz
  - Fahad Shahbaz Khan
  - Joost van de Weijer
publication: CVPR2020
featured: true
tags:
  - Source Themes
projects:
  - internal-project
summary: ""
url_dataset: "#"
url_project: ""
publication_short: CVPR2020
url_source: "#"
url_video: "#"
date: 2020-06-14T07:07:11.452Z
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
CVPR2020. Code:<https://github.com/yaxingwang/MineGAN>