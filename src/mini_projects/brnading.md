---
layout: layouts/mini_projects/branding.njk
tags: mini_project
related:
  - Brand Identity
  - UI Design
cover: ./src/img/awry_cover.png
title: >
  awry.design
subtitle: Designing brand identities for tech startups
date: 2014-01-01
product: >
  awry.design
result_title: Impact
result_content: 5x revenue growth with SDK X
summary_title1: Aim
summary1: Reduce Integration Cycle time and improve user onboarding experience

summary_title2: My Role
summary2: Product Concept, UX Research, Prototyping, High-fidelity mocks & UI Development

summary_title3: Timeline
summary3: 2022

link1: awry.design on Behance
link1_url: https://www.behance.net/awrydesign

context: Helping tech startups boost with a unique brand identity

section1_title: Defining Problems
section1_subtitle: Frustrating Onboarding Experience & Manual team workflow
section1_img: ./src/img/sdkx/cover.png

section2_title: >
  #1 Long onboarding process
section2_content: An integration cycle would start with the Sales team pitching it to the publishers, once a publisher is willing to integrate the SDK in their Android app, the design team would come up with suggestions for the ad placements and mocks, post that once everyone gets on the same page, the developer would go through the Docs on the website for the instructions to integrate using Android Studio.
section2_img: ./src/img/problem.png

section3_title: >
  #2 Ad Unit dimension inconsistency
section3_content: In the SDK 8 integration cycle, the designers from GreedyGame would design mocks in Photoshop which displayed ads over the screenshots to depict how the ad designs will look like when integrated. Once the app publisher approved the placements, they would need to create ad units on the panel with an input box requesting dimensions. They did not understand what the actual values represented and how does it affect the actual ad size on Android phones.
section3_img: ./src/img/adunit_inconsistency.png

section4_title: >
  #3 Inefficient test ad functionality
section4_content: Once a developer integrated the SDK, it was a tedious task to get the sample test ads, to verify the implementation. The developers took about an hour on average to set up test ads on multiple devices. They had to verify the ad implementations such as refresh time, and loading time, debug the issues and check for design alignment. The process is different from Google's AdMob SDK and since a lot of developers were coming from those lines, this method seemed a little unusual and added to the bad user experience.
section4_img: ./src/img/challenge_testad.png

section5_title: >
  #4 Manual JSON templates for native ads
section5_content: For each native ad space and each app a publisher integrated GreedyGame SDK in, graphic designers at GreedyGame had to design a JSON template for the specific Ad Size, incorporating assets that matched the app's UI. This required a lot of man-hours and monotonous activities that could be automated.
section5_img: ./src/img/challenge_testad.png

section6_title: Designing solutions
section6_subtitle: Dynamic responsive Ad templates & User-centric Dashboard
section6_img: ./src/img/design_process.png
section6_content: Designed in XD and Built-in Android Studio

section7_title: Personas & User Flow
section7_content: To start, I created a provisional persona of a potential developer and a publisher based off the dataset of 100s of past clients that have integrated GreedyGame's SDK into their apps. They are either developers or publishers; this persona was created with assumptions and not fully research-based but it was something that I came back to throughout my project to guide my design decisions and priorities.
section7_img: ./src/img/design_process.png
section7_content2: I also created a user flow to show the flow for a publisher who wants to integrate SDK in his app. The highlighted areas represent the first 3 pain points that I will tackle in my design solutions.
section7_img2: ./src/img/design_process.png
section8_pretitle: The Solutions
section8_title: >
  #1 In-built responsive native templates in SDK
section8_content: There are a multiple ways in which a View can be defined in Android. I have designed a decision tree which selects an appropriate ad design XML on the basis of the height and width of the ad space. The size of the text, icon, button; the location of various elements are chosen automatically. This enables the developer to visualise a Test Ad as soon as it is implemented and the size and placement can be changed accordingly in no time. This saves a lot of time in the integration process.
section8_img: ./src/img/userflow.png

section9_title: >
  #2 Ad Unit types and consistent dimensions
section9_content: Publishers can now choose among the common ad unit types that they are familiar too, the width and height of which is a part of the Ad Unit description, that can be referred while implementing the Ad Unit in Android. I conducted Design sessions where the different dimensions that the Android developers are familiar with were explained to the employees at GreedyGame to bring everyone to the same page.
section10_title: >
  #3 Test Ads in-built in the SDK
section10_content: We have devised an easier way for developers to get test ads. By default, any debug build that is created from Android Studio will get sample test ads. If for some reason you want to see the test ads on a release build, you can enable the enableDebug(true) method in the AppConfig Builder as a part of the SDK initialization.
section11_title: Results
section11_subtitle: 10x integrations per week & seamless onboarding
section11_content: I interviewed around 10 Android app developers with each session lasting for about 2 hours where we asked them to do the complete integration process, where I observed them throughout the process. Users were able to understand most of the things by themselves, but I had to assist them at some points through the documentation.

section12_title: User Analytics and Recordings
section12_content: I interviewed around 10 Android app developers with each session lasting for about 2 hours where we asked them to do the complete integration process, and I observed them throughout the process. Users were able to understand most of the things by themselves, but I had to assist them at some points through the documentation.

section13_title: Integration Cycle Timeline
section13_content: We had set up Hotjar on the SDK X Console to analyze the user behaviors and understand the discoverability. Analyzing over 1800 recordings in the first month, we found that the users were able to navigate and perform the tasks on the dashboard faster as compared to the previous dashboard. A few users were unable to understand the procedure after adding the ad units as they were not used to AdMob terminologies. However, the initial target audience for SDK X were users aquatinted with AdMob hence this issue can be considered insignificant.
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
