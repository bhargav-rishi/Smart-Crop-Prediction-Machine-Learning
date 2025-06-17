# Smart Crop Prediction for Agricultural Transformation– Machine Learning Project

![Built With](https://img.shields.io/badge/Built%20With-Python%20%7C%20Scikit--Learn%20%7C%20Machine%20Learning-blue)
![Language](https://img.shields.io/badge/Language-Python-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

This project focuses on predicting the **most suitable crop** for a given set of soil and environmental conditions using various **machine learning algorithms**. It was completed as part of the Machine Learning coursework at the **University of South Florida – Muma College of Business**.

---

## Dataset

Sourced from [Kaggle: Soil Moisture, Temp & Nutrients](https://www.kaggle.com/datasets/r3trovision/soil-moisture-temp-and-nutritions)

- **Features**:  
  `pH`, `Soil EC`, `Phosphorus`, `Potassium`, `Urea`, `T.S.P`, `M.O.P`, `Moisture`, `Temperature`
- **Target**:  
  `Plant Type` – categorical crop label (multi-class)

---

## Technologies Used

- Python
- Scikit-learn
- Jupyter Notebook

---

## ML Models Implemented

| Model               | Accuracy (%) |
|---------------------|--------------|
| Decision Tree       | 91.07        |
| Random Forest       | 91.03        |
| Support Vector Machine (SVM) | 88.69        |
| Logistic Regression | 88.00        |
| Gaussian Naive Bayes| 88.49        |
| Neural Network (MLP)| 80.61        |
| K-Nearest Neighbors (excluded from final shortlist) | 72.50        |

---

## Preferred Models
- **Decision Tree**
- **Random Forest**
- **SVM (Secondary option)**

---

## Evaluation Metrics

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC & AUC (for applicable models)

---

## Implementation Plan
- Web/Mobile app for farmer input (soil pH, moisture, etc.)
- Crop recommendations + resource advice (fertilizer, temperature needs)
- Future integration with IoT sensors for real-time data
- Model retraining with feedback and yield data

---

## Project Structure

Smart-Crop-Prediction-Machine-Learning/
├── ML_Project.ipynb
├── report/
│   └── Project_Report.docx
├── data/
│   ├── Crop_Recommendation_TRAIN.csv
│   └── Crop_Recommendation_Test.csv


