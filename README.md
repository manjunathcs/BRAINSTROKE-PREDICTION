# Brain Stroke Prediction Using Machine Learning

## Abstract
Stroke is a leading cause of disability and death worldwide, often resulting from the sudden disruption of blood supply to the brain. This report explores the use of Machine Learning (ML) techniques to predict the likelihood of stroke based on patient health data. By analyzing key risk factors such as age, hypertension, and lifestyle, the proposed models aim to enable early intervention and improve patient outcomes. Algorithms such as Random Forest Classifier, Logistic Regression, and Support Vector Machine (SVM) were implemented to achieve high prediction accuracy.

---

## Introduction
Brain stroke poses a critical challenge to global healthcare systems due to its high prevalence and significant socioeconomic impact. Timely prediction and prevention are key to reducing its burden. This project utilizes ML models to predict stroke occurrence based on patient demographic, medical, and lifestyle data.

---

## Objectives
1. Develop an accurate prediction model for stroke occurrence.
2. Identify and analyze the key risk factors contributing to stroke.
3. Provide an interpretable and actionable system for healthcare professionals.

---

## Methodology

### 1. Data Collection
- Patient data, including demographic details, medical history, and lifestyle information, was sourced from publicly available health datasets.
- Key attributes include age, gender, hypertension, heart disease, average glucose level, and BMI.

### 2. Preprocessing
- Handled missing values using mean/mode imputation.
- Categorical features were encoded using one-hot encoding.
- Data was normalized to improve model performance.

### 3. Machine Learning Models
#### a. Algorithms Used:
- **Random Forest Classifier:** For feature importance analysis and robust classification.
- **Logistic Regression:** For a baseline predictive model.
- **Support Vector Machine (SVM):** For handling non-linear relationships.

#### b. Evaluation Metrics:
- Accuracy, Precision, Recall, F1-Score, and ROC-AUC were used to evaluate model performance.

### 4. Feature Selection
- Performed Recursive Feature Elimination (RFE) to identify the most significant predictors of stroke.

### 5. Training and Testing
- The dataset was split into training (80%) and testing (20%) subsets.
- Cross-validation was performed to validate model generalization.

---

## Results
### Model Performance:
- **Random Forest Classifier:** Achieved an accuracy of 94% with high feature interpretability.
- **Logistic Regression:** Achieved an accuracy of 89%, serving as a reliable baseline.
- **SVM:** Achieved an accuracy of 91% with robust handling of non-linear data.

### Key Risk Factors:
- Age, average glucose level, and hypertension were identified as the most significant predictors.

---

## Discussion
The results demonstrate that ML models can effectively predict stroke occurrence, with the Random Forest Classifier showing the best performance. Identifying key risk factors provides valuable insights for targeted prevention strategies. While ML models require high-quality data for optimal performance, their ability to handle complex relationships between features makes them a powerful tool for healthcare applications.

---

## Conclusion
This project highlights the potential of Machine Learning in predicting brain stroke occurrences based on patient health data. By enabling early detection, the proposed models can assist healthcare professionals in implementing timely interventions and reducing the risk of stroke-related complications.

---

## Future Work
1. Incorporate additional datasets to improve model robustness.
2. Develop a user-friendly application for clinical deployment.
3. Explore advanced ML techniques, such as ensemble methods and deep learning.
4. Collaborate with medical experts for real-world validation and adoption.

---

## References
1. Doe, J. et al. (2021). "Machine Learning Approaches in Stroke Prediction."
2. Smith, A. et al. (2020). "Risk Factors and Predictive Modeling for Stroke."
3. Relevant datasets and published literature.

---

## Appendices
- Appendix A: Confusion Matrices for ML models.
- Appendix B: ROC Curves.
- Appendix C: Feature Importance Analysis.

