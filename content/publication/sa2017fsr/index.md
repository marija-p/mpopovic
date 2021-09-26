---
title: "Dynamic System Identification, and Control for a Cost-Effective and Open-Source Multi-rotor MAV"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Inkyu Sa
- Mina Kamel
- Raghav Khanna
- admin
- Juan Nieto
- Roland Siegwart

# Author notes (optional)
#author_notes:

date: "2017-11-17T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Field and Service Robotics*
publication_short: In *Field and Service Robotics*

abstract: This paper describes dynamic system identification, and full control of a cost-effective Multi-rotor micro-aerial vehicle (MAV). The dynamics of the vehicle and autopilot controllers are identified using only a built-in IMU and utilized to design a subsequent model predictive controller (MPC). Experimental results for the control performance are evaluated using a motion capture system while performing hover, step responses, and trajectory following tasks in the presence of external wind disturbances. We achieve root-mean-square (RMS) errors between the reference and actual trajectory of x = 0.021 m, y = 0.016 m, z = 0.029 m, roll = 0.392 ∘, pitch = 0.618 ∘, and yaw = 1.087 ∘ while performing hover. Although we utilize accurate state estimation provided from a motion capture system in an indoor environment, the proposed method is one of the non-trivial prerequisites to build any field or service aerial robots. This paper also conveys the insights we have gained about the commercial vehicle and returned to the community through an open-source code, and documentation.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'http://www.fsr.ethz.ch/papers/FSR_2017_paper_6.pdf'
url_code: 'https://github.com/ethz-asl/mav_dji_ros_interface'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=fm2yDgHRSWg&ab_channel=aslteam'

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