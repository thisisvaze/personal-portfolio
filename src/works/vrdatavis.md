---
layout: layouts/works/work_vrdatavis.njk
tags: post

cover: ./src/img/vrvis_cover.png

related:
  - WebXR
  - Data Visualization
  - UI/UX

title: VR Ego-centric Data Navigation
subtitle: MITACS Research Project @ University of Toronto
date: 2015-01-01
result_title: Impact
result_content: Average visibility improved upto 97% with our method
link1: Live demo
link1_url: https://egocentricdataviz.surge.sh/
link2: Research Paper
link2_url: https://www.researchgate.net/publication/337223649_Ego-centric_Data_Visualization
link3: GitHub
link3_url: https://github.com/aadityavaze/ego-centric-data-viz

summary_title1: Research Lab
summary1: DGP @ University of Toronto

summary_title2: Supervision
summary2: Dr. Karan Singh

summary_title3: Timeline
summary3: 2018 - 2019

context: This research project was aimed to visualize higher-dimensional data scaled to 3D in VR. We developed an ego-centric data-visualization technique using JS in VR for interaction and navigation across webspaces.

section1_title: Research Focus
section1_subtitle: Build  a tool to view and navigate search results in VR
section1_content:
section1_img: ./src/img/sdkx/cover.png

section2_title: Overview
section2_content: Over the last few decades technology has revolutionized the ability to create, store and retrieve information on a whim. Information visualization, the art of representing data in a way that it is easy to understand and to manipulate, can help us make sense of information and thus make it useful in our lives. Information Visualization tools currently used are restricted to 2D screens, but with the recent developments in AR/VR give us the ability to visualize information and navigate web in the 3D space. In this report, we design and develop new techniques to interact with information in the AR/VR space.
section2_img: ./src/img/vr_data.png

section3_title: 1. Representing data in VR
section3_content: Reducing higher-dimensional data with force-field implementation where force between nodes is scaled to their affinity. Multidimensional scaling is a visual representation of dissimilarities between sets of objects. The dissimilarities are quantitatively represented as distances. “Objects” can be faces, colour, map coordinates, political persuasion, or any kind of real or  conceptual stimuli.
section3_img: ./src/img/vr_rep_data.png

section4_title: 2. Radial replusion force
section4_content: >
  We start with a data set and its corresponding affinity matrix, and assign random initial position of points in 3D around the user and using physics simulation, let the points settle down on a local minima, according to their affinity. With plethora of data points around the user to look at,there are some ways in which this visualization can be improved. First of all, from the user’s viewpoint, when visualizing data points, points that are close by in the line of sight can intersect and result in an occluded vision, to solve this, we introduce new forces in the system, namely radial repulsion forces between the points that are close enough radially. Secondly, we designate points that are of higher importance as landmarks and reduce the opacity of points that are far enough and not landmarks.
section4_content_2: >
  Finally, we verify the visibility of the nodes with full opacity and use parameters such as spring stiffness of radial-repulsion forces and size of the nodes to remove minor occlusions. A new force was introduce to avoid object oclusions in VR. Users should be able to see all the data points clearly in space.
section4_img: ./src/img/vr_repulsion.png
section4_img2: ./src/img/replusion_force.png
section5_title: Implementation
section5_subtitle: d3-force-3d and WebXR
section5_content: We built a tool where data with nodes and affinity could be used to visualize in VR with maximum visibility. As it's built with WebXR, it is browser-based and supports multiple headsets.
section5_img: ./src/img/vr_d3_force_1.png
section5_img2: ./src/img/vr_random_obj.png

# section6_title: Radial repulsion force
# section6_content:
# section6_img: ./src/img/vr_ideal_angle.png

section7_title: Results
section7_img: ./src/img/vr_data.png
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
