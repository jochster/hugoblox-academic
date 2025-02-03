---
title: 'Reliable overbounding for stochastic IMU error models using interval analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Steffen Schön
  - Elisa Gallon

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-09-24T19:05:41.986Z'
doi: 'https://doi.org/10.33012/2024.19874'

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
  Robust error modeling of stochastic errors over time, such as in multisensory 
  navigation, is crucial for integrity purposes. It can be addressed using the 
  recently developed Power Spectral Density (PSD) overbounding method. Prior works 
  have developed robust Inertial Measurement Unit (IMU) error models through PSD 
  bounding, involving four parameters modeling white noise, First-order Gauss 
  Markov random process (FOGMRP), and random walk components. This paper presents 
  a novel method to address the challenge of ensuring PSD overbounding for stochastic 
  IMU error models by providing reliable interval-valued parameter estimates. This 
  is inherently meaningful, given the fact that numerous feasible combinations of 
  the parameters are expected. Our approach leverages the interval analysis method, 
  estimating the parameters efficiently and autonomously, reducing dependency on 
  precise external information from manufacturers, which is necessary for existing 
  methods. The output solutions are in the form of a set approximated by a number 
  of four-dimensional interval boxes, allowing flexible selection by the users 
  based on the application of interest. The methodology was validated through 
  experiments using Safran STIM300 and MicroStrain 3DM-GQ4-45 IMUs under controlled, 
  static conditions. Its reliability, demonstrated by the experimental results in 
  terms of effectiveness and tightness of PSD bounding, will contribute to the 
  advancement of resilient INS applications and desired sequential RAIM to ensure 
  high integrity.
  
# Summary. An optional shortened abstract.
summary: 
  
tags:
  - IMU
  - integrity
  - interval mathematics
  - uncertainty modeling
  - error bounding

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
