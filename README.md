# Unified Computational Framework for ENSO Analysis

## Overview
This project presents a unified computational framework for analyzing El Niño–Southern Oscillation (ENSO) dynamics using statistical, nonlinear, information-theoretic, operator-theoretic, and recurrence-based approaches.

The framework integrates multiple computational methodologies to study complex climate interactions, nonlinear dependencies, temporal dynamics, and causal relationships across large-scale ENSO datasets.

The project focuses on understanding climate variability using data-driven modeling, nonlinear dynamics, and advanced computational analysis techniques.

---

# Problem Statement
ENSO is one of the most influential large-scale climate phenomena affecting global weather patterns, ocean-atmosphere interactions, rainfall variability, and environmental systems.

Traditional linear analytical methods often fail to capture:
- nonlinear climate dependencies,
- hidden temporal dynamics,
- directional interactions,
- complex regime transitions.

This project aims to develop an integrated computational framework capable of analyzing ENSO dynamics using both classical statistical methods and modern nonlinear analytical approaches.

---

# Objectives
- Develop a unified pipeline for ENSO analysis
- Study nonlinear interactions in climate systems
- Identify dominant ENSO temporal modes
- Analyze causal dependencies between oceanic and atmospheric variables
- Explore recurrence structures and regime transitions
- Apply data-driven dynamical systems modeling techniques

---

# Dataset Information

## Dataset
- Multivariable ENSO climate dataset
- 16 climate-related variables
- 498-month temporal observations

## Variables Included
Examples include:
- Oceanic Niño Index (ONI)
- Sea Surface Temperature (SST)
- Atmospheric variables
- Oceanic circulation indicators
- Pressure-related climate indices

---

# Methodology

## 1. Statistical Analysis
Classical statistical methods were applied for initial exploratory analysis.

### Techniques Used
- Pearson Correlation
- Principal Component Analysis (PCA)

### Purpose
- Identify dominant variability patterns
- Analyze linear relationships
- Reduce dimensionality

---

## 2. Information-Theoretic Analysis

### Mutual Information
Used to capture nonlinear dependencies between climate variables beyond linear correlation.

### Transfer Entropy
Applied for directional causal analysis between oceanic and atmospheric processes.

### Key Findings
- Ocean-to-atmosphere forcing relationships identified
- Nonlinear interactions captured more effectively than Pearson correlation

---

# Operator-Theoretic Modeling

## Dynamic Mode Decomposition (DMD)
DMD was used to extract dominant temporal modes governing ENSO behavior.

### Features
- Hankel time-delay embedding
- Modal decomposition
- Temporal pattern extraction

---

## Koopman Operator Analysis
Derived a Koopman-based governing equation to model ENSO dynamics using DMD eigenvalue structures.

### Outcomes
- Physically interpretable modal representation
- Identification of dominant oscillatory climate modes

---

# Recurrence-Based Analysis

## Recurrence Quantification Analysis (RQA)
RQA was performed to study nonlinear temporal recurrence structures within ENSO dynamics.

### Metrics Analyzed
- Determinism (DET)
- Recurrence structures
- Temporal complexity

### Observations
- Strong deterministic behavior identified
- Distinct regime transition patterns observed

---

## Recurrence Networks
Constructed recurrence networks to analyze:
- Topological climate structures
- El Niño phase dynamics
- La Niña transitions
- Neutral-state behavior

---

# Computational Pipeline

The framework integrates:
- Statistical methods
- Information theory
- Dynamical systems modeling
- Nonlinear recurrence analysis
- Climate time-series processing

This unified approach enables comprehensive ENSO characterization across multiple analytical domains.

---

# Technologies Used

## Programming & Libraries
- Python
- NumPy
- Pandas
- Scikit-learn
- SciPy
- Matplotlib

## Analytical Techniques
- PCA
- DMD
- Koopman Analysis
- Mutual Information
- Transfer Entropy
- Recurrence Analysis

## Domains
- Climate Data Analytics
- Nonlinear Dynamics
- Time-Series Modeling
- Computational Physics

---

# Results & Observations

## Key Findings
- Mutual Information captured nonlinear dependencies better than Pearson correlation
- Transfer Entropy confirmed directional ocean-atmosphere forcing
- DMD extracted dominant ENSO temporal modes
- Recurrence analysis identified deterministic climate structures
- Recurrence networks revealed regime-specific topological transitions

---

# Applications
- Climate variability analysis
- Nonlinear time-series modeling
- Dynamical systems research
- Environmental data analytics
- Computational climate science
- Predictive climate modeling

---

# Future Improvements
- Integration of transformer-based temporal models
- Hybrid physics-informed AI systems
- Real-time climate forecasting pipelines
- Graph neural network-based recurrence analysis
- Large-scale climate simulation integration

---

# Note
This project is currently under active development and code refactoring. Some modules, notebooks, and workflows are being optimized, cleaned, and reorganized for improved reproducibility and documentation.

Due to the large experimental setup and ongoing refinement process, additional notebooks, preprocessing scripts, analytical workflows, and supporting code files will be updated progressively.

For complete implementation details or research-related discussions, feel free to connect.

---

# Author

## Athira Panicker
M.Tech Data Science  
AI | Nonlinear Dynamics | Climate Analytics | Machine Learning

### Connect
- GitHub: https://github.com/panickerathira08-boop
- LinkedIn: https://www.linkedin.com/in/athira-p-1408ap

---
