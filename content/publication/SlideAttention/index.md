---
title: "Slide-Transformer: Hierarchical Vision Transformer with Local Self-Attention"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tianzhu Ye
- Zhuofan Xia
- Shiji Song
- Gao Huang

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Vision and Pattern Recognition (CVPR) 2023*
publication_short: In *Computer Vision and Pattern Recognition (CVPR) 2023*

abstract: Self-attention has been playing an important role in the recent progress of Vision Transformer. Modern Transformers mainly adopt sparse global attention or window attention to alleviate the excessive computation complexity, while the former is inefficient in extracting local features, and the latter may be subject to some handcrafted designs. Comparably, local attention which constrains the receptive field of each query in its own neighboring pixels, enjoys the advantages of both convolution and self-attention, namely local inductive bias and adaptive feature extraction. Nevertheless, current local attention modules either use inefficient Im2Col function, or rely on specific CUDA kernels that are hard to generalize to devices without CUDA support. In this paper, we propose a novel local attention module, dubbed Slide Attention, by using only common convolution operations and achieving high efficiency, flexibility, and generalizability. Specifically, we first re-interpret the column-based Im2Col function from a new row-based view and use Depthwise Convolution as an efficient substitution. On this basis, we propose a deformed shifting module based on the re-parameterization technique, which further relaxes the fixed key/value positions to deformed features in the local region. In this way, our module realizes the local attention paradigm in both efficient and flexible manner. Extensive experiments show that our slide attention module is applicable to a variety of advanced Vision Transformer models and compatible with various hardware devices, and achieves consistently improved performances on comprehensive benchmarks.


# Summary. An optional shortened abstract.
summary: In this paper, we propose a novel local attention module, dubbed Slide Attention, by using only common convolution operations and achieving high efficiency, flexibility, and generalizability.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
