# Higgs Boson Classification

A machine learning project for classifying Higgs boson signal events from background noise using the UCI HIGGS dataset.

## Overview

This project applies classical machine learning and deep learning techniques to the Higgs boson detection problem — distinguishing signal events (Higgs boson production) from background noise using Monte Carlo simulated data.

**Dataset:** [HIGGS — UCI ML Repository](https://archive.ics.uci.edu/dataset/280/higgs)  
**Samples:** 11,000,000 (using 500K subset)  
**Features:** 28 (21 low-level + 7 high-level physics features)  
**Task:** Binary classification (0 = background, 1 = signal)

---

## Project Structure

```
higgs-classification/
│
├── data/               # Raw dataset (not tracked by git)
├── notebooks/          # Jupyter notebooks
│   ├── 01_eda.ipynb            # Exploratory Data Analysis
│   ├── 02_baseline_models.ipynb # Logistic Regression, Random Forest
│   ├── 03_xgboost.ipynb        # Gradient Boosting models
│   └── 04_neural_network.ipynb  # MLP Deep Learning model
├── models/             # Saved trained models
├── plots/              # Generated figures and charts
├── src/                # Helper scripts and utilities
└── requirements.txt    # Python dependencies
```

---

## Models

| Model               | AUC-ROC | Notes                     |
| ------------------- | ------- | ------------------------- |
| Logistic Regression | TBD     | Baseline                  |
| Random Forest       | TBD     | Ensemble baseline         |
| XGBoost             | TBD     | Strong classical baseline |
| MLP Neural Network  | TBD     | Deep learning approach    |

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOURUSERNAME/higgs-boson-classification.git
cd higgs-boson-classification
```

### 2. Create and activate virtual environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Download the dataset

Download the HIGGS dataset from [UCI ML Repository](https://archive.ics.uci.edu/dataset/280/higgs) and place the CSV file in the `data/` folder.

### 5. Launch Jupyter

```bash
jupyter notebook
```

<!-- ---

## Key Findings

> Results will be added as the project progresses.

---

## References

- Baldi, P., Sadowski, P., & Whiteson, D. (2014). _Searching for Exotic Particles in High-Energy Physics with Deep Learning._ Nature Communications.
- [HIGGS Dataset — UCI ML Repository](https://archive.ics.uci.edu/dataset/280/higgs)

---

## Author

**Your Name**
Diploma Project — [Your University Name]
Year: 2025 -->
