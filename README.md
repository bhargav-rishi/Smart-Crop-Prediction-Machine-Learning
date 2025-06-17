# Smart Crop Prediction for Agricultural Transformation 

This project presents a machine learning-based approach to predicting the most suitable crop for a given set of soil and environmental conditions. The work was part of the Advanced Machine Learning curriculum at the University of South Florida – Muma College of Business.

## Dataset
Sourced from [Kaggle – Soil Moisture, Temp, and Nutritions](https://www.kaggle.com/datasets/r3trovision/soil-moisture-temp-and-nutritions)

- Features: `pH`, `Soil EC`, `Phosphorus`, `Potassium`, `Urea`, `T.S.P`, `M.O.P`, `Moisture`, `Temperature`
- Target: `Plant Type` (multi-class)

## ML Models Evaluated
- Gaussian Naive Bayes (Baseline) – Accuracy: **88.49%**
- Logistic Regression – Accuracy: **88.00%**
- Support Vector Machine – Accuracy: **88.69%**
- Decision Tree – Accuracy: **91.07%**
- Random Forest – Accuracy: **91.03%**
- Neural Network – Accuracy: **80.61%**
- KNN – Accuracy: **72.5%** (excluded from final shortlist)

## Preferred Models
- **Decision Tree**
- **Random Forest**
- **SVM (Secondary option)**

## Evaluation Metrics
Each model was tested using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC & AUC curves
- Confusion matrices

## Implementation Plan
- Web/Mobile app for farmer input (soil pH, moisture, etc.)
- Crop recommendations + resource advice (fertilizer, temperature needs)
- Future integration with IoT sensors for real-time data
- Model retraining with feedback and yield data

## Files
- `ML_Project.ipynb`: Full modeling notebook with metrics
- `report/Project_Report.docx`: Final paper report
- `data/`: Dataset csvs
