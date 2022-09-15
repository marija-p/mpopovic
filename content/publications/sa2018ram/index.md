---
title: "Build Your Own Visual-Inertial Drone: A Cost-Effective and Open-Source Autonomous Drone"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Inkyu Sa
- Mina Kamel
- Michael Burri
- Michael Bloesch
- Raghav Khanna
- admin
- Juan Nieto
- Roland Siegwart

# Author notes (optional)
#author_notes:
#- Equal contribution
# Equal contribution

date: "2018-03-31T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics & Automation Magazine*
publication_short: In *IEEE Robotics & Automation Magazine*

abstract: This article describes an approach to building a cost-effective and research-grade visual-inertial (VI) odometry-aided vertical takeoff and landing (VTOL) platform. We utilize an off-the-shelf VI sensor, an onboard computer, and a quadrotor platform, all of which are factory calibrated and mass produced, thereby sharing similar hardware and sensor specifications [e.g., mass, dimensions, intrinsic and extrinsic of camera-inertial measurement unit (IMU) systems, and signal-to-noise ratio]. We then perform system calibration and identification, enabling the use of our VI odometry, multisensor fusion (MSF), and model predictive control (MPC) frameworks with off-the-shelf products. This approach partially circumvents the tedious parameter-tuning procedures required to build a full system. The complete system is extensively evaluated both indoors using a motioncapture system and outdoors using a laser tracker while performing hover and step responses and trajectory-following tasks in the presence of external wind disturbances. We achieve root-mean-square (rms) pose errors of 0.036 m with respect to reference hover trajectories. We also conduct relatively long distance (.180 m) experiments on a farm site, demonstrating a 0.82% drift error of the total flight distance. This article conveys the insights we acquired about the platform and sensor module and offers open-source code with tutorial documentation to the community.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1708.06652.pdf'
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