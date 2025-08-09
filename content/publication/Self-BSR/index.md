---
title: "Self-BSR Self-supervised Image Denoising and Destriping Based on Blind-Spot Regularization"
authors:
- Chao Qu
- Zewei Chen
- Jingyuan Zhang
- Xiaoyu Chen
- Jing Han
author_notes:
- ""
- ""
date: "2025-04-09T00:00:00Z"
doi: "10.1109/TCSVT.2025.3559214"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Circuits and Systems for Video Technology [Accept]"
publication_short: "TCSVT"

abstract: Digital images captured by unstable imaging systems often simultaneously suffer from random noise and stripe noise. Due to the complex noise distribution, denoising and destriping methods based on simple handcrafted priors may leave residual noise. Although supervised methods have achieved some progress, they rely on large-scale noisy-clean image pairs, which are challenging to obtain in practice. To address these problems, we propose a self-supervised image denoising and destriping method based on blind-spot regularization, named Self-BSR. This method transforms the overall denoising and destriping problem into a modeling task for two spatially correlated signals: image and stripe. Specifically, blind-spot regularization leverages spatial continuity learned by the improved blind-spot network to separately constrain the reconstruction of image and stripe while suppressing pixel-wise independent noise. This regularization has two advantages: first, it is adaptively formulated based on implicit network priors, without any explicit parametric modeling of image and noise; second, it enables Self-BSR to learn denoising and destriping only from noisy images. In addition, we introduce the directional feature unshuffle in Self-BSR, which extracts multi-directional information to provide discriminative features for separating image from stripe. Furthermore, the featureresampling refinement is proposed to improve the reconstruction ability of Self-BSR by resampling pixels with high spatial correlation in the receptive field. Extensive experiments on synthetic and real-world datasets demonstrate significant advantages of the proposed method over existing methods in denoising and destriping performance.

# Summary. An optional shortened abstract.
summary: We propose Self-BSR, a self-supervised image denoising and destriping method based on blind-spot regularization. This approach reformulates the overall denoising and destriping problem as a modeling task involving two spatially correlated signals: the image and the stripe.

tags:
  - destriping
  - denoising
featured: true
featured1: true
# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10960454
url_code: 'https://github.com/Jocobqc/Self-BSR'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
