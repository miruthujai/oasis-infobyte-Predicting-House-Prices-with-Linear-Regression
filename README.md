# 🏠 Predicting House Prices with Linear Regression

## 🏢 Internship Details
- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics
- **Project Title:** Predicting House Prices with Linear Regression

---

## 📌 What is This Project About?

In this project, I built a Linear Regression model to predict
house prices based on various features like area, bathrooms,
stories, air conditioning and more.
The goal was to find the best features that influence house
prices and build an accurate prediction model.

---

## 📁 About the Dataset

| Property | Details |
|----------|---------|
| Source | Kaggle |
| Total Rows | 545 |
| Total Columns | 13 |
| Missing Values | None (Zero) |
| File Format | CSV |

### Column Names:
1. **price** - Price of the house (Target Variable)
2. **area** - Total area in square feet
3. **bedrooms** - Number of bedrooms
4. **bathrooms** - Number of bathrooms
5. **stories** - Number of stories
6. **mainroad** - Connected to main road (yes/no)
7. **guestroom** - Has guest room (yes/no)
8. **basement** - Has basement (yes/no)
9. **hotwaterheating** - Has hot water heating (yes/no)
10. **airconditioning** - Has air conditioning (yes/no)
11. **parking** - Number of parking spaces
12. **prefarea** - Located in preferred area (yes/no)
13. **furnishingstatus** - Furnished / Semi / Unfurnished

---

## 🛠️ Tools and Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Pandas | Data Loading and Cleaning |
| NumPy | Numerical Calculations |
| Matplotlib | Creating Charts |
| Seaborn | Beautiful Visualizations |
| Scikit-learn | ML Model & Feature Selection |
| Statsmodels | OLS Regression & VIF |
| Google Colab | Online Coding Platform |

---

## 📊 Steps I Performed

### Step 1 - Data Loading
- Loaded Housing.csv using Pandas
- Checked shape, columns and data types

### Step 2 - Data Cleaning
- Checked missing values → Found ZERO missing values
- Removed outliers from Price using IQR method
- Removed outliers from Area using IQR method

### Step 3 - EDA & Visualization
- Pairplot to check feature relationships
- Boxplots for all categorical vs price
- Furnishing Status vs Price with AC comparison

### Step 4 - Data Preparation
- Binary mapping for yes/no columns
- Dummy variables for furnishing status
- Train-Test Split (70% train / 30% test)
- MinMax Scaling for numerical features

### Step 5 - Model Building
- Used RFE to select top 6 features
- Built OLS Regression model using Statsmodels
- Checked p-values for significance
- Checked VIF for multicollinearity

### Step 6 - Model Evaluation
- Plotted residuals distribution
- Plotted Actual vs Predicted prices
- Calculated R-squared & MSE scores

### Step 7 - Business Recommendations
- Provided actionable insights based on model

---

## 📈 Key Findings

| # | Finding |
|---|---------|
| 1 | **Area** is the strongest predictor of house price |
| 2 | **Bathrooms & Stories** significantly impact price |
| 3 | **Air Conditioning** adds considerable value |
| 4 | **Preferred Area** location boosts price |
| 5 | **Model R² ≈ 65-70%** variance explained |
| 6 | **VIF < 5** for all features - No multicollinearity |

---

## 💡 Business Recommendations

1. **Focus on Area** - Larger area = higher price always
2. **Add Bathrooms** - More bathrooms increase value significantly
3. **Install AC** - Air conditioning adds premium value
4. **Choose Preferred Area** - Location boosts price considerably
5. **Multi-story Homes** - More stories = more market value

---

## 📂 Files in This Repository

| File Name | Description |
|-----------|-------------|
| `Predicting_House_Prices.ipynb` | Main Jupyter Notebook |
| `Housing.csv` | Original dataset |
| `chart1_pairplot.png` | Pairplot - Feature Relationships |
| `chart2_categorical_boxplots.png` | Boxplots - Categorical vs Price |
| `chart3_furnishing_ac.png` | Furnishing Status vs Price |
| `chart4_correlation_heatmap.png` | Correlation Heatmap |
| `chart5_residuals.png` | Error Terms Distribution |
| `chart6_actual_vs_predicted.png` | Actual vs Predicted Prices |

---

## 🚀 How to Run This Project

### Option 1 - Google Colab (Recommended)
1. Download `Predicting_House_Prices.ipynb`
2. Go to colab.research.google.com
3. Click File → Upload notebook
4. Upload the .ipynb file
5. Upload Housing.csv to Colab files
6. Click Runtime → Run all

### Option 2 - Jupyter Notebook (Local)
1. Install Python on your computer
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
3. Open the .ipynb file
4. Run all cells one by one

---

## 👨‍💻 About Me
- Name: Miruthu Jai
- Internship: Oasis Infobyte Data Analytics
- LinkedIn: https://www.linkedin.com/in/miruthujais/
- GitHub: https://github.com/miruthujai

---
🏷️ Tags
`#oasisinfobyte` `#oasisinfobytefamily` `#internship`
`#python` `#datacleaning` `#datanalytics` `#pandas`
`#matplotlib` `#seaborn` `#datascience` `#NYC` `#airbnb`
