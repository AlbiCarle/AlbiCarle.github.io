---
title: 'A novel method to derive personalized minimum viable recommendations for type 2 diabetes prevention based on counterfactual explanations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Marta Lenatti
  - admin
  - Aziz Guergachi
  - Karim Keshavjee
  - Maurizio Mongelli
  - Alessia Paglialonga

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-11-01T00:00:00Z'
doi: '0.1109/ACCESS.2022.3180026'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *PLOS ONE*
publication_short: In *PLOS ONE*

abstract: Despite the growing availability of artificial intelligence models for predicting type 2 diabetes, there is still a lack of personalized approaches to quantify minimum viable changes in biomarkers that may help reduce the individual risk of developing disease. The aim of this article is to develop a new method, based on counterfactual explanations, to generate personalized recommendations to reduce the one-year risk of type 2 diabetes. Ten routinely collected biomarkers extracted from Electronic Medical Records of 2791 patients at low risk and 2791 patients at high risk of type 2 diabetes were analyzed. Two regions characterizing the two classes of patients were estimated using a Support Vector Data Description classifier. Counterfactual explanations (i.e., minimal changes in input features able to change the risk class) were generated for patients at high risk and evaluated using performance metrics (availability, validity, actionability, similarity, and discriminative power) and a qualitative survey administered to seven expert clinicians. Results showed that, on average, the requested minimum viable changes implied a significant reduction of fasting blood sugar, systolic blood pressure, and triglycerides and a significant increase of high-density lipoprotein in patients at risk of diabetes. A significant reduction in body mass index was also recommended in most of the patients at risk, except in females without hypertension. In general, greater changes were recommended in hypertensive patients compared to non-hypertensive ones. The experts were overall satisfied with the proposed approach although in some cases the proposed recommendations were deemed insufficient to reduce the risk in a clinically meaningful way. Future research will focus on a larger set of biomarkers and different comorbidities, also incorporating clinical guidelines whenever possible. Development of additional mathematical and clinical validation approaches will also be of paramount importance.

# Summary. An optional shortened abstract.
summary: Counterfactual recommendations for treatment of type-2 diabetes.

#tags:
  #- Misclassification error control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/journal.pone.0272825.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0272825'
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