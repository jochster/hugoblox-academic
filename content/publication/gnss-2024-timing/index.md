---
title: 'Towards integrity monitoring for GNSS-based time synchronization in technical applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qianwen Lin
  - admin
  - Steffen Schön

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-09-20T19:05:41.986Z'
doi: 'https://doi.org/10.33012/2024.19740'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 37th International Technical Meeting of the Satellite Division of The Institute of Navigation*
publication_short: In *ION GNSS+ 2024*

abstract: >-
  This paper addresses the growing need for integrity monitoring in critical timing 
  applications, driven by increasing reliance on accurate and reliable timing in 
  sectors such as finance and telecommunications. As synchronization becomes more 
  crucial in these fields, ensuring the integrity of timing systems is essential 
  to avoid potential risks and disruptions. In response, we develop a comprehensive 
  integrity monitoring framework that introduces key concepts like Timing Errors (TE), 
  Timing Alert Limit (TAL), and Timing Protection Levels (TPL). Sector-specific TALs 
  are established to meet the stringent synchronization requirements of industries 
  like finance and mobile telecommunications. To verify the proposed framework, we 
  first examine scenarios with accessible ground truth, using open-sky datasets. 
  For cases where ground truth is absent, two theoretical models—one based on quadratic 
  polynomials and another utilizing Chebyshev polynomials—are employed to predict 
  timing errors and establish protection levels. These models are validated through 
  real-world scenarios, where continuous integrity monitoring is successfully 
  demonstrated. Our results show that equipping receivers with Chip-Scale Atomic 
  Clocks (CSACs) significantly improves the accuracy and reliability of integrity 
  monitoring. The residual-variance-based approach effectively handles lower-stability 
  clocks, such as those found in receivers with internal Temperature-Compensated 
  Crystal Oscillators (TCXOs). In contrast, the noise-levelbased approach fails in 
  such scenarios due to its reliance on nominal clock behavior. Notably, selecting 
  optimal time intervals for interpolation and extrapolation is crucial, especially 
  for handling unstable oscillators. The findings suggest that CSACs are highly 
  recommended for applications requiring robust integrity monitoring in timing, 
  with the residual-variance-based method offering reliable performance even in 
  less stable conditions. Future work will explore the impact of signal interference 
  on integrity monitoring and refine the optimization of time intervals for clock 
  error prediction.
  
# Summary. An optional shortened abstract.
summary: 
  
tags:
  - Timing
  - integrity
  - GNSS
  - stochastic modeling

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'mailto:suj@ife.uni-hannover.de'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
links:
  - name: Conference
    url: 'https://www.ion.org/gnss/index.cfm'
    icon: hero/book-open

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  filename: featured.png
#  caption: ''
#  focal_point: Smart
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
