---
title: "Volumetric Occupancy Mapping With Probabilistic Depth Completion for Robotic Navigation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Florian Thomas
- Sotiris Papatheodorou
- Nils Funk
- Teresa Vidal-Calleja
- Stefan Leutenegger

# Author notes (optional)
author_notes:
- Equal contribution
- Equal contribution

date: "2021-03-31T15:21:54+05:30"
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

abstract: In robotic applications, a key requirement for safe and efficient motion planning is the ability to map obstacle-free space in unknown, cluttered 3D environments. However, commodity-grade RGB-D cameras commonly used for sensing fail to register valid depth values on shiny, glossy, bright, or distant surfaces, leading to missing data in the map. To address this issue, we propose a framework leveraging probabilistic depth completion as an additional input for spatial mapping. We introduce a deep learning architecture providing uncertainty estimates for the depth completion of RGB-D images. Our pipeline exploits the inferred missing depth values and depth uncertainty to complement raw depth images and improve the speed and quality of free space mapping. Evaluations on synthetic data show that our approach maps significantly more correct free space with relatively low error when compared against using raw data alone in different indoor environments; thereby producing more complete maps that can be directly used for robotic navigation tasks. The performance of our framework is validated using real-world data.



# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2012.03023.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=brSJPgu8IO4'

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