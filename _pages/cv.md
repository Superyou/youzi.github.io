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
* B.S. in Microelectronic Science and Engineering, Tsinghua University, 2017
* M.S. in Computer Science, University of Southern California, 2020
* Ph.D in Electrical and Computer Engineering, University of Southern California, 2023 (expected)


Research Experience
=====
* The Reversible Coherence Protocol
  * Advisor: Prof. Xuehai Qian, University of Southern California
  * Analyzed resent defense strategy like InvisiSpec and CleanupSpec
  * Designed a buffer-based Undo approach to mitigate the transient speculation flaw.
  * Extended the current memory coherence protocol to support the merging and purging requests in our design.

* GPU Power Virus Project
  * Advisor: Prof. Xuehai Qian, University of Southern California
  * Used genetic algorithm to automatically generate extremely high power consumption.
  * Modified gpgpusim simulator to trace the access pattern for gpgpu simulations
* Design of a Specialization BNN Accelerator
  * Advisor: Prof. Shouyi Yin, Institute of Microelectronics
  * Designed an architecture which can efficiently execute the binarized neural computation.
  * Investigated its application in different neural networks to accelerate computation.
* Vehicular behavior algorithm analysis 
  * Advisor: Prof. Shouyi Yin, Institute of Microelectronics
  * Used deep learning algorithms to analyze human behavior while driving a vehicle.
  * Used the deep learning platform “tensorflow” to solve traditional problems, e.g. MNIST classification.
  * Investigated the mechanism behind deep learning algorithms.
* Pilot Assignment Algorithms for Wireless Networks 
  * Advisor: Prof. Wei Feng, Tsinghua University
  * Investigated pilot assignment algorithms to achieve better performance in cellular MIMO systems.
  * Performed simulation in cellular Gaussian networks to verify the theoretical results. 


Internship Experience
======
* Summer 2016: Research Intern
  * Cornell University
  * Topic: Implementation of BNN on different platforms
  * Supervisor: Zhiru Zhang
* Summer 2022: Research Intern
  * Alibaba Group U.S.
  * Topic: Control Flow Integrity for RISCV ISA
  * Supervisor: Lide Duan 

  

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
