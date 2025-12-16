---
title: 'Provably Efficient and Robust Conformal Prediction under a Realistic Threat Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Luca Oneto
  - Davide Anguita
  - Fabio Roli

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-09-29T00:00:00Z'
doi: 'https://proceedings.mlr.press/v266/carlevaro25a.html'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *PMLR*
publication_short: In *PMLR*

abstract: Robust conformal prediction is a model-agnostic technique designed to construct predictive sets with guaranteed coverage, assuming data exchangeability, even under adversarial attacks. Two primary strategies have been explored to address vulnerabilities to these attacks. The first strategy employs randomization, which is computationally efficient but fails to provide formal performance guarantees without resulting in overly conservative predictive sets. The second strategy involves formal verification, which restores coverage guarantees but leads to excessively conservative predictive sets and prohibitive computational overhead. Indeed, verification generally becomes NP-hard as it attempts to cope with attacks that are practically impossible, rendering some security claims unfalsifiable. In this paper, we propose a novel, provably efficient robust conformal prediction method by clearly defining a realistic threat model. Specifically, we assume explicit knowledge of the set of potential adversarial attacks, aligning our approach with standard certification procedures designed to certify against specific, identified threats. We demonstrate that attacks targeting the model can effectively be reframed as attacks on the score function, allowing us to recalibrate the score quantile to account for these known attacks and thereby restore desired coverage guarantees. It is worth noting that our approach allows to easily incorporate unknown or emerging (zero-day) attacks upon discovery, thus reestablishing coverage guarantees. By avoiding computationally intensive verification and operating under realistic threat assumptions, our approach achieves both efficiency and provable robustness. Empirical evaluations on real-world classification datasets and comparisons with state-of-the-art methods support the effectiveness and practicality of our proposed solution.

# Summary. An optional shortened abstract.
summary: Conformal prediction for adversarially robust machine learning.

#tags:
  #- Misclassification error control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/carlevaro25a.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://proceedings.mlr.press/v266/carlevaro25a.html'
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