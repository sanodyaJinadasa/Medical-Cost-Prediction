# 🏥 Insurance Cost Prediction using Linear Regression

## 📌 Overview
This project predicts individual medical insurance costs using a Linear Regression model. The dataset includes personal attributes such as age, BMI, smoking status, and region, which are used to estimate healthcare expenses.

---

## 📂 Dataset Information

**Dataset Name:** Medical Cost Personal Dataset  
**Source:** Kaggle  

### 🔑 Features

- **age**: Age of the primary beneficiary  
- **sex**: Gender of the insurance holder (male/female)  
- **bmi**: Body Mass Index (kg/m²)  
- **children**: Number of dependents covered  
- **smoker**: Smoking status (yes/no)  
- **region**: Residential area (northeast, southeast, southwest, northwest)  
- **charges**: Medical insurance cost (target variable)  

---

## 🎯 Objective

- Analyze the impact of personal attributes on medical costs  
- Build a Linear Regression model to predict insurance charges  
- Evaluate model performance using metrics  

---

## 🧪 Methodology

### 1. Data Preprocessing
- Checked for missing values  
- Encoded categorical variables  
- Feature scaling (if needed)  

### 2. Exploratory Data Analysis (EDA)
- Visualized data distributions  
- Analyzed correlations  
- Identified important features  

### 3. Model Building
- Applied Linear Regression  
- Split data into training and testing sets  
- Trained the model  

### 4. Evaluation Metrics
- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  

---

## 📊 Key Insights

- Smoking significantly increases medical costs  
- Higher BMI leads to higher charges  
- Age is positively correlated with expenses  
- Region and gender have smaller effects  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/insurance-cost-prediction.git
   ```

2. Navigate to the project folder  
   ```bash
   cd insurance-cost-prediction
   ```

3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. Run the project  
   ```bash
   jupyter notebook
   ```

---

## 📈 Future Improvements

- Use advanced models (Random Forest, XGBoost)  
- Perform hyperparameter tuning  
- Deploy using Flask or Streamlit  

---

## 🙏 Acknowledgements

- Dataset inspired by *Machine Learning with R* by Brett Lantz  
- Data sourced from Kaggle  

---

## 📬 Contact

Your Name  
your.email@example.com  
