---
title: "Informative Path Planning for Active Learning in Aerial Semantic Mapping"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- julius
- liren
- Federico Magistri
- Cyrill Stachniss
- admin

# Author notes (optional)
#author_notes:

date: "2022-08-23T15:21:54+05:30"
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

abstract: Semantic segmentation of aerial imagery is an important tool for mapping and earth observation. However, supervised deep learning models for segmentation rely on large amounts of high-quality labelled data, which is labour-intensive and time-consuming to generate. To address this, we propose a new approach for using unmanned aerial vehicles (UAVs) to autonomously collect useful data for model training. We exploit a Bayesian approach to estimate model uncertainty in semantic segmentation. During a mission, the semantic predictions and model uncertainty are used as input for terrain mapping. A key aspect of our pipeline is to link the mapped model uncertainty to a robotic planning objective based on active learning. This enables us to adaptively guide a UAV to gather the most informative terrain images to be labelled by a human for model training. Our experimental evaluation on real-world data shows the benefit of using our informative planning approach in comparison to static coverage paths in terms of maximising model performance and reducing labelling efforts. 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/abs/2203.01652.pdf'
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