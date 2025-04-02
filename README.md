# Hybrid Intrusion Detection System (IDS)

## Overview
This project implements a **Hybrid Intrusion Detection System (IDS)** that combines **Unsupervised Anomaly Detection** and **Supervised Classification** to enhance cybersecurity threat detection.

## Features
- **Anomaly Detection** using:
  - Isolation Forest
  - One-Class SVM
- **Supervised Classification** with:
  - Random Forest
  - Support Vector Machine (SVM)
  - Deep Neural Networks (DNN)
  - Long Short-Term Memory (LSTM)
- **Feature Engineering** techniques:
  - Recursive Feature Elimination (RFE)
  - Principal Component Analysis (PCA)
- **Performance Evaluation** including:
  - 10-Fold Cross-Validation
  - Hyperparameter Tuning
  - Confusion Matrix
  - ROC Curve Analysis
- **Explainable AI (XAI) Implementation** (Upcoming):
  - SHAP (SHapley Additive exPlanations)
  - LIME (Local Interpretable Model-agnostic Explanations)

## Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Run the main script to train and evaluate the IDS model:
```bash
python ids2.py
```

## Project Structure
```
├── data/              # Dataset folder
├── models/            # Saved trained models
├── notebooks/         # Jupyter notebooks for analysis
├── ids2.py           # Main script for IDS implementation
├── requirements.txt   # Required Python dependencies
└── README.md          # Project documentation
```

## Results
- Model performance metrics will be stored in `results/`
- Visualization plots for ROC curves and confusion matrices will be saved

## Future Improvements
- Implementation of **Explainable AI (XAI)** with SHAP and LIME
- Integration with real-time network traffic monitoring
- Deployment as a cloud-based IDS solution

## Contributing
Feel free to open issues or submit pull requests if you want to contribute!


