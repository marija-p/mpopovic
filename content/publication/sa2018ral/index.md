---
title: "weedNet: Dense Semantic Weed Classification Using Multispectral Images and MAV for Smart Farming"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Inkyu Sa
- Zetao Chen
- admin
- Raghav Khanna
- Frank Liebisch
- Juan Nieto
- Roland Siegwart

# Author notes (optional)
#author_notes:

date: "2018-01-31T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters*
publication_short: In *IEEE Robotics and Automation Letters*

abstract: Selective weed treatment is a critical step in autonomous crop management as related to crop health and yield. However, a key challenge is reliable and accurate weed detection to minimize damage to surrounding plants. In this letter, we present an approach for dense semantic weed classification with multispectral images collected by a micro aerial vehicle (MAV). We use the recently developed encoder-decoder cascaded convolutional neural network, SegNet, that infers dense semantic classes while allowing any number of input image channels and class balancing with our sugar beet and weed datasets. To obtain training datasets, we established an experimental field with varying herbicide levels resulting in field plots containing only either crop or weed, enabling us to use the normalized difference vegetation index as a distinguishable feature for automatic ground truth generation. We train six models with different numbers of input channels and condition (fine tune) it to achieve ~0.8 F1-score and 0.78 area under the curve classification metrics. For the model deployment, an embedded Graphics Processing Unit (GPU) system (Jetson TX2) is tested for MAV integration. Dataset used in this letter is released to support the community and future work.



# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1709.03329.pdf'
url_code: 'https://github.com/inkyusa/weedNet'
url_dataset: 'https://github.com/inkyusa/weedNet/tree/master/data/Sequoia'
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