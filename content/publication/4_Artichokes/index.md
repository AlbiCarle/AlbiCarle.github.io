---
title: 'Artichoke deep learning detection network for site-specific agrochemicals UAS spraying'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alberto Sassu
  - Jacopo Motta
  - Alessandro Deidda
  - Luca Ghiani
  - admin
  - Giovanni Garibotto
  - Filippo Gambella

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-10-01T00:00:00Z'
doi: '10.1109/MIS.2021.3123669'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *Computers and Electronics in Agriculture*
publication_short: In *ELSEVIER*

abstract: Input optimization is a distinguishing characteristic of Precision Agriculture approaches, helping reduce the environmental impact and costs and increase vegetable production quality. Thanks to the high automation evolution of Unmanned Aerial Systems (UAS), a new approach derived from their combination with Deep Learning techniques is leading to significant improvements in agricultural management practices. The study aims at artichoke plants detection and georeferencing as a first step for an on-the-fly, real time, UAS spraying system, and use the gathered information to monitor crop development through a multi-temporal approach. A commercial UAS, equipped with an RGB sensor, acquired images of the artichoke field located in Sardinia (Italy) during the 2021–2022 season in different crop growth stages. The FPN (Feature Pyramid Network), trained and compared with the YOLOv5 (You Only Look Once) network, showed a high detection level with an average F1 score of around 90%, and satisfactory off-line performances on the Nvidia Jetson Nano board. YOLOv5 achieved the best overall result. The FPN recorded a lower recall, which is desirable to achieve a minimum number of detection errors and limit the leakage of agrochemicals on false-positive targets. The multi-temporal approach influenced detection performances, with an inverse response of precision and recall metrics. The growing index trend showed a distinct value in October, peaking at the beginning of December as expected. The proposed approach contributes to designing future automatic and reliable site-specific UAS agrochemicals application and the classification of management zones.


# Summary. An optional shortened abstract.
summary: Original deep object detector for smart agricolture using drones.

#tags:
#  - Misclassification error control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/artichoke.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/pii/S0168169923005732'
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