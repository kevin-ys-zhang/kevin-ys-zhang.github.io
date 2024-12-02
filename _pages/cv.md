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
* B.S. in Computer Science (Honors), Purdue University, 2025 (expected)
* B.S. in Applied Physics (Honors), Purdue University, 2025 (expected)

<!-- Current Projects
======
* Summer 2024: Foundational LLMs for Decompiled Code
  * Advisor: Professor Lin Tan, PhD students Nan Jiang and Danning Xie
  * Gathering decompiled code data from popular GitHub repositories through Ghidra and IDA
  * Developing methods to build on the generalization capabilities current SoTA in the decompiled code domain, LLM4Decompile
  * Exploring data efficient self-supervised methods for extension of a model trained on Ghidra data to both Ghidra and IDA decompiled code
* Fall 2024:  -->

Research Experience
======
* Fall 2024: Quantum Weight Initialization for AdaBoost
  * Advisor: Professor David Bernal Neira
  * Extended usage of optimization via analog quantum computers as an approach for weight pre-processing in AdaBoost
  * Explored usage of different metrics in examining data weight initialization performance against final F-1 score
  * Evaluated results based on quantitative analysis with L1 and Wasserstein distances and qualitative analysis based on final datapoint weighting and decision boundary

* Fall 2024: Quantum Dataset Reduction
  * Advisor: Professor David Bernal Neira
  * Developed an understanding of quantum optimization using analog quantum computers and the application of Rydberg blockade effects for solution to maximum independent set problem
  * Wrote the post-processing algorithm used in turning the quantum probabilistic solution into a classical result
  * Quantized training data such that current neutral atom lattice computers were able to operate on the datasets in our optimization algorithm
  * Demonstrated the effectiveness of quantum maximum independent set as an approach for data reduction

* Summer 2023-Spring 2024: Data Free Model Extraction
  * Advisor: Professor Lin Tan, PhD students Jonathan Rosenthal and Shanchao Liang
  * Implemented data augmentation and transformation techniques on CIFAR100 images with PyTorch data pipeline
  * Formulated novel generative replay step for improvement to state-of-the-art data free model extraction method DisGUIDE, based on a normalized mean latent vector for generation of specific classes, speeding up discovery of image classes by improving diversity of class generation at low query counts
  * Shared and discussed results to collaborate with PI and graduate student mentors and grow skills for literature review, experiment formulation, and result dissemination
  * Tested implementations and simple generative experiments with HuggingFace vision transformers and language models

* Summer 2023: Quantum Naive Bayes
  * Examined previous approach for a Quantum Naïve Bayes system for binary classification of 0/1 on the MNIST dataset
  * Helped other project members develop an understanding of the classical naïve bayes approach
  * Implemented preprocessing for the MNIST dataset, and a 10-qubit naïve bayes quantum system using Qiskit
  * Tested the implementation, and found generally poorer results than previously reported

* Spring 2022-Spring 2023: Collaborative Robotics Lab
  * Advisor: PhD student Mythra V. Balakuntala, (Professor Richard Voyles)
  *	Utilized ROS functionality to obtain information from and control a robotic arm for reinforcement learning
  *	Implemented simple behavioral cloning as supervised trajectory learning for a robotic arm for use in medical ultrasounds
  *	Programmed a neural network in PyTorch to serve as a gesture classification system for a demonstration of concept pipeline in human coaching of a Baxter robotic arm
  *	Used CoppeliaSIM and OpenAI gym frameworks to create simulated environment for testing of reinforcement learning techniques for pick and place object manipulation to mimic human coaching ‘styles’

* Summer 2022-Winter 2022: Automatic Program Repair
  * Advisor: Professor Lin Tan, PhD student Nan Jiang
  *	Designed and executed experiments on ensemble learning methods for automatic program repair (APR) via the training of ‘local’ models on partitioned data sets after conducting a literature review for APR and ensemble techniques
  *	Manipulated and partitioned data with Python to produce distinct clustered and categorized training sets from combined training data before working with PyTorch framework to train graph transformer network
  *	Evaluated model effectiveness on QuixBugs benchmark and analyzed performance through use of ablative tests and attention maps, with understandings gained from conducting literature review for explainable DL and analysis of attention maps
  *	Presented findings and work process in mock symposium held by the Purdue SURF program under Purdue EURO

* Summer 2022: Quantum Convolutional Networks
  *	Analyzed journal articles on Grover’s and Shor’s algorithms, as well as variational quantum computing
  *	Examined quantum computing concepts and gates as well as implementation with Q# and Qiskit
  *	Developed an understanding for quantum neural networks and quantum convolutional layers through journal article discussion and literature review
  *	Implemented and tested previous works in quantum convolutional networks and optimization processes
  *	Designed and tested own novel implementation for a quantum convolutional layer, dubbed CRCartesian

<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Teaching
======
* Undergraduate Teaching Assistant: Purdue CS251 Intro to Data Structures and Algorithms
  *	Held office hours and led PSOs to assist students in understanding course material
  *	Developed quiz and homework questions to assess student learning outcomes
  *	Tested projects for probabilistic data structures in Python

Service and leadership
======
* CS Project Mentor: Purdue Launchpad
  *	Mentored two newly admitted freshmen individually over two years
  *	In both cases, helped with implementation of model and training in PyTorch
  *	Project 1: Assisted in learning Reinforcement Learning and implementation of an RL pipeline for poker
  *	Projet 2: Assisted in implementation of a supervised learning pipeline for gesture recognition
