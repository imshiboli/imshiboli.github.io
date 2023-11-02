---
title: 'Analysis of Multivariate Scoring Functions for Automatic Unbiased Learning to Rank'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tao Yang
  - Shikai Fang
  - Shibo Li
  - Yulan Wang
  - Qingyao Ai

# # # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
  

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
publication_short: In *The 29th ACM International Conference on Information and Knowledge Management (CIKM 2020)*

abstract: Leveraging biased click data for optimizing learning to rank systems has been a popular approach in information retrieval. Because click data is often noisy and biased, a variety of methods have been proposed to construct unbiased learning to rank (ULTR) algorithms for the learning of unbiased ranking models. Among them, automatic unbiased learning to rank (AutoULTR) algorithms that jointly learn user bias models (i.e., propensity models) with unbiased rankers have received a lot of attention due to their superior performance and low deployment cost in practice. Despite their differences in theories and algorithm design, existing studies on ULTR usually use uni-variate ranking functions to score each document or result independently. On the other hand, recent advances in context-aware learning-to-rank models have shown that multivariate scoring functions, which read multiple documents together and predict their ranking scores jointly, are more powerful than uni-variate ranking functions in ranking tasks with human-annotated relevance labels. Whether such superior performance would hold in ULTR with noisy data, however, is mostly unknown. In this paper, we investigate existing multivariate scoring functions and AutoULTR algorithms in theory and prove that permutation invariance is a crucial factor that determines whether a context-aware learning-to-rank model could be applied to existing AutoULTR framework. Our experiments with synthetic clicks on two large-scale benchmark datasets show that AutoULTR models with permutation-invariant multivariate scoring functions significantly outperform those with uni-variate scoring functions and permutation-variant multivariate scoring functions.

# Summary. An optional shortened abstract.
summary: Shibo Li

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2008.09061'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
