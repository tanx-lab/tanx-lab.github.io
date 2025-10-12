---
title: Flow pattern investigation of bionic fish by immersed boundary–lattice Boltzmann
  method and dynamic mode decomposition

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Dehong Fang
- Zhenwei Huang
- Jinsong Zhang
- Zanao Hu
- Jifu Tan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-24T19:29:55.588434Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Ocean Engineering*'
publication_short: ''

doi: 10.1016/j.oceaneng.2022.110823

abstract: The investigation of fish swimming is prevalent in the fields of biomimetic
  hydrodynamics and is important for research on the temporal–spatial evolvement of
  vortex structures around fish, the design and development of propulsion systems,
  the shape and structural design of bionic robot fish, and the energy-saving control
  of schooling robot fish swimming. Conventional numerical simulations of fish swimming
  depend on mesh establishment and testing. However, the deforming body of a swimming
  fish largely affects local grids and results in low simulation accuracy due to the
  uncertainties of mesh resolution and structures. The immersed boundary method adopted
  in this paper has many advantages, it can efficiently capture the details of the
  complex dynamics of solid surfaces. Through this method, the fish surface is discretized
  into Lagrangian points with dynamic coordinates for the performance of complicated
  dynamic motions. In this work, the immersed boundary–lattice Boltzmann method algorithm
  with a multi-direct forcing scheme based on Palabos is tested with the cases of
  flow past a sphere to validate its precision. Then, a function of harmonic oscillation
  is coupled with fish surface points to perform the level swimming of the RoboTuna
  fish at different Reynolds numbers. The evolvements of vortex structures around
  the fish body are analyzed on the basis of the Q-criterion. The processes of the
  deformation of streamlines around the fish tail into local swirling by tail paddling
  are revealed, and an angle of approximately 30° between the outer edges of the velocity
  contour and the line cross of the fish head emerges after the fluid domain develops
  into a stable state. Then, the data of the fluid fields are subjected to dynamic
  mode decomposition (DMD), wherein the single mode reveals the presence of up-and-down
  and axisymmetric patterns behind the fish body. Reconstruction and error calculation
  are performed to validate the accuracy of the DMD model, then DMD prediction is
  performed to obtain the flow pattern in the future state and error analysis is conducted.
  In this work, the mutual effects of the swimming fish and the fluid fields, the
  formation processes of the vortical fields around the fish tail, and the temporal–spatial
  evolvements of the structural dynamics of the fluid fields behind the fish body
  are investigated to provide fundamental information to investigations on propeller
  systems, flexible propulsion devices, the mechanisms of energy extraction from fluids
  by the fish tail, and the energy-saving strategies of fish schooling.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Fish swimming simulation
- Immersed boundary method
- Lattice Boltzmann method
- RoboTuna
- Vortex structures

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
  url: https://www.sciencedirect.com/science/article/pii/S0029801822002670
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
