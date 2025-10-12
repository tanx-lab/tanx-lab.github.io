---
title: Implementation of a Two-Dimensional Finite-Element Fatigue Damage Model with
  Peridynamics to Simulate Crack Growth in a Compact Tension Specimen

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Kyle Mansfield
- Levee Callahan
- Ting Xia
- Jenn-Terng Gau
- Jifu Tan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-24T19:29:55.675939Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Applied Sciences*'
publication_short: ''

doi: 10.3390/app14177858

abstract: The traditional finite element method (FEM) has limitations in accurately
  modeling crack propagation. Peridynamics, a nonlocal extension of the classical
  continuum theory, provides an alternative approach to remedy the limitations of
  the FEM but with a higher computational cost. In this paper, a peridynamic bond-based
  fatigue damage model is developed and incorporated into a commercial finite-element
  software (ABAQUS 2017) via user subroutines. Model-predicted results including the
  crack path spatial position and the damage accumulation rate were validated against
  empirical data. The predicted crack growth as a function of loading cycle and crack
  trajectory showed good agreement with the experimental data over 200,000 loading
  cycles. Therefore, the integration of the peridynamic bond-based fatigue damage
  model into existing FEM software provides an economical means to simulate complex
  fracture behaviors, such as crack growth, in a compact tension specimen examined
  in this paper.

# Summary. An optional shortened abstract.
summary: ''

tags:
- compact tension
- fatigue damage
- finite element modeling
- peridynamics

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
  url: https://www.mdpi.com/2076-3417/14/17/7858
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
