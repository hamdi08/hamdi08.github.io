---
title: ML-Based Streamflow Prediction in the Upper Colorado River Basin Using Climate
  Variables Time Series Data

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pouya Hosseinzadeh
- Ayman Nassar
- Soukaina Filali Boubrahimi
- Shah Muhammad Hamdi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T00:58:36.669218Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Hydrology*'
publication_short: ''

doi: 10.3390/hydrology10020029

abstract: Streamflow prediction plays a vital role in water resources planning in
  order to understand the dramatic change of climatic and hydrologic variables over
  different time scales. In this study, we used machine learning (ML)-based prediction
  models, including Random Forest Regression (RFR), Long Short-Term Memory (LSTM),
  Seasonal Auto- Regressive Integrated Moving Average (SARIMA), and Facebook Prophet
  (PROPHET) to predict 24 months ahead of natural streamflow at the Lees Ferry site
  located at the bottom part of the Upper Colorado River Basin (UCRB) of the US. Firstly,
  we used only historic streamflow data to predict 24 months ahead. Secondly, we considered
  meteorological components such as temperature and precipitation as additional features.
  We tested the models on a monthly test dataset spanning 6 years, where 24-month
  predictions were repeated 50 times to ensure the consistency of the results. Moreover,
  we performed a sensitivity analysis to identify our best-performing model. Later,
  we analyzed the effects of considering different span window sizes on the quality
  of predictions made by our best model. Finally, we applied our best-performing model,
  RFR, on two more rivers in different states in the UCRB to test the model’s generalizability.
  We evaluated the performance of the predictive models using multiple evaluation
  measures. The predictions in multivariate time-series models were found to be more
  accurate, with RMSE less than 0.84 mm per month, R-squared more than 0.8, and MAPE
  less than 0.25. Therefore, we conclude that the temperature and precipitation of
  the UCRB increases the accuracy of the predictions. Ultimately, we found that multivariate
  RFR performs the best among four models and is generalizable to other rivers in
  the UCRB.

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
  url: https://www.mdpi.com/2306-5338/10/2/29
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
