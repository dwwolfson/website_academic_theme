---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Improving the accessibility and transferability of machine learning algorithms
  for identification of animals in camera trap images: MLWIC2'
subtitle: ''
summary: ''
authors:
- Michael A. Tabak
- Mohammad S. Norouzzadeh
- David W. Wolfson
- Erica J. Newton
- Raoul K. Boughton
- Jacob S. Ivan
- Eric A. Odell
- Eric S. Newkirk
- Reesa Y. Conrey
- Jennifer Stenglein
- Fabiola Iannarilli
- John Erb
- Ryan K. Brook
- Amy J. Davis
- Jesse Lewis
- Daniel P. Walsh
- James C. Beasley
- Kurt C. VerCauteren
- Jeff Clune
- Ryan S. Miller
tags:
- '"computer vision"'
- '"deep convolutional neural networks"'
- '"image classification"'
- '"machine learning"'
- '"motion-activated camera"'
- '"R package"'
- '"remote sensing"'
- '"species identification"'
categories: []
date: -01-01
lastmod: 2020-09-21T13:05:35-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-21T18:05:33.951869Z'
publication_types:
- 2
abstract: 'Motion-activated wildlife cameras (or “camera traps”) are frequently used
  to remotely and noninvasively observe animals. The vast number of images collected
  from camera trap projects has prompted some biologists to employ machine learning
  algorithms to automatically recognize species in these images, or at least filter-out
  images that do not contain animals. These approaches are often limited by model
  transferability, as a model trained to recognize species from one location might
  not work as well for the same species in different locations. Furthermore, these
  methods often require advanced computational skills, making them inaccessible to
  many biologists. We used 3 million camera trap images from 18 studies in 10 states
  across the United States of America to train two deep neural networks, one that
  recognizes 58 species, the “species model,” and one that determines if an image
  is empty or if it contains an animal, the “empty-animal model.” Our species model
  and empty-animal model had accuracies of 96.8% and 97.3%, respectively. Furthermore,
  the models performed well on some out-of-sample datasets, as the species model had
  91% accuracy on species from Canada (accuracy range 36%–91% across all out-of-sample
  datasets) and the empty-animal model achieved an accuracy of 91%–94% on out-of-sample
  datasets from different continents. Our software addresses some of the limitations
  of using machine learning to classify images from camera traps. By including many
  species from several locations, our species model is potentially applicable to many
  camera trap studies in North America. We also found that our empty-animal model
  can facilitate removal of images without animals globally. We provide the trained
  models in an R package (MLWIC2: Machine Learning for Wildlife Image Classification
  in R), which contains Shiny Applications that allow scientists with minimal programming
  experience to use trained models and train new models in six neural network architectures
  with varying depths.'
publication: '*Ecology and Evolution*'
url_pdf: https://onlinelibrary.wiley.com/doi/abs/10.1002/ece3.6692
doi: 10.1002/ece3.6692
---
