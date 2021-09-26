---
title: "Multiresolution mapping and informative path planning for UAV-based terrain monitoring"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Teresa Vidal-Calleja
- Gregory Hitz
- Inkyu Sa
- Roland Siegwart
- Juan Nieto

# Author notes (optional)
#author_notes:

date: "2017-09-17T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*

abstract: Unmanned aerial vehicles (UAVs) can offer timely and cost-effective delivery of high-quality sensing data. However, deciding when and where to take measurements in complex environments remains an open challenge. To address this issue, we introduce a new multiresolution mapping approach for informative path planning in terrain monitoring using UAVs. Our strategy exploits the spatial correlation encoded in a Gaussian Process model as a prior for Bayesian data fusion with probabilistic sensors. This allows us to incorporate altitude-dependent sensor models for aerial imaging and perform constant-time measurement updates. The resulting maps are used to plan information-rich trajectories in continuous 3-D space through a combination of grid search and evolutionary optimization. We evaluate our framework on the application of agricultural biomass monitoring. Extensive simulations show that our planner performs better than existing methods, with mean error reductions of up to 45% compared to traditional “lawnmower” coverage. We demonstrate proof of concept using a multirotor to map color in different environments.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1703.02854.pdf'
url_code: 'https://github.com/ethz-asl/tmplanner'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
 -->