# Quantum Classifier for Detecting Malaria from Red Blood Cells

## Project Overview

Malaria is one of the world's deadliest infectious diseases, affecting millions of people every year. Early diagnosis is essential for effective treatment and reducing mortality. This project presents a **Quantum-Classical Hybrid Machine Learning Model** for detecting malaria-infected Red Blood Cells (RBCs) using microscopic blood smear images.

The proposed system combines classical image processing techniques with a **Variational Quantum Classifier (VQC)** to improve classification accuracy while reducing computational complexity compared to conventional deep learning models.

---

## Problem Statement

Traditional malaria diagnosis methods such as microscopy, Rapid Diagnostic Tests (RDT), and PCR are either time-consuming, expensive, or require skilled professionals. Conventional deep learning models provide high accuracy but demand large datasets and high computational resources.

This project addresses these limitations by introducing a **Variational Quantum Classifier (VQC)** that efficiently classifies malaria-infected and uninfected red blood cells using optimized image features.

---

## Objectives

- Detect malaria-infected Red Blood Cells automatically.
- Develop a Quantum-Classical Hybrid Classification Model.
- Extract meaningful image features using Contourlet Transform.
- Reduce feature redundancy using PCA and mRMR.
- Classify infected and uninfected RBCs using Variational Quantum Classifier (VQC).
- Identify the malaria parasite type using a Rule-Based Expert System.

---

## Dataset

**Dataset:** Malaria Cell Images Dataset (Kaggle)

The dataset contains microscopic images of:

- Infected (Parasitized) Red Blood Cells
- Uninfected Red Blood Cells

---

## Technologies Used

- Python
- Qiskit
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## Project Workflow

```

Microscopic RBC Images
↓
Image Preprocessing
↓
Contourlet Feature Extraction
↓
Feature Optimization (PCA + mRMR)
↓
Variational Quantum Classifier (VQC)
↓
Malaria Detection
↓
Rule-Based Expert System
↓
Malaria Parasite Type Identification

```

---

## Key Features

- Quantum-Classical Hybrid Architecture
- Image Preprocessing
- Contourlet-based Feature Extraction
- PCA & mRMR Feature Optimization
- Variational Quantum Classifier (VQC)
- Rule-Based Parasite Identification
- High Accuracy with Low Computational Complexity
- Scalable Medical Image Analysis Framework

---

## Performance Evaluation

The model was evaluated using standard classification metrics:

- Accuracy
- Precision
- Recall
- Specificity
- F1-Score
- Confusion Matrix

---

## Results

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

### Model Output

![Prediction Output](images/prediction_output.png)

---

## Challenges

- Variability in microscopic blood smear images
- Limited availability of quantum hardware
- Designing efficient quantum circuits
- Integration of classical and quantum workflows
- Feature optimization for high-dimensional medical images

---

## Future Enhancements

- Deploy on real quantum hardware
- Improve multi-class malaria parasite classification
- Train on larger and more diverse datasets
- Develop a web-based diagnostic application
- Extend the framework to other medical image classification tasks

---

## Authors

**Abina R**
**Ananya S**
**Dr.Thilakavathy P**

B.E. Computer Science and Engineering

Vels Institute of Science, Technology & Advanced Studies (VISTAS)

Developed as a Final Year Academic Project in collaboration with a teammate.

---

##  Acknowledgement

This project was developed as part of the Bachelor's Degree curriculum at **Vels Institute of Science, Technology & Advanced Studies (VISTAS)**.

Special thanks to the faculty members and project guide for their continuous guidance and support throughout the development of this work.
