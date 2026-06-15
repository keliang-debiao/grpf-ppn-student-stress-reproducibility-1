# GRPF-PPN Student Stress Prediction

This repository provides the reproducible code and experimental materials for the manuscript **Data-Derived Prototype Profiles for Interpretable Student Stress Prediction from Psychometric Tabular Data**.

The project implements **GRPF-PPN**, an interpretable prototype-based model for student stress prediction from psychometric tabular data. The model combines feature-gated input modulation, residual representation learning, class-associated prototypes, and neural–prototype fusion to support both prediction and case-level explanation.

## Datasets

The study uses one primary dataset and three external validation datasets:

- Student Stress Factors: A Comprehensive Analysis  
  https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis

- Student Mental Health Dataset  
  https://www.kaggle.com/datasets/shariful07/student-mental-health

- Depression Anxiety Stress Scales Responses  
  https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses

- Medical Student Mental Health  
  https://www.kaggle.com/datasets/thedevastator/medical-student-mental-health

## Contents

This repository includes code for:

- data preprocessing
- repeated-split model training
- baseline comparison
- external validation
- ablation experiments
- prototype validation
- SHAP vs prototype explanation comparison
- table and figure generation

## Note

All datasets are publicly available secondary datasets. The learned prototypes should be interpreted as data-derived stress-related profiles, not as clinical diagnoses or validated psychological constructs.
