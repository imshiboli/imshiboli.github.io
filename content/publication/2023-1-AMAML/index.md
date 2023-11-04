---
title: 'Meta-Learning with Adjoint Methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shibo Li
  - Zheng Wang
  - Akil Narayan
  - Mike Kirby
  - Shandian Zhe

# # # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
  

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 26th International Conference on Artificial Intelligence and Statistics (<span style="color:blue">AISTATS 2023</span>)*
publication_short: In *The 26th International Conference on Artificial Intelligence and Statistics (<span style="color:blue">AISTATS 2023</span>)*

abstract: Model Agnostic Meta-Learning (MAML) is widely used to find a good initialization for a family of tasks. Despite its success, a critical challenge in MAML is to calculate the gradient w.r.t. the initialization of a long training trajectory for the sampled tasks, because the computation graph can rapidly explode and the computational cost is very expensive. To address this problem, we propose Adjoint MAML (A-MAML). We view gradient descent in the inner optimization as the evolution of an Ordinary Differential Equation (ODE). To efficiently compute the gradient of the validation loss w.r.t. the initialization, we use the adjoint method to construct a companion, backward ODE. To obtain the gradient w.r.t. the initialization, we only need to run the standard ODE solver twice — one is forward in time that evolves a long trajectory of gradient flow for the sampled task; the other is backward and solves the adjoint ODE. We need not create or expand any intermediate computational graphs, adopt aggressive approximations, or impose proximal regularizers in the training loss. Our approach is cheap, accurate, and adaptable to different trajectory lengths. We demonstrate the advantage of our approach in both synthetic and real-world meta-learning tasks. The code is available at https://github.com/shib0li/Adjoint-MAML. 

# Summary. An optional shortened abstract.
summary: Shibo Li

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v206/li23c'
url_code: 'https://github.com/shib0li/Adjoint-MAML'
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
