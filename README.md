# 🏡 House Price Prediction using Machine Learning
This machine learning project predicts house prices based on numerical features like bedrooms, bathrooms, parking, and house area (sqft). The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and final price prediction.

---

## 📁 Project Structure
```
House_Price_Prediction/
│── dataset/
│   └── ncr_house_price.csv
│── House_Price_Prediction.ipynb
│── README.md
```

---

## 📊 Dataset Description
The dataset contains:
- bedrooms: number of bedrooms  
- bathrooms: number of bathrooms  
- parking: parking capacity  
- area: house area (sqft)  
- price: house price (target variable)

---

## 🧹 Data Preprocessing
- Handled missing values  
- Removed duplicates  
- Outlier detection & removal  
- Data visualization  
- Correlation matrix  
- Feature analysis  

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots  
- Scatter plots (feature vs price)  
- Heatmap correlations  
- Outlier visualization  
- Bedroom/bathroom/area vs price insights  

---

## 🤖 Model Training
The model used:
- **Linear Regression (Scikit-Learn)**  

Training pipeline:
```
1. Load dataset  
2. Clean → Handle nulls → Remove duplicates  
3. Feature selection  
4. Train-test split  
5. Train Linear Regression model  
6. Evaluate  
```

---

## 📈 Model Evaluation
Example metrics (replace with actual notebook results):

```
R² Score: 0.98
```

---

## 🧠 Prediction Example
```python
model.predict([[bedrooms, bathrooms, parking, area]])
```

Example:
```python
model.predict([[3, 2, 1, 1200]])
```

---

## ▶️ Run the Project

### 1️⃣ Clone
```bash
git clone https://github.com/your-username/house-price-prediction.git
```

### 2️⃣ Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3️⃣ Open Notebook
```bash
jupyter notebook House_Price_Prediction.ipynb
```

### 4️⃣ Run All Cells

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---


## 📜 License
Open-source for educational use.

---

## 🙌 Acknowledgements
Dataset processed for academic ML learning.
