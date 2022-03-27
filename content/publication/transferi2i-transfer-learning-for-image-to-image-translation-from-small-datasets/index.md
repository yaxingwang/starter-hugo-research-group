---
title: "TransferI2I: Transfer Learning for Image-to-Image Translation from Small
  Datasets"
abstract: "Image-to-image (I2I) translation has matured in recent years and is
  able to generate high-quality realistic images. However, despite current
  success, it still faces important challenges when applied to small domains.
  Existing methods use transfer learning for I2I translation, but they still
  require the learning of millions of parameters from scratch. This drawback
  severely limits its application on small domains. In this paper, we propose a
  new transfer learning for I2I translation (TransferI2I). We decouple our
  learning process into the image generation step and the I2I translation step.
  In the first step we propose two novel techniques: source-target
  initialization and self-initialization of the adaptor layer. The former
  finetunes the pretrained generative model (e.g., StyleGAN) on source and
  target data. The latter allows to initialize all non-pretrained network
  parameters without the need of any data. These techniques provide a better
  initialization for the I2I translation. Second step performs the actual I2I
  translation using the learned weights in the first step. In addition, we
  introduce an auxiliary GAN that further facilitates the training of deep I2I
  systems even from small datasets. In extensive experiments on three datasets,
  (Animal faces, Birds, and Foods), we show that we outperform existing methods
  and that mFID improves on several datasets with over 25 points."
slides: null
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
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
date: 2021-10-10T13:34:22.408Z
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

Code: [](<https://github.com/yaxingwang/
TransferI2I>)[https://github.com/yaxingwang/ TransferI2I](<https://github.com/yaxingwang/
TransferI2I>).