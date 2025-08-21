# 🚢 Titanic Survival Prediction  

## 📌 Project Overview  
The Titanic dataset is one of the most popular datasets for beginners in Machine Learning.  
This project predicts passenger survival based on socio-economic and demographic features such as age, gender, class, and fare.  
The goal is to build machine learning models that classify whether a passenger survived or not.  

---

## 📂 Dataset  
- **Source:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)  
- **Features Used:**  
  - Passenger Class (Pclass)  
  - Gender (Sex)  
  - Age  
  - Siblings/Spouses aboard (SibSp)  
  - Parents/Children aboard (Parch)  
  - Ticket Fare (Fare)  
  - Port of Embarkation (Embarked)  

---

## ⚙️ Technologies & Tools  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Models Used:** Logistic Regression, Decision Tree, Random Forest, KNN, SVM  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 🛠️ Methodology  
1. **Data Preprocessing**  
   - Handling missing values (Age, Embarked).  
   - Encoding categorical features (Sex, Embarked).  
   - Feature scaling where required.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized survival distribution by age, gender, and class.  
   - Identified correlations among features.  

3. **Model Building**  
   - Trained multiple classifiers: Logistic Regression, Random Forest, SVM, KNN.  
   - Performed hyperparameter tuning for better accuracy.  

4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-Score.  
   - Confusion Matrix for classification performance.  

---

## 📊 Results  
- **Best Model:** Random Forest Classifier  
- **Accuracy Achieved:** ~82% (on test set)  
- Strong performance in predicting survival with balanced precision and recall.  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/punam123-bit/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
