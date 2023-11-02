---
title: 'Infinite-Fidelity Surrogate Learning via High-order Gaussian Processes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shibo Li
  - Li Shi
  - Shandian Zhe

# # # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
  

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *1st Workshop on the Synergy of Scientific and Machine Learning Modeling @ ICML2023*
publication_short: In *1st Workshop on the Synergy of Scientific and Machine Learning Modeling @ ICML2023*

abstract: Multi-fidelity learning is popular in computational physics. While the fidelity is often up to the choice of mesh spacing and hence is continuous in nature, most methods only model finite, discrete fidelities. The recent work (Li et al., 2022) proposes the first continuous-fidelity surrogate model, named infinite-fidelity coregionalization (IFC), which uses a neural Ordinary Differential Equation (ODE) to capture the rich information within the infinite, continuous fidelity space. While showing state-of-the-art predictive performance, IFC is computationally expensive in training and is difficult for uncertainty quantification. To overcome these limitations, we propose Infinite-Fidelity High-Order Gaussian Process (IF-HOGP), based on the recent GP high-dimensional output regression model HOGP. By tensorizing the output and using a product kernel at each mode, HOGP can highly efficiently estimate the mapping from the PDE parameters to the high-dimensional solution output, without the need for any low-rank approximation. We made a simple extension by injecting the continuous fidelity variable into the input, and applying a neural network transformation before feeding the input into the kernel. On three benchmark PDEs, IF-HOGP achieves prediction accuracy better than or close to IFC, yet gains 380x speed-up and 87.5% memory reduction. Meanwhile, uncertainty calibration for IF-HOGP is straightforward.

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
