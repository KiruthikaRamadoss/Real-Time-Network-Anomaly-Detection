# Real-Time-Network-Anomaly-Detection

An end-to-end machine learning pipeline for detecting anomalies in synthetic network traffic, aimed at identifying potential cybersecurity threats.

## Table of Contents

- [Overview](#overview)
- [Project Highlights](#project-highlights)
- [Tools & Techniques](#tools--techniques)
- [Poster Presentation](#poster-presentation)
- [Dataset](#dataset)
- [Notebook](#notebook)
- [How to Run](#how-to-run)
- [Contact](#contact)

## Overview
This repository contains code and resources for detecting anomalies in synthetic network traffic using machine learning models. The primary objective is to identify unusual patterns that may indicate cybersecurity threats by implementing a structured ML pipeline.

## Project Highlights

- Developed a machine learning pipeline in Python using `scikit-learn` to detect anomalies in network traffic.
- Addressed class imbalance using **SMOTE**, improving model sensitivity to rare attack instances.
- Applied **Principal Component Analysis (PCA)** for dimensionality reduction and better visualization.
- Trained and evaluated **Isolation Forest** and **Random Forest** classifiers.
- Achieved **83% recall** and **63% accuracy** in detecting anomalies.

## Tools & Techniques

- Python, scikit-learn, pandas, matplotlib
- SMOTE (imbalanced-learn)
- Random Forest, Isolation Forest
- PCA for feature reduction
- Jupyter Notebook for development and visualization

## Poster Presentation

This project was presented at:
- **TXST 1st Data and AI Day – Student Poster Showcase (2025)**

📄 [View Poster (PDF)](Poster%20-%20Kiruthika_Ramadoss.pdf)

## Dataset

- **File**: `synthetic_network_traffic.csv`
- **Description**: A labeled synthetic dataset simulating normal and anomalous network traffic behavior.

📁 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1iSv1C7xmcWMhfMHxbd48Hc_-lJZIUgzn/view?usp=sharing)

## Notebook

The notebook includes the complete ML pipeline:
- Data preprocessing
- Feature selection and dimensionality reduction
- Model training and evaluation
- Visualizations and metrics reporting

📓 [View Jupyter Notebook](Anomaly_Detection.ipynb)

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/KiruthikaRamadoss/Real-Time-Network-Anomaly-Detection.git
   cd Real-Time-Network-Anomaly-Detection
   
2. (Optional) Create and activate a virtual environment:
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

4. Install dependencies:
   pip install -r requirements.txt

6. Launch the notebook:
   jupyter notebook Anomaly_Detection.ipynb


   ## Contact

   For any inquiries or collaboration opportunities:

- [LinkedIn](https://www.linkedin.com/in/kiruthikaramadoss/)
- [GitHub](https://github.com/KiruthikaRamadoss)  
- [Email](mailto:k_r549@txstate.edu)

