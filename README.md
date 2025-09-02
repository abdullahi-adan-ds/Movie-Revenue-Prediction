# 🎬 Movie Revenue Prediction  

A machine learning project predicting **movie revenue** using Random Forest regression.  
Developed during a data science bootcamp, this project demonstrates end-to-end **data cleaning, feature engineering, model training, and optimization**.  

---


## 📌 Project Overview  
- **Goal:** Predict movie revenue based on metadata like budget, genres, and popularity.  
- **Dataset:** [MovieLens + TMDB dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) (`movies_metadata.csv`) from Kaggle.  
- **Methods:** Data preprocessing, feature encoding, Linear Regression, Random Forest, and GridSearchCV for hyperparameter tuning.  
- **Results:** Best Random Forest model achieved **RMSE = 1.46** and **R² = 0.68**.  

---

## 🛠 Tech Stack  
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---

## 📊 Key Features  
- Handled missing values and corrected malformed data types.  
- Encoded complex categorical features (e.g., genres) using `MultiLabelBinarizer`.  
- Compared **Linear Regression vs Random Forest** (R²: 0.68 vs 0.58).  
- Feature importance showed **budget** and **vote count** as top predictors.  

---

## ⚙️ Installation  

Clone the repository:  
```bash
git clone https://github.com/your-username/Movie-Revenue-Prediction.git
cd Movie-Revenue-Prediction
Install dependencies:

pip install -r requirements.txt


Run the notebook:
Open Machine_Learning_Project_SL_CP.ipynb in Jupyter Notebook or Google Colab.

🚀 Future Work

Add more advanced models (e.g., Gradient Boosting, XGBoost).

Explore additional metadata (cast, crew, release month).

Deploy as a web app for interactive revenue prediction.
