---
title: Enhancing Monthly Streamflow Prediction Using Meteorological Factors and Machine
  Learning Models in the Upper Colorado River Basin

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Saichand Thota
- Ayman Nassar
- Soukaina Filali Boubrahimi
- Shah Muhammad Hamdi
- Pouya Hosseinzadeh

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T01:05:33.474443Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Hydrology*'
publication_short: ''

doi: 10.3390/hydrology11050066

abstract: Streamflow prediction is crucial for planning future developments and safety
  measures along river basins, especially in the face of changing climate patterns.
  In this study, we utilized monthly streamflow data from the United States Bureau
  of Reclamation and meteorological data (snow water equivalent, temperature, and
  precipitation) from the various weather monitoring stations of the Snow Telemetry
  Network within the Upper Colorado River Basin to forecast monthly streamflow at
  Lees Ferry, a specific location along the Colorado River in the basin. Four machine
  learning models—Random Forest Regression, Long short-term memory, Gated Recurrent
  Unit, and Seasonal AutoRegresive Integrated Moving Average—were trained using 30
  years of monthly data (1991–2020), split into 80% for training (1991–2014) and 20%
  for testing (2015–2020). Initially, only historical streamflow data were used for
  predictions, followed by including meteorological factors to assess their impact
  on streamflow. Subsequently, sequence analysis was conducted to explore various
  input-output sequence window combinations. We then evaluated the influence of each
  factor on streamflow by testing all possible combinations to identify the optimal
  feature combination for prediction. Our results indicate that the Random Forest
  Regression model consistently outperformed others, especially after integrating
  all meteorological factors with historical streamflow data. The best performance
  was achieved with a 24-month look-back period to predict 12 months of streamflow,
  yielding a Root Mean Square Error of 2.25 and R-squared (R2) of 0.80. Finally, to
  assess model generalizability, we tested the best model at other locations—Greenwood
  Springs (Colorado River), Maybell (Yampa River), and Archuleta (San Juan) in the
  basin.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://www.mdpi.com/2306-5338/11/5/66
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
