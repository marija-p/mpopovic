---
title: "Adaptive-Resolution Field Mapping Using Gaussian Process Fusion With Integral Kernels"

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

date: "2022-07-01T15:21:54+05:30"
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

abstract: Unmanned aerial vehicles are rapidly gaining popularity in many environmental monitoring tasks. A prerequisite for their autonomous operation is the ability to perform efficient and accurate mapping online, given limited on-board resources constraining operation time and computational capacity. To address this, we present an online adaptive-resolution approach for field mapping based on Gaussian Process fusion, a strategy in which Bayesian fusion is applied to update a Gaussian Process prior map. A key aspect of our approach is an integral kernel encoding spatial correlation over the areas of grid cells. This enables efficient information compression in uninteresting areas to achieve a compact map representation while maintaining spatial correlations in a theoretically sound fashion. We evaluate the performance of our approach on both synthetic and real-world data. Results show that our method is more efficient in terms of mapping time and memory consumption without compromising on map quality. Further, we integrate our mapping strategy into an adaptive path planning framework to show that it facilitates information gathering efficiency in online settings.


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