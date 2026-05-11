# Stress Classification: Empatica E4 vs Polar H10

## Overview

This project presents a comparative machine learning study for physiological stress classification using data collected from two wearable sensing devices:

- Empatica E4
- Polar H10

The system analyzes physiological signals, performs feature engineering, trains machine learning and deep learning models, and evaluates stress prediction performance across both devices.

The primary objective is to determine the effectiveness of wearable biosensors for real-time stress monitoring and classification.

---

# Project Objectives

- Collect and preprocess physiological sensor data
- Extract meaningful stress-related features
- Train and evaluate machine learning models
- Compare performance between Empatica E4 and Polar H10
- Analyze feature importance and model behavior

---

# Sensors Used

## Empatica E4

The Empatica E4 wristband provides multiple physiological and motion-based signals including:

- Blood Volume Pulse (BVP)
- Heart Rate (HR)
- Inter-Beat Interval (IBI)
- Accelerometer Data (ACC)
- Skin Temperature (TEMP)

## Polar H10

The Polar H10 chest strap provides high-precision cardiac measurements including:

- Electrocardiogram (ECG)
- Heart Rate (HR)
- Heart Rate Variability (HRV)
- Inter-Beat Interval (IBI)
- Accelerometer Data (ACC)

---

# Machine Learning Pipeline

The project follows a complete ML workflow:

1. Data Collection
2. Data Cleaning
3. Signal Preprocessing
4. Feature Engineering
5. Feature Selection
6. Model Training
7. Performance Evaluation
8. Comparative Analysis

---

# Models Used

The following machine learning and deep learning models were explored:

- Random Forest
- Logistic Regression
- Decision Tree Classifier
- XGBoost
- CatBoost
- LightGBM
- Multi-Layer Perceptron (MLP)
- DeepMLP

CatBoost demonstrated the best overall performance for stress classification across wearable sensor datasets.

---

# Project Structure

```text
Stress-Classification-E4-vs-H10/
│
├── datasets/
│   ├── E4/
│   └── H10/
│
├── notebooks/
│   ├── empatica_e4_model.ipynb
│   └── polar_h10_model.ipynb
│
├── reports/
│   ├── project_report.pdf
│   ├── project_presentation.pptx
│   └── project_poster.jpg
│
├── images/
│   ├── catboost_model_architecture.png
│   ├── methodology.jpg
│   ├── empatica_e4_results.png
│   └── polar_h10_results.png
│
├── demo/
│   └── project_video.mp4
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Dataset Information

The repository contains complete datasets collected from:

- Empatica E4 wearable sensor
- Polar H10 physiological monitoring device

The combined dataset size is approximately 120 MB and includes physiological recordings used for stress classification experiments and comparative analysis.

---

# Key Features

- Multi-sensor stress analysis
- Physiological signal processing
- Feature engineering from biosignals
- Comparative wearable study
- CatBoost-based classification pipeline
- Deep learning-based stress prediction
- Data visualization and analysis
- Model performance evaluation

---

# Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/stress-classification-e4-vs-h10.git
```

Navigate to the project directory:

```bash
cd stress-classification-e4-vs-h10
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

- `empatica_e4_model.ipynb`
- `polar_h10_model.ipynb`

and execute the cells sequentially.

---

# Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- Weighted F1-Score
- Confusion Matrix

---

# Results

The comparative analysis demonstrates the effectiveness of physiological wearable sensors in stress detection tasks.

Key observations include:

- CatBoost achieved the best classification performance
- Physiological feature engineering significantly improved results
- Empatica E4 provided richer multimodal physiological data
- Polar H10 delivered highly reliable cardiac measurements
- Deep learning models improved nonlinear stress pattern recognition

---

# Applications

This project can be extended for:

- Real-time stress monitoring
- Mental health assessment
- Workplace wellness systems
- Healthcare analytics
- Wearable AI systems
- Human activity and emotion recognition

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- LightGBM
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

# Future Improvements

- Real-time streaming classification
- Mobile application deployment
- Cloud-based monitoring dashboard
- Larger multi-subject dataset collection
- Advanced signal denoising techniques
- Transformer-based physiological signal modeling

---

# Author

Adarsh V Kapse

---

# License

This project is intended for academic and research purposes.