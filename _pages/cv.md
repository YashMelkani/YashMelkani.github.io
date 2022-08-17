---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Engineering Physics, University of California, Berkeley, 2024 (in progress)
* Westview High School, 2020

Work experience
======
* Software Developer (Summer 2021 - Present)
  * Supervisor: 
  * Development of automated analysis software for Drosophila (in vivo model) cardiac physiological
assays via machine learning. Focus on developing deep learning models capable of identifying
drosophila heart walls in high-speed cardiac videos on a frame-by-frame basis. Wrote code to
extract relevant parameters (Heart Period, Systolic and Diastolic Intervals) from these model
predictions. Reviewed literature on deep learning techniques for biomedical segmentation tasks
(done to identify candidate model architectures). Implemented and tested a variety of UNet based
neural networks, manipulated dataset to increase size and variation, modified different elements of
the training cycle (loss function, 2d vs 3d data, number of channels per image). The goal of this
project is to replace the previous method of analyzing drosophila hearts which involved highly
mindful human involvement and thus was slow and prone to human biases. The software we
created provides quicker analysis of the data, greater immunity to human bias, and more
representative statistics of the heart being analyzed. Done in collaboration with another
undergraduate student at the University of Alabama, Birmingham.

* Intern, Center for Astrophysics and Space Sciences at UCSD (Summer 2017 – Fall 2020)
  * Supervisor Dr. Brian Keating
  * Created software to simulate astrophotometry data of stellar objects. In particular, once a set of
parameters was given, data regarding a star’s magnitude could be simulated as it moved
throughout the sky. In theory, this allows one to collect magnitude data of a star without having to
plan for extraneous variables such as weather conditions, location, faulty equipment, etc. It also is
much quicker, simulating 8hrs of data in seconds. The software was written using python. All
relevant astrophysics was self-taught. As part of this project, I calculated the optical depth of
Earth’s atmosphere from collected data to be 0.12. The accepted range is between 0.1 and 0.15.
This project was done independently (Summer 2017).
  * Constructed a circular polarimeter with 3D printed parts and developed software for automating
the use of the polarimeter. The software was created in Python and Arduino. I was heavily
involved in troubleshooting mechanical, electrical, and software components of the device. The
project was done in collaboration with another high school intern (Summer 2018, 2019).
  
Skills
======
* Familiar with Jupyter Notebook, Eclipse, IntelliJ
* Knowledge of Java, Python, MATLAB, Arduino
* Image processing with OpenCV library
* Machine Learning with Numpy, Scipy, TensorFlow, and PyTorch
* Worked with CVAT for annotating data for machine learning applications
* Experience developing and implementing machine learning models in Python
* Familiar with implementing auto-encoders, variational auto-encoders, convolution-based models, UNet
variants (DenseNet, AttUNet), GANS, dimensionality reduction techniques (UMAP, t-SNE, PCA)
* Experience working on supercomputers, and multi-gpu processing
* Proficient with Arduino breadboarding and programming. Experience with soldering
* Competent with Microsoft Applications and Google Drive Suite
* Experience using programs such as Python and MATLAB to create basic physics and astronomy-related
simulations.


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
