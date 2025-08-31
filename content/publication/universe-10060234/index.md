---
title: Classification of Major Solar Flares from Extremely Imbalanced Multivariate
  Time Series Data Using Minimally Random Convolutional Kernel Transform

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Kartik Saini
- Khaznah Alshammari
- Shah Muhammad Hamdi
- Soukaina Filali Boubrahimi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T01:24:35.659589Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Universe*'
publication_short: ''

doi: 10.3390/universe10060234

abstract: Solar flares are characterized by sudden bursts of electromagnetic radiation
  from the Sun’s surface, and are caused by the changes in magnetic field states in
  active solar regions. Earth and its surrounding space environment can suffer from
  various negative impacts caused by solar flares, ranging from electronic communication
  disruption to radiation exposure-based health risks to astronauts. In this paper,
  we address the solar flare prediction problem from magnetic field parameter-based
  multivariate time series (MVTS) data using multiple state-of-the-art machine learning
  classifiers that include MINImally RandOm Convolutional KErnel Transform (MiniRocket),
  Support Vector Machine (SVM), Canonical Interval Forest (CIF), Multiple Representations
  Sequence Learner (Mr-SEQL), and a Long Short-Term Memory (LSTM)-based deep learning
  model. Our experiment is conducted on the Space Weather Analytics for Solar Flares
  (SWAN-SF) benchmark data set, which is a partitioned collection of MVTS data of
  active region magnetic field parameters spanning over nine years of operation of
  the Solar Dynamics Observatory (SDO). The MVTS instances of the SWAN-SF dataset
  are labeled by GOES X-ray flux-based flare class labels, and attributed to extreme
  class imbalance because of the rarity of the major flaring events (e.g., X and M).
  As a performance validation metric in this class-imbalanced dataset, we used the
  True Skill Statistic (TSS) score. Finally, we demonstrate the advantages of the
  MVTS learning algorithm MiniRocket, which outperformed the aforementioned classifiers
  without the need for essential data preprocessing steps such as normalization, statistical
  summarization, and class imbalance handling heuristics.

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
  url: https://www.mdpi.com/2218-1997/10/6/234
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
