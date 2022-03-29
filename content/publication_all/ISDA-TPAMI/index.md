---
title: "Regularizing Deep Networks with Semantic Data Augmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yulin Wang
- Gao Huang
- Shiji Song
- admin
- Yitong Xia
- Cheng Wu


# Author notes (optional)
author_notes: ''

date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI) 2021*
publication_short: In *IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI) 2021*

abstract: Data augmentation is widely known as a simple yet surprisingly effective technique for regularizing deep networks. Conventional data augmentation schemes, e.g., flipping, translation or rotation, are low-level, data-independent and class-agnostic operations, leading to limited diversity for augmented samples. To this end, we propose a novel semantic data augmentation algorithm to complement traditional approaches. The proposed method is inspired by the intriguing property that deep networks are effective in learning linearized features, i.e., certain directions in the deep feature space correspond to meaningful semantic transformations, e.g., changing the background or view angle of an object. Based on this observation, translating training samples along many such directions in the feature space can effectively augment the dataset for more diversity. To implement this idea, we first introduce a sampling based method to obtain semantically meaningful directions efficiently. Then, an upper bound of the expected cross-entropy (CE) loss on the augmented training set is derived by assuming the number of augmented samples goes to infinity, yielding a highly efficient algorithm. In fact, we show that the proposed implicit semantic data augmentation (ISDA) algorithm amounts to minimizing a novel robust CE loss, which adds minimal extra computational cost to a normal training procedure. In addition to supervised learning, ISDA can be applied to semi-supervised learning tasks under the consistency regularization framework, where ISDA amounts to minimizing the upper bound of the expected KL-divergence between the augmented features and the original features. Although being simple, ISDA consistently improves the generalization performance of popular deep models (e.g., ResNets and DenseNets) on a variety of datasets, i.e., CIFAR-10, CIFAR-100, SVHN, ImageNet, and Cityscapes. Code for reproducing our results is available at [https://github.com/blackfeather-wang/ISDA-for-Deep-Networks](https://github.com/blackfeather-wang/ISDA-for-Deep-Networks).


# Summary. An optional shortened abstract.
summary: In this paper, we propose a novel semantic data augmentation (ISDA) algorithm to complement traditional approaches. In fact, we show that the proposed implicit semantic data augmentation (ISDA) algorithm amounts to minimizing a novel robust CE loss, which adds minimal extra computational cost to a normal training procedure.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/blackfeather-wang/ISDA-for-Deep-Networks'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://zhuanlan.zhihu.com/p/344953635'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: ''
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
