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
* BEng. in Electronic and Electrical Engineering, Loughborough University, 2006
* Ph.D in Control Theory, Loughborough University, 2010

Work experience
======
* 2020-present: Associate Professor
  * University of Tokyo, Japan
  * I am working on the development of autonomous satellites with multiple subsystems that collaboratively solve complicated tasks by local sensing, control, and communication  
  * Autonomous system control using reinforcement learning policy search methods
  * Data-driven digital twin for decision making
  * Understand the underlying interplay between the AI hardware and physical world, and the available computation, communication, and control resources
  
* 2016-2018: Research Scientist
  * I worked on developing AI technology in UAVs with a focus on hardware implementation
  * FPGA based inference with streaming data
  * Reservoir computing for sensing applications
  * Development of redundant transistor logic circuits 
  * Implementation of the isolation forest algorithm for online anomaly detection
  
* 2016-2018: JSPS Research Fellowship Award
  * University of Tokyo, Japan
  * I was awarded a Japanese Society for the Promotion of Science (JSPS) Postdoctoral Fellowship for Research. I worked at the Artificial Intelligence group on a project titled: “Real-time implementation of deep learning methods for failure detection”. The main research goal is focused on identifying the impact of ‘hidden’ failures in space applications. This involved the application of novel data-driven algorithms that learn/process system data to make system level decisions on the diagnosis and prognosis of system units. 
  * Application of deep learning for system health management problems
  * Develop techniques to detect early faults and anomaly detection
  * Bayesian methods to represent uncertainty in deep learning approaches 

* 2015-2016: Lecturer in Aerospace
  * Coventry University, UK
  * Application of neural networks to aircraft engine fault prediction 
  * Teaching avionics, control design, Matlab and management modules
  * Supervisor: Professor Hub
  
* 2012-2015: Project Manager/Research Fellow
  * Cranfield University, UK
  * Application of machine learning for off-line fault detection 
  * Validation and verification of algorithms and control features 
  * Implementation of real-time testing of embedded systems  
  * Design and development of an intermittent fault emulator
  * Development of a new research discpline called 'No Fault Found' 

* 2010-2011: Systems Engineer
  * Thales Transportation, UK
  * Asset reliability and fault modelling 

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
  
