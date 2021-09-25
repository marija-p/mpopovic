---
title: "Efficient Lazy Theta* Path Planning over a Sparse Grid to Explore Large 3D Volumes with a Multirotor UAV"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Margarida Faria
- Ricardo Marín
- admin
- Ivan Maza
- Antidio Viguria

# Author notes (optional)
author_notes:
-
-

date: "2019-01-17T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Sensors*
publication_short: In *Sensors*

abstract: Exploring large, unknown, and unstructured environments is challenging for Unmanned Aerial Vehicles (UAVs), but they are valuable tools to inspect large structures safely and efficiently. The Lazy Theta* path-planning algorithm is revisited and adapted to generate paths fast enough to be used in real time and outdoors in large 3D scenarios. In real unknown scenarios, a given minimum safety distance to the nearest obstacle or unknown space should be observed, increasing the associated obstacle detection queries, and creating a bottleneck in the path-planning algorithm. We have reduced the dimension of the problem by considering geometrical properties to speed up these computations. On the other hand, we have also applied a non-regular grid representation of the world to increase the performance of the path-planning algorithm. In particular, a sparse resolution grid in the form of an octree is used, organizing the measurements spatially, merging voxels when they are of the same state. Additionally, the number of neighbors is trimmed to match the sparse tree to reduce the number of obstacle detection queries. The development methodology adopted was Test-Driven Development (TDD) and the outcome was evaluated in real outdoors flights with a multirotor UAV. In the results, the performance shows over 90 percent decrease in overall path generation computation time. Furthermore, our approach scales well with the safety distance increases. 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/1424-8220/19/1/174/pdf'
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