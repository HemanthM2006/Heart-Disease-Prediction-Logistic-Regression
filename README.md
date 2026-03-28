# ❤️ Heart Disease Prediction

### Logistic Regression from Scratch

A Machine Learning project that predicts whether a person is likely to have **heart disease (0 or 1)** using **Logistic Regression implemented from scratch in Python**.

This project focuses on understanding the **mathematical foundations of classification**, including sigmoid function, log loss, and gradient descent.

---

# 🚀 Project Overview

The goal of this project is to model the relationship between:

(Age, Sex, Chest Pain, Blood Pressure, Cholesterol, Max Heart Rate, Exercise Angina) → Heart Disease (0 or 1)

Using a **Logistic Regression model**, the algorithm learns to predict the **probability of heart disease**.

The implementation **does not use machine learning libraries** like scikit-learn.  
Instead, everything is built manually using **NumPy and Gradient Descent**.

---

# 🧠 Machine Learning Concepts Used

This project demonstrates important ML concepts:

• Logistic Regression (Binary Classification)  
• Sigmoid Function  
• Log Loss (Binary Cross Entropy)  
• Gradient Descent Optimization  
• Feature Scaling (Standardization)  
• Train/Test Split  
• Early Stopping (Convergence using tolerance)  
• Model Evaluation (Accuracy, Precision, Recall, F1 Score)  
• Confusion Matrix  

---

# 📊 Dataset

Sample dataset:

| Age | Sex | ChestPain | RestBP | Cholesterol | MaxHR | ExerciseAngina | Target |
|-----|-----|----------|--------|------------|------|----------------|--------|
| 63  | 1   | 3        | 145    | 233        | 150  | 0              | 1      |
| 37  | 1   | 2        | 130    | 250        | 187  | 0              | 1      |
| 57  | 0   | 0        | 120    | 354        | 163  | 1              | 0      |
| ... | ... | ...      | ...    | ...        | ...  | ...            | ...    |

---

# 📈 Logistic Regression Model

The prediction function:

z = w₁x₁ + w₂x₂ + ... + wₙxₙ + b  
ŷ = 1 / (1 + e^(-z))

Where:

| Symbol | Meaning |
|--------|--------|
| x      | Input features |
| z      | Linear combination |
| ŷ      | Predicted probability |
| w      | Weights |
| b      | Bias |

Final classification:

ŷ ≥ 0.5 → 1 (Disease)  
ŷ < 0.5 → 0 (No Disease)

---

# ⚙️ Technologies Used

• Python 🐍  
• NumPy  
• Pandas  
• Matplotlib  

---

# 📉 Training & Evaluation

The model includes:

• Data shuffling  
• Train/Test split (80/20)  
• Feature scaling (based on training data)  
• Gradient descent with early stopping  

Evaluation metrics:

Accuracy  ≈ 75%  
Precision ≈ 0.75  
Recall    ≈ 1.00  
F1 Score  ≈ 0.86  

---

# 📊 Confusion Matrix

          Pred 0    Pred 1  
Actual 0     0         1  
Actual 1     0         3  

---

# 📊 Visualizations

The project includes:

• Cost vs Iterations (training convergence)  
• Feature Importance (model weights)  
• Prediction probabilities vs actual values  

---

# 🔮 Example Prediction

Example input:

Age: 50  
Sex: 1  
ChestPain: 2  
RestBP: 130  
Cholesterol: 250  
MaxHR: 160  
ExerciseAngina: 0  

Predicted Output:

Probability: 0.82  
Prediction: 1 (Heart Disease Likely)

---

# 📂 Project Structure

heart-disease-logistic-regression  
│  
├── main.py  
├── heart.csv  
├── README.md  

---

# 🎯 Key Learning Outcomes

Through this project, we understand:

• Difference between regression and classification  
• Why sigmoid is used  
• Importance of log loss over MSE  
• How gradient descent works in classification  
• How to evaluate classification models properly  
• Trade-off between precision and recall  

---

# 📌 Future Improvements

Possible extensions:

• Use a larger real-world dataset  
• Tune decision threshold (0.5 → optimal value)  
• Add ROC curve & Precision-Recall curve  
• Compare with scikit-learn implementation  
• Build a web app (Streamlit)  

---

# 👨‍💻 Author

**Hemanth M**  

Computer Science Student | Machine Learning Enthusiast  
