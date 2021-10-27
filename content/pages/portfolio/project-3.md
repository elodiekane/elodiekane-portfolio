---
title: Robot Homing & Tracking Simulation
subtitle: 'Written in Java, using Webots - 3D robotics simulation software'
date: '2019-04-08'
thumb_image: /images/weBots2.JPG
thumb_image_alt: A yellow retro telephone on a yellow background
image_alt: A yellow retro telephone on a yellow background
seo:
  title: Robot Homing & Tracking Simulation
  description: This is the project 3 description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 3
      keyName: property
    - name: 'og:description'
      value: This is the project 3 description
      keyName: property
    - name: 'og:image'
      value: images/3.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 3
    - name: 'twitter:description'
      value: This is the project 3 description
    - name: 'twitter:image'
      value: images/3.jpg
      relativeUrl: true
layout: project
---
Created a simulation where a Roomba-like robot identifies its environment through the use of cameras, proximity sensors, and accelerometers.

The image below shows the robot in its environment, and the top left square shows the robot's camera view when attempting to identify the red balls.

![](/images/weBots-0c989424.JPG)

Once a red ball is identified, the robot navigates its environment with left and right motors to push the balls off the edge of the map.
