# SVM-PSO Bearing Fault Diagnosis in Rotating Machinery

**Intelligent fault detection of bearings using hybrid SVM-PSO (Support Vector Machine + Particle Swarm Optimization)**

This project implements a hybrid machine learning approach for predictive maintenance in rotating machinery. It combines SVM with PSO for hyperparameter optimization to achieve high-accuracy bearing fault classification.

### Key Features
- Used public **CWRU bearing dataset** (2,953 samples)
- Extracted 8 time-domain statistical features (RMS, kurtosis, skewness, crest factor, etc.)
- PSO optimized SVM hyperparameters (C ≈ 814.11, γ ≈ 1.42)
- Achieved **96.28% ± 0.50%** accuracy (5-fold cross-validation)

### Technologies
- Python, NumPy, Pandas, Scikit-learn, Matplotlib
- Particle Swarm Optimization (PSO)
- Support Vector Machine (SVM) with RBF kernel

### Results
- Average Accuracy: **96.28%**
- Precision / Recall / F1-Score: **96.28%**
- Near-perfect confusion matrix with minimal misclassifications

### Repository Contents
- `main.py` – Full implementation
- `pso_svm_optimizer.py` – PSO optimization class
- `extract_features.py` – Feature extraction from vibration signals
- `CWRU_data/` – Dataset handling

**Colab Link:** [Open in Colab](https://colab.research.google.com/drive/1yeFjgOkJdQk3oSGtib2WNZQPmn79ZUF9?usp=sharing)

Made by Alireza Kokabi Dezfuli  
