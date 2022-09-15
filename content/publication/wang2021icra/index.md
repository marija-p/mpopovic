---
title: "Elastic and Efficient LiDAR Reconstruction for Large-Scale Exploration Tasks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yiduo Wang
- Nils Funk
- Milad Ramezani
- Sotiris Papatheodorou
- admin
- Marco Camurri
- Stefan Leutenegger
- Maurice Fallon

# Author notes (optional)
#author_notes:

date: "2021-05-17T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation*
publication_short: In *IEEE International Conference on Robotics and Automation*

abstract: We present an efficient, elastic 3D LiDAR reconstruction framework which can reconstruct up to maximum LiDAR ranges (60 m) at multiple frames per second, thus enabling robot exploration in large-scale environments. Our approach only requires a CPU. We focus on three main challenges of large-scale reconstruction- integration of long-range LiDAR scans at high frequency, the capacity to deform the reconstruction after loop closures are detected, and scalability for long-duration exploration. Our system extends upon a state-of-the-art efficient RGB-D volumetric reconstruction technique, called supereight, to support LiDAR scans and a newly developed submapping technique to allow for dynamic correction of the 3D reconstruction. We then introduce a novel pose graph clustering and submap fusion feature to make the proposed system more scalable for large environments. We evaluate the performance using two public datasets including outdoor exploration with a handheld device and a drone, and with a mobile robot exploring an underground room network. Experimental results demonstrate that our system can reconstruct at 3 Hz with 60 m sensor range and ~5 cm resolution, while state-of-the-art approaches can only reconstruct to 25 cm resolution or 20 m range at the same frequency. 



# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2010.09232.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=-_vtsAyHXOg'

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