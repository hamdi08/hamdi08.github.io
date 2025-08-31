---
title: Spatio-Temporal Graph Neural Networks for Streamflow Prediction in the Upper
  Colorado Basin

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Akhila Akkala
- Soukaina Filali Boubrahimi
- Shah Muhammad Hamdi
- Pouya Hosseinzadeh
- Ayman Nassar

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T01:05:33.315595Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Hydrology*'
publication_short: ''

doi: 10.3390/hydrology12030060

abstract: Streamflow prediction is vital for effective water resource management,
  enabling a better understanding of hydrological variability and its response to
  environmental factors. This study presents a spatio-temporal graph neural network
  (STGNN) model for streamflow prediction in the Upper Colorado River Basin (UCRB),
  integrating graph convolutional networks (GCNs) to model spatial connectivity and
  long short-term memory (LSTM) networks to capture temporal dynamics. Using 30 years
  of monthly streamflow data from 20 monitoring stations, the STGNN predicted streamflow
  over a 36-month horizon and was evaluated against traditional models, including
  random forest regression (RFR), LSTM, gated recurrent units (GRU), and seasonal
  auto-regressive integrated moving average (SARIMA). The STGNN outperformed these
  models across multiple metrics, achieving an R2 of 0.78, an RMSE of 0.81 mm/month,
  and a KGE of 0.79 at critical locations like Lees Ferry. A sequential analysis of
  input–output configurations identified the (36, 36) setup as optimal for balancing
  historical context and forecasting accuracy. Additionally, the STGNN showed strong
  generalizability when applied to other locations within the UCRB. These results
  underscore the importance of integrating spatial dependencies and temporal dynamics
  in hydrological forecasting, offering a scalable and adaptable framework to improve
  predictive accuracy and support adaptive water resource management in river basins.

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
  url: https://www.mdpi.com/2306-5338/12/3/60
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
