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
* B.Sc. in Electronics and Communication Engineering, Khulna University of Engineering and Technology, 2014
* Ph.D in Computer Engineering, The University of Texas at San Antonio, 2022 (expected)

Research Experience
======
**Graduate Research Assistant**\

**Employer:** IoT Security Lab, The University of Texas at San Antonio\
**Supervisor:** Dr. Guenevere (Qian) Chen, Assistant Professor, Electrical and Computer Engineering\

* Researched on host behavior-based intrusion detection systems
* Designed and developed deep learning experiments for ransomware detection and classification
* Collected windows audit and application logs under normal scenario for 90 days for host behavior modeling
* Collected host logging data from 35 computers running Microsoft Windows 10 OS using Windows Logging
	Service (WLS)
* Collected attack dataset in controlled environment FOG server and Cuckoo sandbox for 100 malwares
* Indexed collected data in Elasticsearch server using Logstash and performed statistical analysis for
	preprocessing and visualized using Kibana
* Published a journal on attention based BiLSTM and Conditional Random Field (CRF) deep learning models
	for ransomware detection and classification in Springer Nature
* Currently working on LogGNN: a graph neural network-based log provenance analysis for threat hunting


**Undergraduate Research**\

**Employer:** Khulna University of Engineering and Technology\

* Studied and surveyed ultrasound imaging systems in biomedical imaging
* Developed ultrasound strain imaging system using dynamic programming and information theory for
	nonlinear ultrasound RF data and published two conference papers
  
Skills
======
* Programming Languages: Python, C, C++, CUDA
* Search & Analytics Tools: ELK stack (Elasticsearch, Logstash, Kibana)
* Application Software & Packages: MATLAB, TensorFlow, PyTorch, Wireshark, WLS,
* Language: English (Fluent), Bangla (Native Speaker)

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
