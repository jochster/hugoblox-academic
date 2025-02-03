---
title: 'Deterministic approaches for bounding GNSS uncertainty: A comparative analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Steffen Schön

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: 2022-04-07T17:39:00.969Z
doi: 10.1109/NAVITEC53682.2022.9847545

featured: true

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2022 10th Workshop on Satellite Navigation Technology (NAVITEC)*
publication_short: In *NAVITEC 2022*

abstract: >-
  Uncertainty modeling and bounding are of vital importance for high-integrity
  GNSS applications. Classical approaches are mostly developed in a stochastic
  manner with probabilistic assumptions. However, the exact error distribution
  is often unknown, and remaining systematics may persist, so that a purely
  stochastic modeling of all error sources will not be adequate, and alternative
  uncertainty bounding and propagation should be studied. 

  This paper introduces two deterministic approaches for GNSS uncertainty bounding 
  and compares them with the conventional least-squares method theoretically and 
  experimentally with simulated and real measurements. Both methods use deterministic 
  intervals to denote observation uncertainty, subsequently following a linear 
  uncertainty propagation instead of quadratic one. The interval extension of 
  least-squares transfers the uncertainty into the position domain in the form of 
  zonotope and further bound the stochasticity by the extended point confidence 
  domain. As a comparison, the other method takes advantage of geometrical constraints 
  and convex optimization, leading to a polytopic solution set and zonotopic 
  confidence region. We show their theoretical similarities and highlight different 
  interpretations in practice. Nevertheless, both are sufficient to account for both 
  random and systematic components of uncertainty.


# Summary. An optional shortened abstract.
summary: This paper introduces two deterministic approaches for GNSS
  uncertainty bounding and compares them with the conventional least-squares
  method theoretically and experimentally with simulated and real measurements.
  
tags:
  - GNSS
  - integrity
  - uncertainty modeling
  - interval mathematics

# Display this page in the Featured widget?
featured: true
draft: false

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
    url: 'https://atpi.eventsair.com/navitec-2022'
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
