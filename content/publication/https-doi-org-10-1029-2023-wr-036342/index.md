---
title: Spatiotemporal Data Augmentation of MODIS-Landsat Water Bodies Using Adversarial
  Networks

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Soukaina Filali Boubrahimi
- Ashit Neema
- Ayman Nassar
- Pouya Hosseinzadeh
- Shah Muhammad Hamdi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T00:57:11.068651Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Water Resources Research*'
publication_short: ''

doi: https://doi.org/10.1029/2023WR036342

abstract: Abstract With increasing demands for precise water resource management,
  there is a growing need for advanced techniques in mapping water bodies. The currently
  deployed satellites provide complementary data that are either of high spatial or
  high temporal resolutions. As a result, there is a clear trade-off between space
  and time when considering a single data source. For the efficient monitoring of
  multiple environmental resources, various Earth science applications need data at
  high spatial and temporal resolutions. To address this need, many data fusion methods
  have been described in the literature, that rely on combining data snapshots from
  multiple sources. Traditional methods face limitations due to sensitivity to atmospheric
  disturbances and other environmental factors, resulting in noise, outliers, and
  missing data. This paper introduces Hydrological Generative Adversarial Network
  (Hydro-GAN), a novel machine learning-based method that utilizes modified GANs to
  enhance boundary accuracy when mapping low-resolution MODIS data to high-resolution
  Landsat-8 images. We propose a new non-saturating loss function for the Hydro-GAN
  generator, which maximizes the log of discriminator probabilities to promote stable
  updates and aid convergence. By focusing on reducing squared differences between
  real and synthetic images, our approach enhances training stability and overall
  performance. We specifically focus on mapping water bodies using MODIS and Landsat-8
  imagery due to their relevance in water resource management tasks. Our experimental
  results demonstrate the effectiveness of Hydro-GAN in generating high-resolution
  water body maps, outperforming traditional methods in terms of boundary accuracy
  and overall quality.

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
  url: https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2023WR036342
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
