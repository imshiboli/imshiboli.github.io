---
title: 'Multi-Fidelity Bayesian Optimization via Deep Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shibo Li
  - Wei Xing
  - Mike Kirby
  - Shandian Zhe

# # # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
  

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Thirty-fourth Conference on Neural Information Processing Systems (<span style="color:blue">NeurIPS 2020</span>)*
publication_short: In *Thirty-fourth Conference on Neural Information Processing Systems (<span style="color:blue">NeurIPS 2020</span>)*

abstract: Bayesian optimization (BO) is a popular framework to optimize black-box functions. In many applications, the objective function can be evaluated at multiple fidelities to enable a trade-off between the cost and accuracy. To reduce the optimization cost, many multi-fidelity BO methods have been proposed. Despite their success, these methods either ignore or over-simplify the strong, complex correlations across the fidelities, and hence can be inefficient in estimating the objective function. To address this issue, we propose Deep Neural Network Multi-Fidelity Bayesian Optimization (DNN-MFBO) that can flexibly capture all kinds of complicated relationships between the fidelities to improve the objective function estimation and hence the optimization performance. We use sequential, fidelity-wise Gauss-Hermite quadrature and moment-matching to fulfill a mutual information-based acquisition function, which is computationally tractable and efficient. We show the advantages of our method in both synthetic benchmark datasets and real-world applications in engineering design. 

# Summary. An optional shortened abstract.
summary: Shibo Li

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.neurips.cc/paper/2020/file/60e1deb043af37db5ea4ce9ae8d2c9ea-Paper.pdf'
url_code: 'https://github.com/shib0li/DNN-MFBO'
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
