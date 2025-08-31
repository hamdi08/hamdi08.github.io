---
title: Impacts of Data Preprocessing and Sampling Techniques on Solar Flare Prediction
  from Multivariate Time Series Data of Photospheric Magnetic Field Parameters

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- MohammadReza EskandariNasab
- Shah Muhammad Hamdi
- Soukaina Filali Boubrahimi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T01:35:12.667345Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*The Astrophysical Journal Supplement Series*'
publication_short: ''

doi: 10.3847/1538-4365/ad7c4a

abstract: The accurate prediction of solar flares is crucial due to their risks to
  astronauts, space equipment, and satellite communication systems. Our research enhances
  solar flare prediction by employing sophisticated data preprocessing and sampling
  techniques for the Space Weather Analytics for Solar Flares (SWAN-SF) data set,
  a rich source of multivariate time series data of solar active regions. Our study
  adopts a multifaceted approach encompassing four key methodologies. Initially, we
  address over 10 million missing values in the SWAN-SF data set through our innovative
  imputation technique called fast Pearson correlation-based k-nearest neighbors imputation.
  Subsequently, we propose a precise normalization technique, called LSBZM normalization,
  tailored for time series data, merging various strategies (log, square root, Box–Cox,
  Z-score, and min–max) to uniformly scale the data set's 24 attributes (photospheric
  magnetic field parameters), addressing issues such as skewness. We also explore
  the “near decision boundary sample removal” technique to enhance the classification
  performance of the data set by effectively resolving the challenge of class overlap.
  Finally, a pivotal aspect of our research is a thorough evaluation of diverse oversampling
  and undersampling methods, including SMOTE, ADASYN, Gaussian noise injection, TimeGAN,
  Tomek links, and random undersampling, to counter the severe imbalance in the SWAN-SF
  data set, notably a 60:1 ratio of major (X and M) to minor (C, B, and FQ) flaring
  events in binary classification. To demonstrate the effectiveness of our methods,
  we use eight classification algorithms, including advanced deep-learning-based architectures.
  Our analysis shows significant true skill statistic scores, underscoring the importance
  of data preprocessing and sampling in time-series-based solar flare prediction.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

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
  url: https://dx.doi.org/10.3847/1538-4365/ad7c4a
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
