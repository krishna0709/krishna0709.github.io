---
layout: archive
title: "Education"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

&nbsp;


* Ph.D in Electrical Engineering (Concentration: Computer Engineering), The University of Texas at San Antonio, May 2022 (expected)
* M.S. in Electrical Engineering (Concentration: Computer Engineering), The University of Texas at San Antonio, December 2021 
* B.Sc. in Electronics and Communication Engineering, Khulna University of Engineering and Technology, September 2014
            


&nbsp;

Research Experience
======
<ins>**Graduate Research Assistant**</ins>

**Employer:** IoT Security Lab, The University of Texas at San Antonio\
**Supervisor:** Dr. Guenevere (Qian) Chen, Assistant Professor, Electrical and Computer Engineering

Cyber Physical System 
* Conducted driving tests in simulation-based Testbed using OpenDS for 50 college-age drivers (IRB approved) under 20 driving tasks and 12 cyber-attack scenarios.
* Collected physical and behavioral data of the vehicle (e.g., position, steering angle, reaction time etc.).
* Proposed Cyber, Physical and Human factor-based framework, ExHPD for driving behavior modeling to detect vehicle cyber-attack using Random Forest and LSTM Autoencoder model.


Enterprise Network                 
* Developed testbed of bare-metal servers for host log (benign/malware) data collection with FOG-project, WLS, Windows ETW and ELK stack.  
* Collected audit and application log (Windows/Linux) dataset under benign scenario for 90-days and 35-users (IRB approved) in a large enterprise network in collaboration with Sandia National Lab (SNL).
* Collected malware dataset in controlled environment (Cuckoo sandbox) for more than 150 malware samples (e.g., Adware, Ransomware, Backdoor/Trojan etc.).
* Indexed collected data (2TB) in Elastic server using Logstash, analyzed and visualized using Kibana for preprocessing (anonymization for privacy) in Python.
* Designed and implemented DeepRan an attention-based bi-LSTM and CRF model for ransomware early detection and classification with more than 98% accuracy.
* Proposed LogGNN a Graph Neural Network (GNN) based graph embedding algorithm for representation learning of heterogeneous Provenance graph constructed from host log and behavioral data. 
* Developed Cyber-Psychology (Delay Discounting, Risk-Taking) mapping framework for early detection of Insider Threat. 
* Currently working on GNN-LSTM based unsupervised malware detection model using provenance graph constructed from collected malware logs for threat hunting in enterprise network.

<ins>**Graduate Research Assistant**</ins> 

**Employer:** The University of Texas at San Antonio, United States                                                           
* Designed differential privacy mechanism for publishing optimized building energy consumption data.
* Analyzed k-anonymity, Local differential privacy (LDP), Exponential and Laplace mechanism for differential privacy mechanism and.
* Analyzed differential privacy mechanisms for social graphs using Facebook data from SNAP 

&nbsp;

<ins>**Undergraduate Research**</ins>

**Employer:** Khulna University of Engineering and Technology
* Studied and surveyed ultrasound imaging systems in biomedical imaging
* Developed ultrasound strain imaging system using dynamic programming and information theory for
	nonlinear ultrasound RF data and published two conference papers

&nbsp;

Skills and Expertise
======
* **AI Algorithms:** ML (SVM, LR, RF), DL (CNN, LSTM, GNN, Autoencoder, GAN), NLP, Transformer
* **Programming Languages:** Python, C, C++, MATLAB, CUDA
* **Software & Tools:** ELK stack (Elasticsearch, Logstash, Kibana), WLS, WireShark, TensorFlow, PyTorch, Keras, Weka
* **Web & Cloud:** Google Colaboratory, Azure Notebooks, IBM Watson Studio
* **Platforms:** Windows, Linux/Unix, MacOS

&nbsp;

Projects Accomplished
======
<ins>**Graduate Projects**</ins>

**Institution:** The University of Texas at San Antonio 
* **Driver Behavior Analysis Model:** Developed driver behavior modeling tool using deep learning autoencoder
models with real life driving and driver behavioral data.
* **Smart and Secured Parking System:** Developed RF based smart parking system with light weight MQTT
protocol and performed security vulnerability analysis with Wireshark in IoT Security course.
* **TRN for Video Summarizing:** Implemented multiscale temporal relational reasoning network (TRN) for
video event detection and summarizing in Deep Learning course.
* **Cache Performance Simulator in Python:** Designed Cache Performance Simulator in Advanced Computer
Architecture course in python
* **Cloud Solution for Medical Emergency:** Proposed and implemented a cloud solution for handling medical
emergency visits in rural areas through android application. Implemented collective communication system in
cloud using OpenStack and interfaced with android application in Cloud Computing course.

&nbsp;

<ins>**Undergraduate Projects**</ins>

**Institution:** Khulna University of Engineering and Technology 
* Designed and implemented land rover robot controlled by mobile commands using DTMF
* Designed and implemented a microcontroller-based PC remote controller system with RC5 protocol
* Designed and implemented Line follower robot with mash solving ability
* Developed FPGA based 64-bit magnitude comparator with BIST facility

&nbsp;

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
&nbsp;

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

