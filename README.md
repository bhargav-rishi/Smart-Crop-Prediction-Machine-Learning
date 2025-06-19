# Smart Crop Prediction for Agricultural Transformation – Machine Learning Project

![Built With](https://img.shields.io/badge/Built%20With-Python%20%7C%20Scikit--Learn%20%7C%20Pandas%20%7C%20NumPy%20%7C%20Machine%20Learning-blue)
![Language](https://img.shields.io/badge/Language-Python-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---
Choosing the wrong crop for a specific soil or weather condition can seriously affect yield, cost, and even long-term soil health. On average, **up to 30% of potential agricultural output is lost** each year due to poor crop selection and environmental mismatch ([FAO, 2021](https://www.fao.org/news/story/en/item/1395127/icode/)).

This project focuses on predicting the **most suitable crop** for a given set of soil and environmental conditions using various **machine learning algorithms**. It was completed as part of the Machine Learning coursework at the **University of South Florida – Muma College of Business**.

---

## Dataset

Sourced from [Kaggle: Soil Moisture, Temp & Nutrients](https://www.kaggle.com/datasets/r3trovision/soil-moisture-temp-and-nutritions)

The dataset includes information like:
- Soil pH
- Electrical Conductivity (Soil EC)
- Nutrient levels: Phosphorus, Potassium, Urea, T.S.P, M.O.P
- Moisture content
- Temperature

The goal is to predict the ideal plant type for those conditions.

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
- **Precision** and **Recall** – to understand error types  
- **F1 Score** – to balance precision vs. recall  
- **Confusion Matrix** – to visualize misclassifications  
- **ROC-AUC** – for performance on each class (For applicable models)

---

## What Could This Look Like in Real Life?

This could power:
- A mobile app where farmers input their soil info and get crop suggestions  
- A dashboard for agricultural consultants to support local farmers  
- Integration with IoT sensors for real-time updates  
- Ongoing retraining as more planting/yield data becomes available

By helping a farmer choose the right crop, this tool could:
- Avoid input waste (fertilizer, seed, water)  
- Increase **profit margins by 15–30%** depending on region ([FAO, 2021](https://www.fao.org/news/story/en/item/1395127/icode/))  
- Improve long-term soil health and sustainability

---

## Project Structure
<pre>
Smart-Crop-Prediction-Machine-Learning/
├── ML_Project.ipynb
├── report/
│   └── Project_Report.docx
├── data/
│   ├── Crop_Recommendation_TRAIN.csv
│   └── Crop_Recommendation_Test.csv
  </pre>


