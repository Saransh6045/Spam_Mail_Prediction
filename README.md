# Spam Mail Prediction

## Problem Statement
The objective of this project is to build a machine learning model that can predict whether a given email message is **Spam** or **Ham (Not Spam)** based on its content. This system helps in automatically identifying and filtering unwanted or irrelevant emails.

---

## About Dataset
- **Total Samples**: 5,572  
- **Total Features**: 1 (Mail Message/Text)  
- **Target Classes**:
  - **Spam** – Unwanted or promotional emails  
  - **Ham** – Legitimate emails  

The dataset contains labelled email messages, making it suitable for supervised machine learning techniques.

---

## Technologies Used
- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Google Colab**

---

## Model Used
### Logistic Regression Model
Logistic Regression is chosen because the problem involves **binary classification** (Spam or Ham). It is an efficient and widely used algorithm for text classification tasks and performs well when combined with appropriate feature extraction techniques.

---

## Methodology
The project follows a systematic machine learning workflow:

1. **Data Collection**  
   - Load the dataset and understand its structure.

2. **Data Preprocessing**  
   - Clean the data and apply **label encoding** to convert categorical target values into numerical form.

3. **Train-Test Split**  
   - Divide the dataset into training and testing sets to evaluate model performance.

4. **Feature Extraction**  
   - Convert textual email data into numerical features suitable for model training.

5. **Model Training**  
   - Train the Logistic Regression model using the training dataset.

6. **Model Evaluation**  
   - Evaluate the trained model using test data to measure accuracy.

7. **Single-input Predictive System**  
   - Develop a system that can predict whether a newly entered email message is spam or ham.

---

## Results
- **Training Accuracy**: 96.72%
- **Testing Accuracy**: 97.04%

The results indicate that the model performs well and is capable of accurately classifying unseen email messages.

---

## Conclusion
This project demonstrates an effective approach to spam mail detection using machine learning. With high accuracy on both training and testing data, the Logistic Regression model proves to be a reliable choice for binary text classification tasks.


