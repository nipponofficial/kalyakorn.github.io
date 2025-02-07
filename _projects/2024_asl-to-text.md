---
layout: project
title: Sign Language (ASL) to Text Translation
subtitle: "A real-time sign language to text translation system"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

This project is the final project for the **Deep Learning** class at **Tsinghua University**, taught by <a href="https://www.xlhu.cn/">Prof. Xiaolin Hu</a>. Our team consists of myself, Boqiao Wang, and Yingwei Shi.

Sign language serves as a critical communication tool for the hard-of-hearing and deaf communities. However, the lack of widespread understanding among non-signers presents a significant barrier to effective communication. This project aims to bridge this gap by developing a deep learning-based system that translates American Sign Language (ASL) gestures into text.

Utilizing an open-source ASL dataset with 87,000 images across 29 classes, we implement and evaluate two models: a Convolutional Neural Network (CNN) and StarNet. While the CNN model provides a reliable baseline, StarNet introduces a lightweight yet efficient approach to feature extraction. Both models undergo training with data augmentation and are optimized using the Adam optimizer with categorical cross-entropy loss.

Our findings demonstrate the potential of deep learning for real-time ASL recognition, paving the way for applications that promote accessibility and inclusivity for the deaf and hard-of-hearing communities. Future work will focus on enhancing model accuracy, expanding datasets, and integrating real-time applications.

Please refer to our <a href="/assets/projects/2024_asl-to-text/report.pdf">report</a> for implementation details.