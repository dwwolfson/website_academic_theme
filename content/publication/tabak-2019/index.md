---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Machine learning to classify animal species in camera trap images: Applications
  in ecology'
subtitle: ''
summary: ''
authors:
- Michael A. Tabak
- Mohammad S. Norouzzadeh
- David W. Wolfson
- Steven J. Sweeney
- Kurt C. Vercauteren
- Nathan P. Snow
- Joseph M. Halseth
- Paul A. Di Salvo
- Jesse S. Lewis
- Michael D. White
- Ben Teton
- James C. Beasley
- Peter E. Schlichting
- Raoul K. Boughton
- Bethany Wight
- Eric S. Newkirk
- Jacob S. Ivan
- Eric A. Odell
- Ryan K. Brook
- Paul M. Lukacs
- Anna K. Moeller
- Elizabeth G. Mandeville
- Jeff Clune
- Ryan S. Miller
tags:
- '"artificial intelligence"'
- '"camera trap"'
- '"convolutional neural network"'
- '"deep neural networks"'
- '"image classification"'
- '"machine learning"'
- '"r package"'
- '"remote sensing"'
categories: []
date: '2019-01-01'
lastmod: 2020-09-06T20:54:50-05:00
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
publishDate: '2020-09-07T01:54:48.913994Z'
publication_types:
- 2
abstract: Motion-activated cameras (“camera traps”) are increasingly used in ecological
  and management studies for remotely observing wildlife and are amongst the most
  powerful tools for wildlife research. However, studies involving camera traps result
  in millions of images that need to be analysed, typically by visually observing
  each image, in order to extract data that can be used in ecological analyses. We
  trained machine learning models using convolutional neural networks with the ResNet-18
  architecture and 3,367,383 images to automatically classify wildlife species from
  camera trap images obtained from five states across the United States. We tested
  our model on an independent subset of images not seen during training from the United
  States and on an out-of-sample (or “out-of-distribution” in the machine learning
  literature) dataset of ungulate images from Canada. We also tested the ability of
  our model to distinguish empty images from those with animals in another out-of-sample
  dataset from Tanzania, containing a faunal community that was novel to the model.
  The trained model classified approximately 2,000 images per minute on a laptop computer
  with 16 gigabytes of RAM. The trained model achieved 98% accuracy at identifying
  species in the United States, the highest accuracy of such a model to date. Out-of-sample
  validation from Canada achieved 82% accuracy and correctly identified 94% of images
  containing an animal in the dataset from Tanzania. We provide an r package (Machine
  Learning for Wildlife Image Classification) that allows the users to (a) use the
  trained model presented here and (b) train their own model using classified images
  of wildlife from their studies. The use of machine learning to rapidly and accurately
  classify wildlife in camera trap images can facilitate non-invasive sampling designs
  in ecological studies by reducing the burden of manually analysing images. Our r
  package makes these methods accessible to ecologists.
publication: '*Methods in Ecology and Evolution*'
url_pdf: http://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.13120
doi: 10.1111/2041-210X.13120
---
