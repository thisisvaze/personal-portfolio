---
layout: layouts/works/work_things.njk
tags: post
related:
  - Unity
  - Interaction Design
  - Mixed Reality
  - Machine Learning
cover: ./src/img/things_cover.png
subtitle: M. Des. Thesis @ OCAD University
title: >
  Contextual learning with Mixed Reality
date: 2014-01-01
summary_title1: MR Headset support
summary1: Meta Quest & Hololens 2
result_title: M.Des. Thesis (In Progress)
result_content: Supervised by Dr. Alexis Morris, Dr. Ian Clarke
summary_title2: Tools
summary2: Unity, OpenXR, MRTK, Socket.io, PyTorch
summary_title3: Timeline
summary3: 2022 - Present
# link1: Thesis (Work in Progress)
# link1_url: ocadu.ca

context: For my Master's thesis, I'm building a platform to support curiosity with Mixed Reality. Learners would be able to learn math concepts such as the volume of a cylinder when looking at a cup to biology concepts on how plant cells look like when near a plant.
section1_title:
section1_subtitle: How can Mixed Reality support curiosity?
section1_img: ./src/img/sdkx/cover.png
section2_content: In this project, we are working on a mixed reality system to support educational content. I present an approach to map multiple context sources from the real world for multi-modal learning with the learning agents using APIs (deep learning models) to support curiosity and improve knowledge recall among learners. The prototypes allow users to learn languages, science, history, general knowledge and mathematics concepts through the objects around them and the environment.
section2_img: ./src/img/things_overview.png
section3_title: Prototype 1
section3_subtitle: AR language learning
section3_subtitle2: The Motivation
section3_subtitle2_content: How can we learn languages in context?
section3_content: Since I arrived in Canada in 2021, I had been trying to learn French through different techniques. After a bit of research, I learned that immersion can significantly accelerate the learning process and I was motivated to build an app for smartglasses that could make learning languages fun and highly efficient for me and all the other language learners.
section4_title: User Personas
section4_content: With an inspiration to make language learning fun and efficient for certain concepts I started researching user personas for language learners. I wanted to target language learners who had started learning recently; beginners since the advanced concepts needed a deeper understanding of different languages for me and learn instructional design for teaching languages. Advanced learners can be a target for future work and further iterations of this concept.
section4_img: ./src/img/persona_things.png
section4a_title: Storyboarding
section4a_content: I worked on several sketches to visualize use cases and understand interactions that could help smart glasses users learn vocabulary or grammar.
section4a_img: ./src/img/things_indoor_storyboard.png
section4_img_caption: Sketches to visualize indoor use cases
section4a_img2: ./src/img/things_storyboard.png
section4_img2_caption: Sketches to visualize outdoor use cases
section5_title: Hi-fi mockups & Development
section5_content: The app features real-time intelligence to help you learn languages in an immersive context. When users wearing smart glasses look at any object around them, they see what’s that object called in the target language on the HUD(heads-up display) screen. It supports about 100 languages and allows the users can switch between languages by tapping on the capacitive touch panel on the glasses. The smart glasses display the translation of the object’s name and speak out the pronunciation as well.
section5_img: ./src/img/things_hifi.png
section5_img_caption: Hi fidelity mockups for language learning with Hololens 2
section5_img2: ./src/img/things_lang.png
section5_img2_caption: Android Prototype on Vuzix Blade smart glasses
section5_img3: ./src/img/things_how.png
section5_img3_caption: Underlying Technical Process
section6_title: Prototype 2
section6_subtitle: Curiosity visualization agent
section6_subtitle2: The Motivation
section6_subtitle2_content: How can MR help learners visualize things?
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
section8_content: The demo is built on Microsoft Hololens 2, with real-time object detection from the sketch using a custom-trained model. The model is trained on the Google Quickdraw dataset and works with around 350 common objects (chairs, cars, apples, etc.). The 3D models are fetched from the SketchFab API. This allows for real-time searching for models such as an “apple”, filtering and finding a suitable model that is supported by Hololens 2, downloading it, and then rendering it in front of the user. The user can then use their hands to interact with these objects to either scale, rotate or move them in the space.

section8a_title: System Architecture
section8a_img: ./src/img/viz_arch.png
section8a_content: There are majorly four technical parts to this prototype, first, getting the paper crop from the camera stream, then, detecting the user-drawn object on the paper, using SketchFab to display the model, and finally adding the hand interaction abilities (rotate, scale and move) for the 3D model.

section9_title: Plan for Winter 2023
section9_img: ./src/img/final_grid_things.png
section9_content: I'm building a platform to support a variety of lessons where educators can add learning content such as Math lessons for the Surface area and volume, Biology lessons for plant cells, History lessons to learn about inventions etc. This creation tool will allow educators to create MR lessons easily from the web.
---
