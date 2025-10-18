# Blood Group Detection Using Fingerprint Patterns – A Deep Learning Approach

This repository contains the official research paper and presentation slides for the paper titled "Blood Group Detection Using Fingerprint Patterns – A Deep Learning Approach," which was accepted and presented at the **International Conference on Advancing Technology in Engineering and Science (ICATES-2025)**.

The conference was organized by the **Xavier Institute of Engineering** in association with **The Institution of Engineering and Technology (IET)**.

---

## Authors

* Rohit Kandelkar
* Yash Jahagirdar
* Sukanya Bhaskar
* Rajeshwari Golande

**Mentor:**
* Prof. Anandkumar Birajdar

**Affiliation:**
* Department of Computer Engineering (Regional Language), PCCOE Pune, India

---

## Abstract

**Problem:** Traditional blood typing methods are accurate but suffer from significant drawbacks: they are invasive, time-consuming, and resource-intensive, making them non-ideal for emergencies or large-scale screening.

**Method:** This research proposes a non-invasive, cost-effective, and scalable alternative using deep learning. We evaluate multiple Convolutional Neural Network (CNN) architectures (Shallow, Custom, and Deep) to classify blood groups from fingerprint patterns.

**Key Results:** The models were trained on a publicly available Kaggle dataset that was rigorously preprocessed using class balancing (under-sampling), image normalization, and data augmentation to ensure robustness. Our findings show that a well-optimized **Shallow CNN outperformed** more complex and deeper models, achieving a final accuracy of **89.49%** with the fastest training time.

**Impact:** This work demonstrates that with a proper preprocessing pipeline, a simple and lightweight network can be a highly effective tool for biometric-based blood typing, offering a viable alternative to conventional serological methods.

---

## Methodology

Four different neural network architectures were implemented and compared under identical training and preprocessing conditions:

1.  **Shallow CNN:** A lightweight model with two convolutional layers.
2.  **Custom CNN:** A moderately deep model with three convolutional layers.
3.  **Deep CNN:** A deeper model with five convolutional layers and batch normalization.
4.  **MLP (Baseline):** A simple Multilayer Perceptron with no convolutional layers.

The results confirmed that the **Shallow CNN** provided the best balance of high accuracy (89.49%) and computational efficiency (130.7s training time).

---

## Repository Contents

* `BLOOD GROUP DETECTION USING FINGERPRINT PATTERNS – A DEEP LEARNING APPROACH .pdf`: The final accepted research paper.
* `ICATES RohitKandelkar.pptx`: The presentation slides from the ICATES 2025 conference.

---

## How to Cite

This paper is scheduled for publication in conference proceedings. A formal citation will be added here once it is available.