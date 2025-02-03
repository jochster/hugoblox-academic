---
title: 'LUCOOP: Leibniz University Cooperative Perception and Urban Navigation
  Dataset'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jeldrik Axmann
  - Rozhin Moftizadeh
  - admin
  - Benjamin Tennstedt
  - Qianqian Zou
  - Yunshuang Yuan
  - Dominik Ernst
  - Hamza Alkhatib
  - Claus Brenner
  - Steffen Schön

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-07-27T07:17:00.000Z'
doi: '10.1109/IV55152.2023.10186693'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE Intelligent Vehicles Symposium (IV)
publication_short: In *IEEE IV 2023*

abstract: >-
  Recently published datasets have been increasingly comprehensive with
  respect to their variety of simultaneously used sensors, traffic scenarios,
  environmental conditions, and provided annotations. However, these datasets
  typically only consider data collected by one independent vehicle. Hence,
  there is currently a lack of comprehensive, real-world, multi-vehicle datasets
  fostering research on cooperative applications such as object detection, urban
  navigation, or multi-agent SLAM. In this paper, we aim to fill this gap by
  introducing the novel LUCOOP dataset, which provides time-synchronized
  multi-modal data collected by three interacting measurement vehicles. The
  driving scenario corresponds to a follow-up setup of multiple rounds in an
  inner city triangular trajectory. Each vehicle was equipped with a broad
  sensor suite including at least one LiDAR sensor, one GNSS antenna, and up to
  three IMUs. Additionally, Ultra-Wide-Band (UWB) sensors were mounted on each
  vehicle, as well as statically placed along the trajectory enabling both V2V
  and V2X range measurements. Furthermore, a part of the trajectory was
  monitored by a total station resulting in a highly accurate reference
  trajectory. The LUCOOP dataset also includes a precise, dense 3D map point
  cloud, acquired simultaneously by a mobile mapping system, as well as an LOD2
  city model of the measurement area. We provide sensor measurements in a
  multi-vehicle setup for a trajectory of more than 4 km and a time interval of
  more than 26 minutes, respectively. Overall, our dataset includes more than
  54,000 LiDAR frames, approximately 700,000 IMU measurements, and more than 2.5
  hours of 10 Hz GNSS raw measurements along with 1 Hz data from a reference
  station. Furthermore, we provide more than 6,000 total station measurements
  over a trajectory of more than 1 km and 1,874 V2V and 267 V2X UWB
  measurements. Additionally, we offer 3D bounding box annotations for
  evaluating object detection approaches, as well as highly accurate ground
  truth poses for each vehicle throughout the measurement campaign.
  
# Summary. An optional shortened abstract.
summary: There is currently a lack of comprehensive, real-world, multi-vehicle
  datasets fostering research on cooperative applications such as object
  detection, urban navigation, or multi-agent SLAM. In this paper, we aim to
  fill this gap by introducing the novel LUCOOP dataset, which provides
  time-synchronized multi-modal data collected by three interacting measurement
  vehicles. 
  
tags:
  - integrity
  - multi-sensor fusion
  - autonomous driving
  - cooperative perception
  - urban navigation
  - dataset

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'mailto:suj@ife.uni-hannover.de'
url_code: ''
url_dataset: 'https://data.uni-hannover.de/dataset/lucoop-leibniz-university-cooperative-perception-and-urban-navigation-dataset'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
links:
  - name: Conference
    url: 'https://2023.ieee-iv.org/'
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
