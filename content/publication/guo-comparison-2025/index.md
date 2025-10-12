---
title: Comparison of dynamic mode decomposition with other data-driven models for
  lung cancer incidence rate prediction

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- L. Raymond Guo
- Jifu Tan
- M. Courtney Hughes

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-24T19:29:55.663276Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Frontiers in Public Health*'
publication_short: ''

doi: 10.3389/fpubh.2025.1472398

abstract: IntroductionPublic health data analysis is critical to understanding disease
  trends. Existing analysis methods struggle with the complexity of public health
  data, which includes both location and time factors. Machine learning offers powerful
  tools but can be computationally expensive and require specialized knowledge. Dynamic
  mode decomposition (DMD) is an alternative that offers efficient analysis with fewer
  resources. This study explores applying DMD in public health using lung cancer data
  and compares it with other machine learning models.MethodsWe analyzed lung cancer
  incidence data (2000–2021) from 1,013 US counties. Machine learning models (random
  forest, gradient boosting machine, support vector machine) were trained and optimized
  on the training data. We also employed time series, a linear regression model, and
  DMD for comparison. All models were evaluated based on their ability to predict
  2021 lung cancer incidence rates.ResultsThe time series model achieved the lowest
  root mean squared error, followed by random forest. Meanwhile, DMD had an RMSE similar
  to that of Random Forest. Nearly all counties in Kentucky had higher lung cancer
  incidence rates, while states like California, New Mexico, Utah, and Idaho showed
  lower trends.ConclusionIn summary, DMD offers a promising alternative for public
  health professionals to capture underlying trends and potentially have lower computational
  demands compared to other machine learning models.

# Summary. An optional shortened abstract.
summary: ''

tags:
- dynamic mode decomposition
- gradient boosting machine
- lung cancer
- machine learning
- public health data
- random forest

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
  url: https://www.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2025.1472398/full
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
