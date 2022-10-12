---
layout: layouts/works/work_things.njk
tags: post
related:
  - Unity
  - Hololens 2
  - Oculus Quest
cover: ./src/img/things_cover.png
title: >
  Contextual learning with Mixed Reality
date: Created
product: >
  Thesis (Work in Progress)
subtitle: M.Des. Thesis @ OCAD University
summary_title1: Aim
summary1: Reduce Integration Cycle time and improve user onboarding experience

summary_title2: Tools
summary2: Unity, Hololens MRTK3, Node, PyTorch
summary_title3: Timeline
summary3: 2022 - Present

link1: Thesis (Work in Progress)
link1_url: ocadu.ca

context: >
  Since I arrived in Canada about 6 months ago, I’ve been trying to learn French through different techniques. I’ve tried some of the most popular apps such as Duolingo, completed certain French grammar exercises, and watched a bunch of French movies as well. Although I’ve caught some bits of grammar and vocabulary along the way, I feel that these techniques are not efficient. After a bit of research, I realized that conventional technological tools to learn languages are inefficient as they lack a real context. Immersion can significantly accelerate the learning process and I was curious to build an app that could make learning languages fun and highly efficient for me and all the other language learners.

section1_title: Reimagining the way we learn
section1_subtitle: Can we bring learning to life?
section1_content: Context + Mixed Reality = Magic
section1_img: ./src/img/sdkx/cover.png

section2_title: Research Question
section2_content: How can adaptive context-aware systems support interactive mixed reality learning experiences?
section2_img: ./src/img/things_overview.png
section2_img_credits: How Augmented Reality Will Change Education Completely | Florian Radke | TEDxGateway
section3_title: >
  # Prototype 1: Language Learning
section3_content: Things is an app built for Android smart glasses with a camera and a microphone. The app features real-time intelligence to help you learn languages in an immersive context. When users wearing smart glasses look at any object around them, they see what’s that object called in the target language on the HUD(heads up display) screen. It currently supports 3 languages (French, Italian, and Japanese) and allows the users can switch between languages by tapping on the capacitive touch panel on the glasses. The smart glasses display the translation of the object’s name and speak out the pronunciation as well.
section3_img: ./src/img/things_lang.png

section4_title: >
  # Prototype 2: Surface area and Volumes
section4_content: Once a developer integrated the SDK, it was a tedious task to get the sample test ads, to verify the implementation. The developers took about an hour in average to setup test ads in multiple devices. They had to verify the ad implementations such as refresh time, loading time, debugging the issues, and checking for design alignment. The process is different from Google's AdMob SDK and since a lot of developers were coming from those lines, this method seemed a little unusual and added to bad user experience.
section4_img: ./src/img/sample_ads.png

section5_title: Designing Native Ad Templates
section5_content: For each native ad space and each app a publisher integrated GreedyGame SDK in, graphic designers at GreedyGame had to design JSON template for the specific Ad Size, incorporating assets that matched the app's UI. This required a lot of man hours and monotonous activities that could be automated.
section5_img: ./src/img/sample_ads.png

section6_title: Designing solutions
section6_subtitle: Dynamic responsive Ad templates & User-centered Dashboard
section6_img:
section6_content: Designed in XD and Built in Android Studio

section7_title: Personas and User Flow
section7_content: To start off, I created a provisional persona of a potential developer and a publisher based off the dataset of 100s of past clients that have integrated GreedyGame's SDK into their apps. They are either developers or publishers; this persona was created with assumptions and not fully research-based but it was something that I came back to throughout my project to guide my design decisions and priorities. I also created a user flow to show the flow for a publisher who wants to integrate SDK in his app. The highlighted areas represent the first 3 pain points which I will tacle in my design solutions.
section7_img: ./src/img/design_process.png
section7_img2: ./src/img/design_process.png

section8_title: In-built responsive native templates in SDK
section8_content: There are a multiple ways in which a View can be defined in Android. I have designed a decision tree which selects an appropriate ad design XML on the basis of the height and width of the ad space. The size of the text, icon, button; the location of various elements are chosen automatically. This enables the developer to visualise a Test Ad as soon as it is implemented and the size and placement can be changed accordingly in no time. This saves a lot of time in the integration process.
section8_img: ./src/img/userflow.png

section9_title: Ad Unit types and consistent dimensions
section9_content: Publishers can now choose among the common ad unit types that they are familiar too, the width and height of which is a part of the Ad Unit description, that can be referred while implementing the Ad Unit in Android. I had conducted Design sessions where the different dimensions that the Android developers are familiar with were explained to the employees at GreedyGame to bring everyone to the same page.

section10_title: Test Ads in-built in the SDK
section10_content: We have devised an easier way for developers to get test ads. By default, any debug build that is created from Android Studio will get sample test ads. If for some reason you want to see the test ads on a release build, you can enable the enableDebug(true) method in the AppConfig Builder as a part of the SDK initialization.

section11_title: Results
section11_content: I interviewed around 10 Android app developers with each session lasting for about 2 hourse where we asked them to do the complete integration process, where I observed them throughout the process. Users were able to understand most of the things by themselves, but I had to assist them at some points through the documentation.

section12_title: User Analytics and Recordings
section12_content: I interviewed around 10 Android app developers with each session lasting for about 2 hourse where we asked them to do the complete integration process, where I observed them throughout the process. Users were able to understand most of the things by themselves, but I had to assist them at some points through the documentation.

section13_title: Integration Cycle Timeline
section13_content: We had setup Hotjar on the SDK X Console to analyze the user behaviours and understand the discoverability. Analysing over 1800 recordings in the first month, we found that the users were able to navigate and perform the tasks on the dashboard quicker as compared to the previous dashboard. Few users were unable to unable to understand the procedure after adding the ad units as they were not used to AdMob terminologies. However, the initial target audience for SDK X were users aquatinted with AdMob hence this issue can be considered insignificant.
# apples:
#   - one
#   - two
# sections:
#   - section1:
#       - title: apple
#       - subtitle: orange
#   - section2:
#       - title: apple2
#       - subtitle: orange2
---
