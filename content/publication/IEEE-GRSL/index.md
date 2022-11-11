---
title: "Multifeature Transformation and Fusion-Based Ship Detection With Small Targets and Complex Backgrounds"
authors:
- Mingfeng Zha
- Wenbin Qian
- Wenji Yang
- Yilu Xu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-07-14T00:00:00Z"
doi: "10.1109/LGRS.2022.3192559"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Geoscience and Remote Sensing Letters*"
publication_short: ""

abstract: With the development of deep learning, synthetic aperture radar (SAR) image ship detection based on the convolutional neural network has made significant progress. However, there are two problems: 1) the false alarm detection rate is high due to complex background and coherent speckle noise interference and 2) for smaller ship targets, missed detection is prone to occur. In this letter, a novel ship detection model based on multifeature transformation and fusion (MFTF-Net) is proposed to address the issues. First, to avoid the randomness of initial point selection and the influence of outlier points, the anchor frame clustering approach based on the K -medians++ algorithm is presented to cluster the object candidate frames. Second, the low-level feature information is passed to the high level by constructing a local enhancement network; then, an improved transformer structure is introduced to replace the last convolutional block of the backbone network to obtain rich contextual information. Finally, a four-scale residual feature fusion network is designed, which fully fuses the object’s detailed and semantic information. In addition, improved convolutional block attention module (CBAM) and squeeze and excitation (SE) attention mechanisms are applied in the lower two layers and upper two layers of the network output to reduce the interference of confusing information, respectively. The experimental results demonstrate that the proposed method is superior to the state-of-the-art 13 baseline models on SAR ship detection dataset (SSDD), high-resolution SAR images dataset (HRSID), and SAR-ship-dataset public datasets in terms of the mean average precision (mAP), recall, accuracy, and F1 metrics.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9833507
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
