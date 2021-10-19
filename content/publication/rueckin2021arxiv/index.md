---
title: "Adaptive Informative Path Planning Using Deep Reinforcement Learning for UAV-based Active Sensing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- julius
- liren
- admin

# Author notes (optional)
#author_notes:

date: "2021-09-28T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Aerial robots are increasingly being utilized for a wide range of environmental monitoring and exploration tasks. However, a key challenge is efficiently planning paths to maximize the information value of acquired data as an initially unknown environment is explored. To address this, we propose a new approach for informative path planning (IPP) based on deep reinforcement learning (RL). Bridging the gap between recent advances in RL and robotic applications, our method combines Monte Carlo tree search with an offline-learned neural network predicting informative sensing actions. We introduce several components making our approach applicable for robotic tasks with continuous high-dimensional state spaces and large action spaces. By deploying the trained network during a mission, our method enables sample-efficient online replanning on physical platforms with limited computational resources. Evaluations using synthetic data show that our approach performs on par with existing information-gathering methods while reducing runtime by a factor of 8-10. We validate the performance of our framework using real-world surface temperature data from a crop field. 


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2109.13570.pdf'
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