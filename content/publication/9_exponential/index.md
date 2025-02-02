---
title: 'Exact characterization of ε-Safe Decision Regions for exponential family distributions and Multi Cost SVM approximation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Teodoro Alamo
  - Fabrizio Dabbene
  - Maurizio Mongelli

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-01-29T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2501.17731'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Probabilistic guarantees on the prediction of data-driven classifiers are necessary to define models that can be considered reliable. This is a key requirement for modern machine learning in which the goodness of a system is measured in terms of trustworthiness, clearly dividing what is safe from what is unsafe. The spirit of this paper is exactly in this direction. First, we introduce a formal definition of {\epsilon}-Safe Decision Region, a subset of the input space in which the prediction of a target (safe) class is probabilistically guaranteed. Second, we prove that, when data come from exponential family distributions, the form of such a region is analytically determined and controllable by design parameters, i.e. the probability of sampling the target class and the confidence on the prediction. However, the request of having exponential data is not always possible. Inspired by this limitation, we developed Multi Cost SVM, an SVM based algorithm that approximates the safe region and is also able to handle unbalanced data. The research is complemented by experiments and code available for reproducibility.

# Summary. An optional shortened abstract.
summary: Exact characterization of epsilon-safe safety regions for exponential families distributions.

#tags:
  #- Misclassification error control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/arXiv_exponential.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2501.17731'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Safe ML

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---