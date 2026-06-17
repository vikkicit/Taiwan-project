# Taiwan Project – Phase 2: Hyperspectral Imaging-Based Gastrointestinal Disease Classification

## Overview

Phase 2 of the Taiwan Project focuses on the development of an AI-driven diagnostic framework for the classification of Gastrointestinal (GI) diseases using Hyperspectral Imaging (HSI). The objective is to leverage the rich spatial and spectral information available in hyperspectral data to improve disease detection, classification accuracy, and model interpretability.

Unlike conventional White Light Imaging (WLI), which captures only RGB information, HSI acquires hundreds of narrow spectral bands, enabling detailed analysis of tissue composition and biochemical characteristics. This enhanced spectral information provides a stronger foundation for machine learning and deep learning models to identify subtle pathological changes associated with GI disorders.

The project targets the classification of:

* Barrett's Esophagus (BE)
* High-Grade Dysplasia (HGD)
* Polyps
* Gastrointestinal Cancer
* Suspicious Lesions
* Normal Tissue

---

## Objectives

* Develop an AI-based classification system for GI disorders.
* Compare traditional WLI and Hyperspectral Imaging approaches.
* Identify optimal spectral wavelength bands for disease discrimination.
* Improve classification performance through spectral feature extraction.
* Reduce information loss caused by RGB-based imaging systems.
* Enhance model transparency using Explainable AI techniques.
* Generate Grad-CAM visualizations to highlight clinically relevant regions.

---

## Dataset

### Input Data Sources

#### White Light Imaging (WLI)

* Standard RGB endoscopic images.
* Baseline clinical imaging modality.
* Used for comparison with hyperspectral approaches.

#### Hyperspectral Imaging (HSI)

* Multi-band spectral images.
* Captures both spatial and spectral information.
* Generates spectral cubes containing tissue reflectance data.
* Provides detailed biochemical and structural signatures.

---

## Project Workflow

### Phase 1: Data Acquisition

* Collect GI endoscopic datasets.
* Acquire WLI and HSI image samples.
* Organize images according to disease categories.

### Phase 2: Data Preprocessing

* Noise reduction.
* Image normalization.
* Spectral calibration.
* Removal of corrupted spectral bands.
* Data quality validation.

### Phase 3: Spectral Band Selection

* Analyze hyperspectral wavelength responses.
* Identify informative nanoband spectral regions.
* Remove redundant spectral information.
* Optimize feature representation.

### Phase 4: Feature Extraction

#### Spatial Features

* Texture analysis.
* Morphological characteristics.
* Lesion boundary information.

#### Spectral Features

* Reflectance signatures.
* Absorption characteristics.
* Tissue-specific spectral patterns.

### Phase 5: Model Development

Machine Learning Models:

* Support Vector Machine (SVM)
* Random Forest (RF)

Deep Learning Models:

* Convolutional Neural Networks (CNN)
* Spectral-Spatial Deep Learning Architectures

### Phase 6: Training and Validation

* Dataset splitting.
* Model training.
* Hyperparameter optimization.
* Cross-validation.
* Performance monitoring.

### Phase 7: Classification

Disease categories:

* Barrett's Esophagus
* High-Grade Dysplasia
* Polyps
* GI Cancer
* Suspicious Lesions
* Normal Tissue

### Phase 8: Performance Evaluation

Evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

### Phase 9: WLI vs HSI Comparative Analysis

Comparative assessment of:

* Classification Accuracy
* Disease Detection Rate
* Spectral Information Utilization
* Model Robustness
* Clinical Interpretability

### Phase 10: Explainable AI Integration

To overcome black-box limitations of deep learning models, Explainable AI (XAI) techniques are incorporated.

Key goals:

* Improve clinical trust.
* Visualize decision-making processes.
* Identify disease-specific regions influencing predictions.
* Support medical interpretation.

### Phase 11: Grad-CAM Generation

Gradient-weighted Class Activation Mapping (Grad-CAM) is applied to visualize model attention regions.

Outputs include:

* Heatmap generation.
* Lesion localization.
* Disease-specific activation maps.
* Overlay visualization on original GI images.

Grad-CAM enables clinicians to verify whether the model focuses on medically relevant tissue regions during classification, improving transparency and reliability.

---

## Technologies Used

* Python
* PyTorch
* TensorFlow
* OpenCV
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

---

## Expected Outputs

* Trained Classification Models
* Spectral Band Selection Results
* Disease Classification Reports
* Accuracy Metrics
* Confusion Matrix
* WLI vs HSI Performance Comparison
* Explainable AI Visualizations
* Grad-CAM Heatmaps

---

## Future Scope

* Real-Time Endoscopic Disease Detection
* Clinical Decision Support Systems
* Multi-Center Validation Studies
* Deployment in Hospital Environments
* Integration with Advanced Explainable AI Frameworks

---

## Author

**Vigneshwaran N**

Taiwan Project – Phase 2 Research and Development
