---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Rinor Cakaj, a PhD candidate at the University of Stuttgart in the Institute of Signal Processing and System Theory, where I am advised by [Prof. Dr.-Eng. Bin Yang](https://www.iss.uni-stuttgart.de/institut/team/Yang-00004/) and co‑supervised by [Dr. rer. nat. Jens Mehnert](https://www.linkedin.com/in/drjensmehnert/). I have done my PhD in cooperation with Robert Bosch GmbH, have completed my thesis, and will defend it soon. My research focused on improving the performance of Convolutional Neural Networks (CNNs) for computer vision tasks.

I currently work as a **Solution Architect at Quality Match GmbH** in Heidelberg and am **Co‑Founder & Full‑Stack Developer of Fletza** in Stuttgart, an AI‑driven platform that converts lecture materials into flashcards, quizzes, and exam simulations. Feel free to reach out to me via [email](mailto:rinor.cakaj@de.bosch.com). You can also check out my [CV](/cv/).

## Expertise & Technical Interests

My research focused on developing new regularization techniques and innovative CNN architectures to improve their efficiency and performance. As part of my PhD, I have published five papers and authored five patents related to these novel methods, with one already published and four currently under review. Additionally, I’ve gained a deep understanding of other deep learning architectures, including Transformers (such as Vision Transformers (ViT) and Large Language Models (LLMs)).

## Professional Experience

### Quality Match GmbH — Solution Architect 

* Developing AI‑driven techniques to automatically evaluate and improve data quality.
* Designing and building Nano‑Task Trees and pipelines for efficient data annotation.
* Implementing an LLM‑based solution that automatically designs Nano‑Tasks.

### Fletza — Co‑Founder & Full‑Stack Developer

* Building an AI‑driven platform that transforms lecture materials (PDF, Word, PPTX) into flashcards, quizzes, and exam questions.
* Integrating the SM‑2 spaced‑repetition algorithm (similar to Anki) for effective learning.
* Providing exam simulations with automatic feedback.
* Learn more at [www.fletza.com](https://www.fletza.com).


## Selected Publication

- **[CNN Mixture‑of‑Depths (MoD)](/publication/2024-10-01-mod)** — *ACCV 2024&nbsp;(Accepted)*  
  **Authors:** Rinor Cakaj, Jens Mehnert, Bin Yang  
  **Contribution:** Introduces MoD, a channel‑selective inference technique that reduces compute while preserving accuracy.  
  **Impact**  
  - *ImageNet:* ResNet75‑MoD matches ResNet50 with **25 % CPU / 15 % GPU speed‑up**; ResNet86‑MoD ↑ **0.45 % accuracy** with **6 % CPU / 5 % GPU speed‑up**  
  - *Cityscapes:* FCN‑ResNet86‑MoD ↑ **0.95 % mIoU** at similar cost  
  - *Pascal VOC:* Faster‑RCNN‑ResNet86‑MoD ↑ **0.37 % mAP** (+0.4 % AP50) with **10 % CPU speed‑up**  

  [ArXiv](https://arxiv.org/abs/2409.17016)

## Talks & Workshops

* **AI Officer Course, Stuttgart - Speaker (20 May 2025):** One‑day curriculum on Generative AI, Machine Learning, and Deep Learning (same as Hamburg session).
* **AI Governance Workshop, Erlangen - Technical Advisor (13 May 2025):** Guidance on integrating LLMs in workplace environments; covered model limitations, data usage, and monitoring.
* **AI Officer Course, Hamburg - Speaker (10 Apr 2025):** Introduced Generative AI, detailed GPT architecture/training, and presented RAG and RLHF techniques.

## Background

Before starting my PhD, I completed a master’s degree in Mathematics interdisciplinary Informatics and a bachelor’s degree in Business Mathematics at the Technical University of Darmstadt. I also gained work experience as a working student in CIO Consulting - Digital Strategy at KPMG and as a mathematician in a multi family office at Segura & Jesberger GmbH.

## Personal Projects

### Stock Index Trend Prediction Tool

In addition to my academic research, I’ve been working on a personal project to predict stock index trends using deep learning. I developed an end-to-end pipeline, starting with automatic data collection through web scraping and adding a plausibility check for data integrity. The data is processed using rolling statistics and data augmentation techniques to enhance robustness, followed by splitting it into training, validation, and test sets.

The deep learning model uses multi-scale convolutions to capture diverse patterns and BiLSTM layers to handle temporal dependencies. Implemented in Python and PyTorch, this project allowed me to gain practical experience with various tools and libraries, categorized as follows:

* **Development Environment**: JupyterLab, VS Code, Anaconda
* **Data Processing and Visualization**: Pandas, NumPy, Plotly, Matplotlib, Scipy
* **Automation and Testing**: Selenium, Pytest, Optuna
* **Model Tracking and Deployment**: Weights & Biases, TensorBoard, Docker, Git
* **Documentation**: Sphinx

### Electronic Access Control System

For my local swimming club, I developed an electronic access control system using a Raspberry Pi 4 and Python. The system features a GUI, an RFID reader with cards, and a touch display, providing an efficient way for members to access the club.

### Early App Development

During my school years, I created simple Android and iOS apps, such as a calculator and a game called "Bouncing Ball," where the goal was to keep the ball in the air. The apps were implemented in Java for Android and Swift for iOS. These early projects sparked my interest in software development and problem-solving.
