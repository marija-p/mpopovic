---
title: "Adaptive-Resolution Gaussian Process Mapping for Efficient UAV-based Terrain Monitoring"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- liren
- julius
- Stefan Kiss
- Teresa Vidal-Calleja
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

abstract: Unmanned aerial vehicles (UAVs) are rapidly gaining popularity in a variety of environmental monitoring tasks. A key requirement for autonomous operation is the ability to perform efficient environmental mapping and path planning online, given their limited on-board resources constraining operation time and computational capacity. To address this, we present an adaptive-resolution approach for terrain mapping based on the Nd-tree structure and Gaussian Processes (GPs). Our approach enables retaining details in areas of interest using higher map resolutions while compressing information in uninteresting areas at coarser resolutions to achieve a compact map representation of the environment. A key aspect of our approach is an integral kernel encoding spatial correlation of 2D grid cells, which enables merging uninteresting grid cells in a theoretically sound way. Results show that our approach is more efficient in terms of time and memory consumption without compromising on mapping quality. The resulting adaptive-resolution map accelerates the on-line adaptive path planning as well. Both performance enhancement in mapping and planning facilitate the efficiency of autonomous environmental monitoring with UAVs. 


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2109.14257.pdf'
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