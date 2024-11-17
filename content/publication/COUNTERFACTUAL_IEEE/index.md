---
title: 'Counterfactual Building and Evaluation via eXplainable Support Vector Data Description'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Marta Lenatti
  - Alessia Paglialonga
  - Maurizio Mongelli

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-05-01T00:00:00Z'
doi: '0.1109/ACCESS.2022.3180026'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Acces*
publication_short: In *IEEE*

abstract: Increasingly in recent times, the mere prediction of a machine learning algorithm is considered
insufficient to gain complete control over the event being predicted. A machine learning algorithm should
be considered reliable in the way it allows to extract more knowledge and information than just having
a prediction at hand. In this perspective, the counterfactual theory plays a central role. By definition,
a counterfactual is the smallest variation of the input such that it changes the predicted behaviour. The paper
addresses counterfactuals through Support Vector Data Description (SVDD), empowered by explainability
and metric for assessing the counterfactual quality. After showing the specific case in which an analytical
solution may be found (under Euclidean distance and linear kernel), an optimisation problem is posed for any
type of distances and kernels. The vehicle platooning application is the use case considered to demonstrate
how the outlined methodology may offer support to safety-critical applications as well as how explanation
may shed new light into the control of the system at hand.


# Summary. An optional shortened abstract.
summary: Construction of counterfactual explanations for SVDD-based binary classification.

tags:
  #- Misclassification error control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/paperCounterfactual.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/9787552'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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