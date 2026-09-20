---
# Leave the homepage title empty to use the site title
title: 'Alberto Carlevaro'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
        #text:
        #  color: black  # Set text color to black
        image:
          # Add your image background to `assets/media/`.
          filename: IMG_0425.png #IMG_8704_v1.jpeg #stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
       I am a mathematician and computer scientist working at the intersection of machine learning, trustworthy artificial intelligence, and scientific and industrial applications.

       I graduated from the University of Genoa (<a href="https://unige.it/en" target="_blank">UNIGE</a>) in 2020 with a Master's degree in Applied Mathematics from the Department of Mathematics (<a href="https://dima.unige.it/" target="_blank">DIMA</a>). In 2024, I received my Ph.D. in Science and Technology for Electronic and Telecommunication Engineering from the Department of Electrical, Electronic and Telecommunications Engineering (<a href="https://diten.unige.it/en" target="_blank">DITEN</a>), where my research focused on mathematical methods for explainable and reliable machine learning. From 2023 to 2024, I was a Visiting Research Scholar in the Electrical Engineering and Computer Sciences (<a href="https://eecs.berkeley.edu/" target="_blank">EECS</a>) department at <a href="https://www.berkeley.edu/" target="_blank">UC Berkeley</a>, working with Prof. Alberto Sangiovanni Vincentelli on Physics-Informed Machine Learning and the integration of physical knowledge into data-driven models.

       My current academic research focuses on Trustworthy Artificial Intelligence (TAI), with particular emphasis on Reliable Machine Learning, Robust and Adversarial Machine Learning, and Uncertainty Quantification, including Conformal Prediction and Order Statistics. I am also interested in Machine Learning for Science, particularly Physics-Informed Neural Networks (PINNs) and their application to learning unknown dynamics and modelling discrepancies between physical models and observed data.

       Alongside my academic research, I have developed substantial experience in publicly funded research and industrial innovation. Since July 2024, I have been working as a Research Project Manager and AI Researcher at <a href="https://www.aitek.it/en/" target="_blank">Aitek S.p.A.</a>, where I contribute to the development and management of funded research projects involving Artificial Intelligence, computer vision, logistics, and the digital transformation of critical infrastructures such as ports and road networks. My work includes research proposal development, project management, coordination with academic and industrial partners, and technical research activities. I am also a researcher at the Institute of Electronics and Information and Telecommunications Engineering (<a href="https://www.ieiit.cnr.it/it/" target="_blank">CNR-IEIIT</a>) of the National Research Council of Italy.

       I am particularly interested in research that connects rigorous mathematical methods with real-world AI systems, bridging academic research, competitive research funding, and industrial applications.

       Proficient in Python and MATLAB.

       If you'd like to get in touch, feel free to send me a message in Italian 🇮🇹 or English 🇺🇸.
 

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: grid
      columns: '1'
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: '' #Hype stuff
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    # Page type to display. E.g. post, talk, publication...
  #    page_type: post
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
      # Filter on criteria
  #    filters:
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: date-title-summary
      # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
  #- block: cta-card
  #  demo: true # Only display this section in the Hugo Blox Builder demo site
  #  content:
  #    title: 👉 Build your own academic website like this
  #    text: |-
  #      This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.
  #
  #      <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>
  #
  #      Easily build anything with blocks - no-code required!
  #      
  #      From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #    button:
  #      text: Get Started
  #      url: https://hugoblox.com/templates/
  #  design:
  #    card:
        # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #     css_style: ""
---
