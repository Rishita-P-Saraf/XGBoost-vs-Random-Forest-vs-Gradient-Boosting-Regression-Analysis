# 🧠 XGBoost vs Random Forest vs Gradient Boosting – Regression Analysis

This repository provides a comparison of three powerful ensemble machine learning algorithms using the **California Housing dataset** for regression:

- 🔸 XGBoost Regressor  
- 🔸 Random Forest Regressor  
- 🔸 Gradient Boosting Regressor  

The goal is to predict housing prices and evaluate performance using **Mean Squared Error (MSE)**.

---

## 📁 Files Included

| File Name                      | Description                                               |
|-------------------------------|-----------------------------------------------------------|
| `XgBoost_Algorithm.ipynb` | Main implementation for loading data, training models, and evaluating results |
| `README.md`                   | Project documentation                         |

---

## 📊 Dataset

**California Housing Dataset** from Scikit-learn  
➡️ Contains features such as average income, house age, population, etc.  
➡️ Target: Median house value in California districts.

---

## 🛠 Requirements

Install the dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
---
## 🚀 How to Run
1. Clone this repository:
```
git clone https://github.com/yourusername/xgboost-housing-analysis.git
cd xgboost-housing-analysis
```
2. Run the script:
```
python XG_Boost_Implementation.py
```
---
## 📌 Key Steps
1. Data Loading
Load and split California Housing data using train_test_split.

2. Model Training
Train three models: XGBRegressor, RandomForestRegressor, and GradientBoostingRegressor.

3. Prediction & Evaluation
Predict on the test set and evaluate using mean_squared_error.

4. (Optional) Grid Search
Code for GridSearchCV is included but commented out.

---

## ✅ Results

| Model                   | Mean Squared Error |
|------------------------|--------------------|
| 🧠 XGBoost Regressor    | 0.2226             |
| 🌲 Random Forest        | 0.2554             |
| 📈 Gradient Boosting    | 0.2940             |

✔️ **XGBoost outperforms the others in terms of MSE.**

---

## 🚧 Future Improvements

- Enable and optimize using `GridSearchCV`
- Add more metrics: `R² score`, `MAE`
- Add feature importance visualizations
- Integrate a simple web UI or API for predictions

---

## 📜 License

**MIT License**  
Feel free to use, modify, and distribute with attribution.

---

## 🙏 Acknowledgments

- [Scikit-learn](https://scikit-learn.org/)
- [XGBoost](https://xgboost.readthedocs.io/)

---

## 📬 Contact

**Created by** [Your Name]  
📧 Email: `rishitasarafp@gmail.com`  
🌐 GitHub: Rishita-P-Saraf (https://github.com/Rishita-P-Saraf)
