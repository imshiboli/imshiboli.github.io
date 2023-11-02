---
title: 'Deep Multi-Fidelity Active Learning of High-Dimensional Outputs '

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shibo Li
  - Zheng Wang
  - Mike Kirby
  - Shandian Zhe

# # # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
  

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 25th International Conference on Artificial Intelligence and Statistics (AISTATS 2022)*
publication_short: In *The 25th International Conference on Artificial Intelligence and Statistics (AISTATS 2022)*

abstract: Many applications, such as in physical simulation and engineering design, demand we estimate functions with high-dimensional outputs. To reduce the expensive cost of generating training examples, we usually choose several fidelities to enable a cost/quality trade-off. In this paper, we consider the active learning task to automatically identify the fidelities and training inputs to query new examples so as to achieve the best learning benefit-cost ratio. To this end, we propose DMFAL, a Deep Multi-Fidelity Active Learning approach. We first develop a deep neural network-based multi-fidelity model for high-dimensional outputs, which can flexibly capture strong complex correlations across the outputs and fidelities to enhance the learning of the target function. We then propose a mutual information based acquisition function that extends the predictive entropy principle. To overcome the computational challenges caused by large output dimensions, we use the multi-variate delta method and moment-matching to estimate the output posterior, and Weinstein-Aronszajn identity to calculate and optimize the acquisition function. We show the advantage of our method in several applications of computational physics and engineering design. The code is available at https://github.com/shib0li/DMFAL. 

# Summary. An optional shortened abstract.
summary: Shibo Li

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v151/li22b.html'
url_code: 'https://github.com/shib0li/DMFAL'
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
