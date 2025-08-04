# rTMS Machine Learning Simulation

This project simulates clinical and protocol data from repetitive transcranial magnetic stimulation (rTMS) treatment for depression, and uses machine learning models to predict treatment response.

## 🧪 Goal

To develop and refine a machine learning pipeline that can predict rTMS treatment responders vs non-responders using:
- Clinical features (PHQ-9, age, illness duration)
- Protocol features (frequency, target, pulses, sessions)
- Derived features (e.g., total pulses)

This serves as a learning exercise for working with health data, modeling response prediction, and preparing for future work with real clinical and imaging data.

## 📁 Files

- `rTMS_Model.ipynb`: Main notebook containing simulation, preprocessing, model training and evaluation.
- `requirements.txt`: List of packages used.
- (Future) `data/`: Real or semi-simulated datasets.
- (Future) `visuals/`: Figures and output plots.

## 📊 Methods

- Simulated dataset of 200 patients
- Preprocessing: encoding, scaling, train-test split
- Models: Logistic Regression, Random Forest
- Evaluation: accuracy, confusion matrix, classification report, ROC AUC

## 🔍 Example Features

| Feature            | Type         |
|--------------------|--------------|
| Age                | Numerical    |
| PHQ-9 Score        | Numerical    |
| Illness Duration   | Numerical    |
| Frequency          | Categorical  |
| Target Area        | Categorical  |
| Sessions           | Numerical    |
| Pulse Count        | Numerical    |
| Total Pulses       | Derived      |

## 🚧 Future Plans

- Explore additional ML models (e.g., XGBoost, SVM)
- Use real patient data
- Incorporate rs-fMRI data from OpenNeuro or other sources
- Extend to continuous outcome prediction (e.g., % improvement)

## 💡 Motivation

This project is part of a broader effort to bridge neuroscience and AI by building skills in:
- Machine learning
- Health data science
- Neuroimaging
- Reproducible research

## 📫 Contact

Created by AaronNeuroResearh
Email: aaronjackson0203@gmail.com
