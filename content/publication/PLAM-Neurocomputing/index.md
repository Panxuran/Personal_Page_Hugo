---
title: "PLAM: A plug-in module for flexible graph attention learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shiji Song
- Yiming Chen
- Liejun Wang
- Gao Huang


# Author notes (optional)
author_notes: ''

date: "2022-02-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing, 2022*
publication_short: In *Neurocomputing, 2022*

abstract: Graph Convolutional Networks (GCNs) are general deep representation learning models for graphstructured data. In this paper, we propose a simple Plug-in Attention Module (PLAM) to improve the representation power of GCNs, inspired by the recent success of the query-key mechanism in computer vision and natural language processing. With this module, our network is able to adaptively learn the weights from a node towards its neighbors. Different from existing attention-based GCNs, the proposed PLAM has several important properties. First, the parameter space for the attention module is isolated from that for feature learning. This ensures that the proposed approach can be conveniently applied to existing GCNs as a plug-in module. Second, the anchor node and neighbor nodes are treated separately when learning the attention weights, which further enhances the flexibility of our structure. Third, our
attention module extracts higher-level information by computing the inner product of the features between the anchor node and neighbor nodes, leading to significantly increased representation power. Last, we take a step forward and propose a novel structural encoding technique for the graph attention module to inject local and global structure information. Although being simple, our PLAM models have achieved state-of-the-art performances on graph-structured datasets under both the transductive and inductive settings. Additionally, experiments on image and point cloud datasets show potential applications of PLAM on several computer vision tasks.


# Summary. An optional shortened abstract.
summary: In this paper, we propose a simple Plug-in Attention Module (PLAM) to improve the representation power of GCNs, inspired by the recent success of the query-key mechanism in computer
vision and natural language processing.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0925231222000637'
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
