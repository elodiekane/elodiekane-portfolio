---
subtitle: Written in a Jupyter Notebook using Google Colab and Tensorflow
date: '2019-05-10'
thumb_image: /images/NN_Headphones.jpg
thumb_image_alt: 'White, black, and red shoe sole'
image_alt: 'White, black, and red shoe sole'
seo:
  title: Project Title 1
  description: This is the project 1 description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 1
      keyName: property
    - name: 'og:description'
      value: This is the project 1 description
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 1
    - name: 'twitter:description'
      value: This is the project 1 description
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: project
title: Sound Classifier Neural Network
---
I worked in a partnered project where we designed and implemented a 5-layer Convolutional Neural Network (CNN) for translating audio data into visual spectrograms.

Being able to identify sounds could be very useful in technology for those that are hearing impaired. This real-world application was a key motivator creating and training a network that could correctly classify a range of urban sound audio clips.

Dataset: [urbansound8k](https://urbansounddataset.weebly.com/urbansound8k.html)

There were 10 classes within this audio dataset. The distribution can be seen below:



![](/images/classesNN.PNG)

We formatted the data by translating the audio waves into spectrograms and then inputting the spectrogram images into the CNN model. Below is an example audio wave of a dog barking, and its accompanying spectrogram:

![](/images/NN_AudioWave-e8c473ed.PNG)![](/images/NN_Spectrogram-922e481c.PNG)

Following this, we then trained and evaluated using 10-fold cross validation, and the best accuracy was saved for any future testing.
