---
layout: splash
read_time: false
comments: true
share: true
author_profile: true
title: <br /> <br /> <br /> Projects
permalink: /projects/
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: https://images.unsplash.com/photo-1518314916381-77a37c2a49ae?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1351&q=80

uizard_lofi_conversion:
  - image_path: assets/images/projects/uizard_lofi_conversion.gif
    alt: "Uizard, sketch to design conversion"
    title: 'Transforming sketches into a UI design prototype'
    excerpt: "Worked on a machine learning pipeline that transforms a picture of a rough sketch into a high fidelity design.
    <br /> <br />
    [Watch video](https://www.youtube.com/watch?v=6PVgUBMBpsw){: .btn .btn--inverse .btn--large} &emsp; [Try it](https://app.uizard.io/auth/sign-up){: .btn .btn--primary .btn--large}"

uizard_theme_extraction:
  - image_path: assets/images/projects/uizard_theme_extraction.png
    alt: "Uizard, generate "
    title: 'Generating design systems from an image'
    excerpt: "We built a machine learning pipeline that generates a design system (with styles for buttons, text and other components) from an image, webpage or Sketch file. 
    <br /> <br />
    [Read blog post](https://tbeltramelli.medium.com/generating-design-systems-using-deep-learning-abe8d1195960){: .btn .btn--inverse .btn--large} &emsp; [Try it](https://app.uizard.io/auth/sign-up){: .btn .btn--primary .btn--large}"

uizard_semi_supervised:
  - image_path: assets/images/projects/realmix.png
    alt: "Uizard, realmix "
    title: 'Bringing semi-supervised learning to the real world'
    excerpt: "Current semi-supervised techniques work well on clean academic datasets. What does it take to make them work while building a product? At Uizard we have done a bunch of research to answer this question. 
    <br /> <br />
    [Read blog post](https://towardsdatascience.com/from-research-to-production-with-deep-semi-supervised-learning-7caaedc39093){: .btn .btn--inverse .btn--large} &emsp;
    [Read paper](https://arxiv.org/abs/1912.08766){: .btn .btn--inverse .btn--large} &emsp;
    [Watch talk](https://youtu.be/1j8NVHo5vUg){: .btn .btn--primary .btn--large}"

side_clip_playground:
  - image_path: assets/images/projects/side_clip_playground.gif
    alt: "CLip playground"
    title: 'CLIP Playground: A user interface around OpenAIs CLIP model'
    excerpt: "A Streamlit powered interface around [CLIP](https://openai.com/blog/clip/). 
    <br /> <br />
    [Read thread](https://twitter.com/JavierFnts/status/1363522529072214019?s=20){: .btn .btn--inverse .btn--large} &emsp;
    [Try it](https://clipplayground.co){: .btn .btn--primary .btn--large}"

robotics_thesis:
  - image_path: assets/images/projects/robotics_thesis.png
    alt: "Slide thesis"
    title: 'Instance segmentation using sequences'
    excerpt: "During my master thesis at ETH I wrote about how to improve instance segmentation models (like Mask R-CNN) with a sequence of images. 
    <br /> <br />
    [Slides](https://drive.google.com/file/d/0B8E2dzNzwAG0bGRzR3IwRHdyd196ZVRkZjJnXzBhVnhLbzVV/view?usp=sharing){: .btn .btn--primary .btn--large}"

robotics_tools:
  - image_path: assets/images/projects/robotics_tools.gif
    alt: "Tools"
    title: 'Tool recognition for robotic manipulation pipeline'
    excerpt: "I built the tool detection and recognition pipeline as part of a robotics challenge.  
    <br /> <br />"

robotics_lidar:
  - image_path: assets/images/projects/robotics_lidar.gif
    alt: "Lidar"
    title: 'A cheap (and really slow) 3D lidar'
    excerpt: "We built a really basic 3D lidar using a couple of motors, a sensor and some electronics. The Lidar will then send the measurements to a computer for visualization.  
    <br /> <br />
    [Code](https://github.com/JaviFuentes94/DTULidar){: .btn .btn--primary .btn--large}"

 
---
Some of the cool projects I have been working in the past few years
## Uizard
{% include feature_row id="uizard_lofi_conversion" type="left" %}
{% include feature_row id="uizard_theme_extraction" type="left" %}
{% include feature_row id="uizard_semi_supervised" type="left" %}

## Side projects
{% include feature_row id="side_clip_playground" type="left" %}
## Robotics
{% include feature_row id="robotics_thesis" type="left" %}
{% include feature_row id="robotics_tools" type="left" %}
{% include feature_row id="robotics_lidar" type="left" %}
