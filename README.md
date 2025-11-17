# Portfolio

## Summary

AI student with a foundational background in Data Science and ML/DL. I enjoy exploring and learning through hands-on projects, and I continuously work on improving my programming, data processing, and model-building skills to prepare for more complex projects in the future.

## Technical Skills

| Category | Skills |
| :--- | :--- |
| **Programming** | Python, C++, SQL |
| **Data Science** | Pandas, NumPy, Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn, XGBoost |
| **Deep Learning** | PyTorch, OpenCV, MediaPipe |
| **Tools** | Git, GitHub, Jupyter Notebook, VS Code, PyCharm |

## Education

Artificial Intelligence | FPT UNIVERSITY

*2023 – Present*

## Projects

### 1. Driver Drowsiness Detection System
[Project Report (PDF)](reports/Driver_Drowsiness_Detection_System.pdf) | [Source Code](https://github.com/Pham-Hoang-Phuc/Drowsiness-detection/tree/main)

Developed a real-time Computer Vision system to detect driver fatigue using webcam video, designed with a modular and high-speed processing pipeline powered by MediaPipe.

**Key Features**

- **Eye State Classification (Open/Closed):** Built a custom lightweight CNN achieving 98.70% accuracy, optimized for low-latency real-time deployment.
- **Yawn Detection (Hybrid MAR-CNN):** Implemented a dual-verification method combining geometric Mouth Aspect Ratio (MAR) + CNN. → Reduced false positives compared to MAR-only approaches.
- **Real-time System Architecture:** Facial landmark detection via MediaPipe, Eye & mouth ROI extraction module, Hybrid classification engine, Alert trigger subsystem.

**My Contributions**

- Built a complete pipeline including data collection, preprocessing, model training, and evaluation.
- Implemented facial landmark extraction and real-time processing with OpenCV and MediaPipe.
- Developed custom CNN models for eye state classification and yawn detection.

<div align="center">
  <img src="pics/pic.png" alt="Pipeline Overview" width="70%"/>
</div>

### 2. Heart Disease Prediction Using Machine Learning
[Project Report (PDF)](reports/Heart_Disease_Prediction_Using_Machine.pdf) | [Source Code](https://github.com/Pham-Hoang-Phuc/Heart_Disease/tree/main)

Applied supervised machine learning models on a clinical dataset (918 samples, 12 features) to predict the presence of heart disease, focusing on minimizing False Negatives (FNs).

**Key Features**

- **Comparative Model Evaluation:** Trained and evaluated Logistic Regression, XGBoost, and Random Forest classifiers. Random Forest achieved the best results with 88.0% Accuracy and a high 89.0% Recall (crucial for medical diagnosis).
- **Data Analysis & Feature Engineering:** Performed comprehensive Exploratory Data Analysis (EDA) to understand feature distributions and correlations. Identified Oldpeak, MaxHR, and Age as the strongest predictors for the target variable.
- **Statistical Insight Extraction:** Generated heatmaps, pairplots, and count plots to visually confirm the correlation structure. Established that a lower Max Heart Rate (MaxHR) and higher Oldpeak score strongly correlate with increased disease risk.

**My Contributions**

- Led the Exploratory Data Analysis (EDA) and Data Visualization stages.

## Contact

- **Email:** pham.phuc.david@gmail.com
- **GitHub:** https://github.com/Pham-Hoang-Phuc
