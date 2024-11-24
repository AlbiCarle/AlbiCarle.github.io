---
title: 'Conformal predictions for probabilistically robust scalable machine learning classification'

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

date: '2024-07-01T00:00:00Z'
doi: 'https://doi.org/10.1007/s10994-024-06571-6'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *Springer Nature*
publication_short: In *Springer*

abstract: Conformal predictions make it possible to define reliable and robust learning algorithms. But they are essentially a method for evaluating whether an algorithm is good enough to be used in practice. To define a reliable learning framework for classification from the very beginning of its design, the concept of scalable classifier was introduced to generalize the concept of classical classifier by linking it to statistical order theory and probabilistic learning theory. In this paper, we analyze the similarities between scalable classifiers and conformal predictions by introducing a new definition of a score function and defining a special set of input variables, the conformal safety set, which can identify patterns in the input space that satisfy the error coverage guarantee, i.e., that the probability of observing the wrong (possibly unsafe) label for points belonging to this set is bounded by a predefined error level. We demonstrate the practical implications of this framework through an application in cybersecurity for identifying DNS tunneling attacks. Our work contributes to the development of probabilistically robust and reliable machine learning models.

# Summary. An optional shortened abstract.
summary: A conformal prediction approach to define safety regions for misclassification error control.

#tags:
  #- Misclassification error control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/springer_conformal.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/article/10.1007/s10994-024-06571-6'
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