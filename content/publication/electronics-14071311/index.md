---
title: 'Info-CELS: Informative Saliency Map-Guided Counterfactual Explanation for
  Time Series Classification'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Peiyu Li
- Omar Bahri
- Pouya Hosseinzadeh
- Soukaïna Filali Boubrahimi
- Shah Muhammad Hamdi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-08-31T00:55:26.005563Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Electronics*'
publication_short: ''

doi: 10.3390/electronics14071311

abstract: As the demand for interpretable machine learning approaches continues to
  grow, there is an increasing necessity for human involvement in providing informative
  explanations for model decisions. This is necessary for building trust and transparency
  in AI-based systems, leading to the emergence of the Explainable Artificial Intelligence
  (XAI) field. Recently, a novel counterfactual explanation model, CELS, has been
  introduced. CELS learns a saliency map for the interests of an instance and generates
  a counterfactual explanation guided by the learned saliency map. While CELS represents
  the first attempt to exploit learned saliency maps not only to provide intuitive
  explanations for the reason behind the decision made by the time series classifier
  but also to explore post hoc counterfactual explanations, it exhibits limitations
  in terms of its high validity for the sake of ensuring high proximity and sparsity.
  In this paper, we present an enhanced approach that builds upon CELS. While the
  original model achieved promising results in terms of sparsity and proximity, it
  faced limitations in terms of validity. Our proposed method addresses this limitation
  by removing mask normalization to provide more informative and valid counterfactual
  explanations. Through extensive experimentation on datasets from various domains,
  we demonstrate that our approach outperforms the CELS model, achieving higher validity
  and producing more informative explanations.

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
  url: https://www.mdpi.com/2079-9292/14/7/1311
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
