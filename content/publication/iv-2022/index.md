---
title: 'Towards integrity for GNSS-based urban navigation - challenges and
  lessons learned'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Steffen Schön
  - Kai-Niklas Baasch
  - Lucy Icking
  - Ali KarimiDoona
  - Qianwen Lin
  - Fabian Ruwisch
  - Anat Schaper
  - admin

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-06-05T18:00:35.596Z'
doi: '10.1109/IV51971.2022.9827402'

featured: true

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 33rd IEEE Integelligent Vehicles Symposium*
publication_short: In *IEEE IV 2022*

abstract: >-
  For safety critical applications like autonomous driving, high trust in the 
  reported navigation solution is mandatory. This trust can be expressed by the 
  navigation performance parameters, especially integrity. Multipath errors are 
  the most challenging error source in GNSS since only partial correction is 
  possible. In order to ensure high integrity of GNSS-based urban navigation, 
  signal propagation mechanisms and the potential error sources induced by the 
  complex measurement environment should be sufficiently understood. 

In this contribution, we report on recent progress on this topic in our group. 
We conducted various experiments in urban areas and investigated the behavior and 
magnitude of GNSS signal propagation errors. To this end, ray tracing algorithms 
combined with 3D city models are implemented to identify propagation obstructions 
and quantify propagation errors. A Fresnel zone-based criterion is exploited to 
determine the occurrence and magnitude of diffraction. GNSS Feature Maps are 
proposed to visualize the analyses and to predict situations with potential loss 
of integrity. 

To measure the integrity of urban navigation, we developed alternative set-based 
approaches in addition to the classical stochastic approach. Based on interval 
mathematics and geometrical constraints, they are sufficient to bound remaining 
systematic uncertainty and feasible for integrity applications.

# Summary. An optional shortened abstract.
summary: For safety critical applications like autonomous driving, high trust in
  the reported navigation solution is mandatory. This trust can be expressed by
  the navigation performance parameters, especially integrity. Multipath errors
  are the most challenging error source in GNSS since only partial correction is
  possible. In order to ensure high integrity of GNSS-based urban navigation,
  signal propagation mechanisms and the potential error sources induced by the
  complex measurement environment should be sufficiently understood.
  
tags:
  - urban navigation
  - GNSS
  - integrity
  - autonomous driving
  - Multipath effect
  - interval mathematics

# Display this page in the Featured widget?
featured: true

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
    url: 'https://www.iv2022.com'
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
