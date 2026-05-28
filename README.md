# Breast Cancer Detection using Multi-Input Deep Learning

[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue.svg)](https://www.kaggle.com/code/mandanabakhshi/cw2-25400380-breast-cancer-model)
[![Python](https://img.shields.io/badge/Python-3.10+-green.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.17-orange.svg)](https://www.tensorflow.org/)
[![Flask](https://img.shields.io/badge/Flask-Deployed-red.svg)](https://flask.palletsprojects.com/)

## Overview

This project develops **multi-input deep learning models** for breast cancer detection using the **CBIS-DDSM (Curated Breast Imaging Subset of Digital Database for Screening Mammography)** dataset. The models combine:

- **Mammogram images** (processed through DenseNet121)
- **Clinical metadata** (breast density, subtlety, assessment, etc.)

The system provides a **Flask-based web interface** for real-time cancer detection.

## Key Achievements

| Metric | Mass Model | Calcification Model |
|--------|------------|---------------------|
| Accuracy | 77% | 69% |
| AUC-ROC | 0.828 | 0.73 |
| Sensitivity (Recall) | 75% | 66% |
| Specificity | 85% | 65% |


## Installation

### Local Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/breast-cancer-detection.git
cd breast-cancer-detection

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```


