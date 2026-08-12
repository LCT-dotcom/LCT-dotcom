<div align="center">

# Biomedical Signal Processing & Machine Learning

**Building reproducible deep-learning pipelines for ECG, PPG, and wearable health data.**

[![Profile](https://img.shields.io/badge/GitHub-LCT--dotcom-181717?style=flat-square&logo=github)](https://github.com/LCT-dotcom)

</div>

## About

I develop research-oriented machine-learning systems for physiological time-series data, with a focus on:

- ECG and wearable PPG signal processing
- temporal deep learning and domain adaptation
- leakage-aware validation and subject-level generalization
- reproducible experiments, clear limitations, and responsible reporting

My goal is to turn experimental biomedical AI work into implementations that other researchers can inspect, reproduce, and extend.

## Featured research

| Project | What it demonstrates |
|---|---|
| [**AD8232 ECG Domain Adaptation**](https://github.com/LCT-dotcom/ad8232-ecg-domain-adaptation) | End-to-end audit and Stage-B adaptation of a three-class ECG beat classifier, evaluated with a leakage-controlled temporal protocol. |
| [**PPG-DaLiA Heart-Rate Estimation**](https://github.com/LCT-dotcom/ppg-dalia-temporal-heart-rate-estimation) | Configurable PPG/ACC temporal modeling, strict leave-one-subject-out evaluation, ablation studies, and TorchScript export. |

## Technical focus

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Research principles

- **Validate honestly:** split data before feature extraction and prevent temporal or subject leakage.
- **Document decisions:** publish configurations, evaluation protocols, limitations, and reproducibility notes.
- **Report responsibly:** distinguish proof-of-concept results from independent or clinical validation.
- **Build for reuse:** organize code, experiments, and artifacts so others can understand the workflow quickly.

## Current direction

I am currently exploring robust physiological time-series models that generalize across subjects, devices, activities, and recording conditions.

> Research software only. The projects on this profile are not medical devices and are not intended for clinical diagnosis.

