---
title: Image Classifier Neural Network
subtitle: Written in Python
date: '2019-02-26'
thumb_image: /images/AI_Pets.jpg
thumb_image_alt: A table tennis racket on a pink background
image_alt: A table tennis racket on a pink background
seo:
  title: Project Title 4
  description: This is the project 4 description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 4
      keyName: property
    - name: 'og:description'
      value: This is the project 4 description
      keyName: property
    - name: 'og:image'
      value: images/4.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 4
    - name: 'twitter:description'
      value: This is the project 4 description
    - name: 'twitter:image'
      value: images/4.jpg
      relativeUrl: true
layout: project
---
Designed and implemented a Convolutional Neural Network to identify and classify 60000 32x32 images.

**Dataset:** [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)

Below is an image demonstrating the 10 different classes that the network was able to identify:

![](/images/CIFAR.JPG)

We achieved accuracy scores of 91% for the training data and an 80% overall testing accuracy.

After creating an accurate model, we then implemented an interactive app that allowed users to classify their own images.

Below is a screenshot of the network correctly classifying my team member's dog:

![](/images/AI_Dog-67270b0f.PNG)
