---
title: Improving Solar Energetic Particle Event Prediction through Multivariate Time
  Series Data Augmentation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pouya Hosseinzadeh
- Soukaina Filali Boubrahimi
- Shah Muhammad Hamdi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T00:55:26.135482Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*The Astrophysical Journal Supplement Series*'
publication_short: ''

doi: 10.3847/1538-4365/ad1de0

abstract: Solar energetic particles (SEPs) are associated with extreme solar events
  that can cause major damage to space- and ground-based life and infrastructure.
  High-intensity SEP events, particularly ∼100 MeV SEP events, can pose severe health
  risks for astronauts owing to radiation exposure and affect Earth’s orbiting satellites
  (e.g., Landsat and the International Space Station). A major challenge in the SEP
  event prediction task is the lack of adequate SEP data because of the rarity of
  these events. In this work, we aim to improve the prediction of ∼30, ∼60, and ∼100
  MeV SEP events by synthetically increasing the number of SEP samples. We explore
  the use of a univariate and multivariate time series of proton flux data as input
  to machine-learning-based prediction methods, such as time series forest (TSF).
  Our study covers solar cycles 22, 23, and 24. Our findings show that using data
  augmentation methods, such as the synthetic minority oversampling technique, remarkably
  increases the accuracy and F1-score of the classifiers used in this research, especially
  for TSF, where the average accuracy increased by 20%, reaching around 90% accuracy
  in the ∼100 MeV SEP prediction task. We also achieved higher prediction accuracy
  when using the multivariate time series data of the proton flux. Finally, we build
  a pipeline framework for our best-performing model, TSF, and provide a comprehensive
  hierarchical classification of the ∼100, ∼60, and ∼30 MeV and non-SEP prediction
  scenarios.

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
  url: https://dx.doi.org/10.3847/1538-4365/ad1de0
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
