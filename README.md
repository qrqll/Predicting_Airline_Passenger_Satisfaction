# Diabetes Prediction using Naive Bayes

## Overview
This project analyzes the diabetes dataset of Native Americans from Pima to predict diabetes outcomes. It highlights the importance of various medical indicators such as glucose levels, Body Mass Index (BMI), and age in the prediction process.

## Key Findings
- Data balancing played a significant role in achieving high accuracy.
- Techniques such as TF-IDF were used to extract key features, helping identify important and distinctive words in the texts.
- The model's good performance indicates the effectiveness of preprocessing steps (such as removing stop words and stemming) in improving the model's accuracy.

## Methodology
1. **Data Collection**: Gathered the diabetes dataset from the Pima Indian community.
2. **Data Preprocessing**:
   - Data balancing to ensure an even distribution of classes.
   - Removal of stop words and application of stemming.
3. **Feature Extraction**: Utilized TF-IDF to extract significant features.
4. **Model Building**: Built two models using the Naive Bayes classification algorithm.
5. **Evaluation**: 
   - The second model achieved an accuracy of 78.65%.
   - The first model achieved an accuracy of 77.92%.

## Conclusion
The results illustrate the effectiveness of the Naive Bayes algorithm in predicting diabetes based on medical data, contributing to improved early diagnosis and better treatment decisions.

## Installation
To run this project, make sure you have the following libraries installed:
```bash
pip install pandas scikit-learn numpy matplotlib seaborn
