---
title: "Autonomous Exploration and Inspection Path Planning for Aerial Robots Using the Robot Operating System"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Christos Papachristos
- Mina Kamel
- admin
- Shehryar Khattak
- Andreas Bircher
- Helen Oleynikova
- Tung Dang
- Frank Mascarich
- Kostas Alexis
- Roland Siegwart 

# Author notes (optional)
#author_notes:

date: "2018-07-17T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: 'In *Robot Operating System (ROS): The Complete Reference (Volume 3)*'
publication_short: 'In *Robot Operating System (ROS): The Complete Reference (Volume 3)*'

abstract: This use case chapter presents a set of algorithms for the problems of autonomous exploration, terrain monitoring and optimized inspection path planning using aerial robots. The autonomous exploration algorithms described employ a receding horizon structure to iteratively derive the action that the robot should take to optimally explore its environment when no prior map is available, with the extension to localization uncertainty--aware planning. Terrain monitoring is tackled by a finite--horizon informative planning algorithm that further respects time budget limitations. For the problem of optimized inspection with a model of the environment known a priori, an offline path planning algorithm is proposed. All methods proposed are characterized by computational efficiency and have been tested thoroughly via multiple experiments. The Robot Operating System corresponds to the common middleware for the outlined family of methods. By the end of this chapter, the reader should be able to use the open--source contributions of the algorithms presented, implement them from scratch, or modify them to further fit the needs of a particular autonomous exploration, terrain monitoring, or structural inspection mission using aerial robots. Four different open--source ROS packages (compatible with ROS Indigo, Jade and Kinetic) are released, while the repository https://github.com/unr-arl/informative-planning stands as a single point of reference for all of them.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/profile/Shehryar-Khattak/publication/326233319_Autonomous_Exploration_and_Inspection_Path_Planning_for_Aerial_Robots_Using_the_Robot_Operating_System/links/60c65ac84585157774d6bc96/Autonomous-Exploration-and-Inspection-Path-Planning-for-Aerial-Robots-Using-the-Robot-Operating-System.pdf'
url_code: 'https://github.com/unr-arl/informative-planning'
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