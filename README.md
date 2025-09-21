# College Placement Prediction using ANN

## Project Overview
This project predicts whether a student will be **Placed** or **Not Placed** using an **Artificial Neural Network (ANN)**. The model is trained on student data from `CollegePlacement.csv`, including academic scores, test results, and other relevant features.

---

## Key Steps

1. **Data Preprocessing**  
   - Handle missing values and categorical encoding  
   - Feature scaling using `StandardScaler`  
   - Oversampling minority class with `SMOTE`  

2. **Model Building**  
   - ANN with input, hidden, and output layers  
   - ReLU activation for hidden layers, Sigmoid for output  
   - Binary classification using `binary_crossentropy` loss  

3. **Model Training**  
   - Trained with `X_train` and `y_train`  
   - Validated on `X_test` and `y_test`  
   - Achieved **high accuracy** on both training and validation sets  

4. **Evaluation**    
   - Model generalizes well to unseen data  

---

## Requirements
- Python 3.x  
- `pandas`, `numpy`, `scikit-learn`, `imblearn`, `tensorflow`, `nltk`  

---

## Conclusion
The ANN model effectively predicts student placement, achieving high accuracy and low loss. It can be used to identify students likely to be placed based on their academic and personal features.
