---
title: "Enviromental Mapping and Informative Path Planning for UAV-based Active Sensing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:

date: "2019-10-17T15:21:54+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: '*PhD Thesis, ETH Zurich*'
publication_short: '*PhD Thesis, ETH Zurich*'

abstract: 'Robotic platforms represent a new frontier for data acquisition in a wide range of monitoring and exploration missions, including agriculture, surveillance, post-disaster assessment, and environmental sensing. A key challenge to realize their full potential is deciding how an autonomous agent should act to gather the most useful data about an uncertain environment within the set of its resource constraints. To address this, this thesis investigates the problem of active sensing: in such scenarios, how can the actions of the agent be planned in order to maximize the efficiency of the data collection process? It proposes new methods for environmental mapping and informative path planning as crucial elements towards achieving this goal. The strategies are developed in the context of two distinct applications: (a) terrain monitoring, and (b) active sensing under localization uncertainty, with a focus on Unmanned Aerial Vehicle (UAV) systems.

The main contribution of this thesis is an informative planning framework that is applicable for general active sensing tasks. The overall approach integrates individual contributions on three different fronts, which aim to address the challenges associated with information gathering in uncertain 3-D environments with computationally limited systems. Firstly, a new method for environmental field mapping is presented for terrain monitoring scenarios. The strategy exploits a Gaussian Process (GP) model as a prior for recursive Bayesian data fusion with probabilistic, variable-resolution sensors. In doing so, it supports mapping using dense visual imagery without the computational burden of standard GP regression, making it suitable for online on-platform applications. Moreover, it accommodates noisy sensors with altitude-dependent performance, as relevant for UAV-based systems. Secondly, an online, adaptive informative path planning algorithm is introduced for generating continuous trajectories to collect data in resource-constrained missions. A key feature of the method is that it uses the output from a discrete grid search as an informed prior to initialize a trajectory optimization routine and thereby improve its convergence in a large and complex objective space. This strategy also enables trading off between computational efficiency and solution accuracy for deployment on systems with limited computing power. Finally, methods are proposed to account for the robot pose uncertainty in active sensing tasks. Unlike prior work, the approach propagates this uncertainty into both the mapping and planning modules towards improving the robustness and accuracy of information gathering. A new utility function is developed that allows the robot to auto matically trade off between exploiting the existing map to maintain good localization and exploring areas to acquire new data in a principled way, without relying on any manually-tuned parameters. The formulation is derived in the context of a GP-based monitoring scenario and is also applicable across different learning problems.

The developed framework is modular, and can be tailored to a wide range of active sensing problems. Extensive simulation studies were conducted to evaluate the approach, examining how it performs against existing methods both as an integrated system as well as in terms of its key components. The main findings show that the proposed approach effectively: (a) produces maps with similar certainty and accuracy in significantly less time compared to current planning strategies; (b) can focus on adaptively mapping specific areas of interest; and (c) improves upon both field map accuracy and irobot localization by accounting for the pose uncertainty in informative planning. Results using an experimental dataset demonstrate system integration and validation in a photorealistic UAV-based terrain monitoring scenario. Finally, field tests are presented to demonstrate the algorithms implemented and running in real-time on robots for various data gathering tasks, including vegetation mapping on a farm. The framework is made publicly available as an open-source package.'


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/428335/phd-thesis-popovic-a4.pdf?sequence=1&isAllowed=y'
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