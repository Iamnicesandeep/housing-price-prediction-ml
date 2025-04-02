
## 🏡 Housing Price Prediction (Advanced Regression Techniques)

This project applies advanced machine learning algorithms to predict housing prices using the **Ames, Iowa dataset**, a widely-used benchmark in real estate price modeling. It was developed as part of our **MSBA Machine Learning Final Project** to explore how data-driven approaches can improve accuracy, transparency, and efficiency in the real estate market.

---

### 📌 Problem Statement

In a volatile real estate market, traditional valuation methods are time-consuming and prone to human error. This project aims to build a predictive model that provides **accurate and automated home price predictions**, reducing manual effort while empowering both buyers and sellers to make informed decisions.

---

### 🧠 Project Highlights

- Developed multiple regression models including **Linear Regression, Ridge/Lasso, Random Forest, and XGBoost**
- Created new engineered features such as total square footage and time since last remodel
- Achieved a significant reduction in RMSE from **0.35 (Linear Regression)** to **~0.14 (XGBoost)** through tuning and ensembling
- Final model demonstrates strong generalization via **cross-validation**

---

### 🛠️ Tools & Technologies

- **Languages**: Python  
- **Libraries**: Scikit-learn, XGBoost, Pandas, NumPy, Seaborn, Matplotlib  
- **Platform**: Kaggle

---

### 🔍 Methodology

1. **Data Cleaning**
   - Imputed missing values (e.g., `LotFrontage`, `GarageYrBlt`)
   - Encoded categorical variables using Label Encoding

2. **Feature Engineering**
   - Created interaction features (e.g., Mass × Total SF)
   - Derived new time-based and spatial features

3. **Modeling & Tuning**
   - Trained and compared multiple ML models
   - Performed GridSearchCV to fine-tune hyperparameters

4. **Evaluation**
   - Metric: Root Mean Squared Error (RMSE)
   - Validation via cross-validation and leaderboard submission

---

### 📈 Results

| Model               | RMSE      |
|--------------------|-----------|
| Linear Regression   | 0.350     |
| Random Forest       | ~0.180    |
| XGBoost (final)     | **~0.140** |

> ✅ Final XGBoost model showed strong predictive accuracy and robustness on the validation set.

---

### 🧩 Use Cases

- **For Sellers**: Improve pricing strategy using data-driven insights
- **For Buyers**: Avoid overpaying with transparent pricing predictions
- **For Firms**: Automate valuation, saving time and enhancing competitiveness

---

### 📁 Repository Structure

```
housing-price-prediction-ml/
├── ML_Final.ipynb          # Jupyter notebook with code
├── Analysis.pdf            # Final project report
├── Sandeep_Poster.pptx     # Presentation poster
├── visuals/                # Key charts and visuals
└── README.md               # Project documentation
```

---

### 📬 Let’s Connect

📧 Karumudi@wisc.edu  
📞 +1 (608) 707-2216  
🔗 [LinkedIn](https://www.linkedin.com/in/sandeep-karumudi) *(update if needed)*  
💻 [Portfolio](https://your-portfolio-link.com) *(optional)*
