## **Predicting Type II Diabetes in Women using Machine Learning**  

### **Overview**  
This project applies machine learning techniques to predict the likelihood of Type II Diabetes in women using the **Pima Indians Diabetes Dataset**. The study explores key health indicators and risk factors to assist in early diagnosis and preventive measures.  

### **Dataset**  
- The dataset is publicly available on [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).  
- It consists of **768** records of female Pima Indians, with **8 features** that help predict diabetes.  
- The target variable (`Outcome`): **0** (non-diabetic) and **1** (diabetic).  

### **Features Used in Prediction**  
- **Pregnancies**: Number of times a woman has been pregnant.  
- **Glucose Level**: Measured via an oral glucose tolerance test.  
- **Blood Pressure**: Diastolic blood pressure (mm Hg).  
- **Skin Thickness**: Triceps skinfold thickness (mm).  
- **Insulin**: 2-hour serum insulin (mu U/ml).  
- **BMI**: Body Mass Index.  
- **Diabetes Pedigree Function**: Family history of diabetes.  
- **Age**: Patient’s age in years.  

### **Preprocessing Steps**  
- **Handling Missing Values**: Missing values were replaced using the **mean imputation method**.  
- **Feature Scaling**: Standardized using `StandardScaler()` from Scikit-learn.  
- **Data Balancing**: Used **under-sampling** to balance the dataset.  

### **Machine Learning Models Used**  
Three supervised learning models were trained and evaluated:  
1. **Decision Tree (ID3 Algorithm)**  
2. **Random Forest**  
3. **Naive Bayes**  

### **Results**  
After training and testing with the balanced dataset, the accuracy scores were:  
- **Decision Tree**: **67%**  
- **Random Forest**: **75%**  
- **Naive Bayes**: **77%** (Best performing model)  

### **Conclusion**  
- The **Naive Bayes classifier** provided the highest accuracy, making it the most effective model for this dataset.  
- The study highlights the importance of **early diabetes prediction** using health indicators.  
- Future improvements include expanding the dataset, incorporating **male records**, and adding lifestyle factors like **diet and exercise**.  

### **Installation & Usage**  
#### **Requirements**  
Ensure you have the following installed:  
- Python (>=3.7)  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
