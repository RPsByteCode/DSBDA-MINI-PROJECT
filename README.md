### **Housing Price Prediction System | Data Science & Big Data Analytics (DSBDA) Project**
**Tech Stack:** Python, Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-learn, and XGBoost.

**Guidance:** Guided by Prof. S.H. Patil at PVG’s COET.

* **Data & Pipeline:** Implemented a 6-stage machine learning pipeline. Integrated three real-world datasets containing over 1.6 million records from Ames USA, 99acres India, and Bengaluru India. Performed comprehensive data cleaning, categorical encoding, and feature scaling. Conducted Exploratory Data Analysis (EDA) focusing on price distribution, correlation heatmaps, and feature importance analysis.
* **Model Training & Evaluation:** Trained and compared three distinct regression models.
  * **Random Forest:** Achieved an R² of ~0.9999 and an RMSE of 0.00304.
  * **XGBoost:** Implemented with early stopping, achieving an R² of ~0.97.
  * **LassoCV:** Implemented with L1 regularization, achieving an R² of ~0.93 and an RMSE of 0.05336.
* **Final Outcome:** Selected the Random Forest model as the final solution due to its superior accuracy and generalization capabilities on unseen data.
