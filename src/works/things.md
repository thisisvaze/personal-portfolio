---
layout: layouts/works/work_things.njk
tags: post
related:
  - Unity
  - Interaction Design
  - Mixed Reality
  - Machine Learning
cover: ./src/img/things_cover.png
subtitle: >
  MDes Thesis @ OCAD University
title: >
  Contextual Learning with Mixed Reality
date: 2013-01-01
summary_title1: MR Headset support
summary1: Meta Quest Pro & Hololens 2
result_title: M.Des. Thesis
result_content: Supervised by Dr. Alexis Morris, Dr. Ian Clarke
summary_title2: Tools
summary2: Unity, OpenXR, Oculus SDK, Socket.io, PyTorch
summary_title3: Timeline
summary3: 2022 - 2023 (Lanuching soon on Meta Store)
link1: CuriosityXR
link1_url: https://www.curiosityxr.com

context: For my Master's thesis, I'm building a platform to support curiosity with XR. Learners would be able to learn math concepts such as the volume of a cylinder when looking at a cup to biology concepts on how plant cells look like when near a plant.
section1_title: >
  How can XR support curiosity?
section1_subtitle: The Problem
section1_img: ./src/img/sdkx/cover.png
section2_content: I am building an app to support XR learning experiences. I present an approach to map real-world context for multi-modal learning using ChatGPT, SketchFab API and other ML agents to support curiosity and improve knowledge recall. The prototypes allow users to learn languages, science, history, general knowledge and mathematics concepts through the objects around them and the environment.
section2_img: ./src/img/things_overview.png
section2_img2: ./src/img/things_overview2.png

section6_subtitle2: >
  "What if I draw an apple, and it's there in front of me?"
section6_subtitle2_content: Help learners visualize things
section6_content: The concept of turning sketches into objects such as a chair, car, etc. is interesting and can be extended to drawing objects which don’t exist like purple apples or magical worlds of mushrooms with abstract gradients as the background. The interaction techniques for this expression in 3D spaces could be through 2D sketches and could provide learners with a natural way to imagine and create 3D spaces/objects. This technique could support curiosity by not limiting the learner’s imagination to the paper.
section7_title: Storyboarding
section7_img: ./src/img/p2_pain_points.png
section7_img_caption: User sketch or speech is used to show 3D models from database
section7_img2: ./src/img/viz_support2.png
section7_img2_caption: User sketch is used to show 3D models rendered real-time
section7_content: This prototype aims to understand the benefits and scope of a Mixed Reality visualization support system. To map out the use case of recognizing user intents such as drawings or speech and augmenting them in the MR space, I drew some use case sketches to visualize this tool.
section8_title: Outcomes
section8_img: ./src/img/p2_visualization.png
section8_img_caption: Saying "Can I see mars?" shows 3D model of mars
section8_gif2: ./src/img/apple_viz.gif
section8_img2_caption: Sketching apple renders 3D model of an apple
section8_content: The demo is built on Microsoft Hololens 2, with real-time object detection from the sketch using a custom-trained model. The model is trained on the Google Quickdraw dataset and works with around 350 common objects (chairs, cars, apples, etc.). This allows for real-time searching for models such as an “apple”, filtering and finding a suitable model that is supported by Hololens 2, downloading it, and then rendering it in front of the user. The user can then use their hands to interact with these objects to either scale, rotate or move them in the space.

section8_subtitle2: >
  "What if I want to know something about an apple?"
section8a_title: Storyboarding
section8_subtitle2_content: Help them learn anything they want to learn
section8a_img: ./src/img/viz_arch.png
section8a_content: After brainstorming and sketching ideas, some of the use case scenarios could be the following. The user could ask questions about the model, parts of a model or one of the many models loaded. I used Wit.ai to recognize user intent and ChatGPT API to support learners with as many questions as they had while exploring these models.

section8b_title: Outcomes
section8b_img: ./src/img/cxr_screenshots.png
section8b_content: >
  The application is being built and tested for the Quest Platform and can bring learning content real-time in the form of text, images, videos, 3D models to provide engaging learning experiences. The application also uses Wit.ai to understand user intent and collect the relevant information required to provide the best learning experience to the user.

section9_title: Work in progress..
section9_subtitle: Building tools to support limitless learning
section9_img: ./src/img/final_grid_things.png
section9_content: This research process and user study is currently in progress and has helped in the development of CuriosityXR, resulting in a system that provides engaging and immersive learning experiences that support learners' curiosity. The application is planned to launch in April 2023 on Quest store, Register for the waitlist on the link below.
---
