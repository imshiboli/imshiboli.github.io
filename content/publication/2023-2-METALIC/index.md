---
title: 'Meta Learning of Interface Conditions for Multi-Domain Physics-Informed Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shibo Li
  - Michael Penwarden
  - Yiming Xu
  - Conor Tillinghast
  - Akil Narayan
  - Mike Kirby
  - Shandian Zhe

# # # Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 40th International Conference on Machine Learning (ICML 2023)*
publication_short: In *The 40th International Conference on Machine Learning (ICML 2023)*

abstract: Physics-informed neural networks (PINNs) are emerging as popular mesh-free solvers for partial differential equations (PDEs). Recent extensions decompose the domain, apply different PINNs to solve the problem in each subdomain, and stitch the subdomains at the interface. Thereby, they can further alleviate the problem complexity, reduce the computational cost, and allow parallelization. However, the performance of multi-domain PINNs is sensitive to the choice of the interface conditions. While quite a few conditions have been proposed, there is no suggestion about how to select the conditions according to specific problems. To address this gap, we propose META Learning of Interface Conditions (METALIC), a simple, efficient yet powerful approach to dynamically determine appropriate interface conditions for solving a family of parametric PDEs. Specifically, we develop two contextual multi-arm bandit (MAB) models. The first one applies to the entire training course, and online updates a Gaussian process (GP) reward that given the PDE parameters and interface conditions predicts the performance. We prove a sub-linear regret bound for both UCB and Thompson sampling, which in theory guarantees the effectiveness of our MAB. The second one partitions the training into two stages, one is the stochastic phase and the other deterministic phase; we update a GP reward for each phase to enable different condition selections at the two stages to further bolster the flexibility and performance. We have shown the advantage of METALIC on four bench-mark PDE families.

# Summary. An optional shortened abstract.
summary: Shibo Li

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=e694Xvz6Q6'
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
