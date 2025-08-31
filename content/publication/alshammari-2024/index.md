---
title: Identifying Flare-indicative Photospheric Magnetic Field Parameters from Multivariate
  Time-series Data of Solar Active Regions

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Khaznah Alshammari
- Shah Muhammad Hamdi
- Soukaina Filali Boubrahimi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T01:35:12.676301Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*The Astrophysical Journal Supplement Series*'
publication_short: ''

doi: 10.3847/1538-4365/ad21e4

abstract: Photospheric magnetic field parameters are frequently used to analyze and
  predict solar events. Observation of these parameters over time, i.e., representing
  solar events by multivariate time-series (MVTS) data, can determine relationships
  between magnetic field states in active regions and extreme solar events, e.g.,
  solar flares. We can improve our understanding of these events by selecting the
  most relevant parameters that give the highest predictive performance. In this study,
  we propose a two-step incremental feature selection method for MVTS data using a
  deep-learning model based on long short-term memory (LSTM) networks. First, each
  MVTS feature (magnetic field parameter) is evaluated individually by a univariate
  sequence classifier utilizing an LSTM network. Then, the top performing features
  are combined to produce input for an LSTM-based multivariate sequence classifier.
  Finally, we tested the discrimination ability of the selected features by training
  downstream classifiers, e.g., Minimally Random Convolutional Kernel Transform and
  support vector machine. We performed our experiments using a benchmark data set
  for flare prediction known as Space Weather Analytics for Solar Flares. We compared
  our proposed method with three other baseline feature selection methods and demonstrated
  that our method selects more discriminatory features compared to other methods.
  Due to the imbalanced nature of the data, primarily caused by the rarity of minority
  flare classes (e.g., the X and M classes), we used the true skill statistic as the
  evaluation metric. Finally, we reported the set of photospheric magnetic field parameters
  that give the highest discrimination performance in predicting flare classes.

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
  url: https://dx.doi.org/10.3847/1538-4365/ad21e4
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
