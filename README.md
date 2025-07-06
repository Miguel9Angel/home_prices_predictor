# 🏡 PREDICTION OF HOME PRICES

![preview](/assests/model_evaluation.png)

A data science project aimed at predicting home prices using supervised regression techniques. The goal is to help buyers, sellers, and real state agents make more informed decisions based on property features and market behavior.

## 🔍 Problem

Estimating the fair value of a property in the real state market is so challenging for buyers and sellers, due to different variations and characteristics of the property. 
This project addresses this issue by analysing historical data of residential properties and applying supervised learning techniques to build predictive mdoels. The objective is to understannd how key property features influence the final sale price.

## 📊 Dataset

- Sourced: [Kaggle](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset)
- Nº of registers: 2931 houses
- Features: Order,PID,MS SubClass,MS Zoning,Lot Frontage,Lot Area,Street,Alley,Lot Shape,Land Contour,Utilities,Lot Config,Land Slope,Neighborhood,Condition 1,Condition 2,Bldg Type,House Style,Overall Qual,Overall Cond,Year Built,Year Remod/Add,Roof Style,Roof Matl,Exterior 1st,Exterior 2nd,Mas Vnr Type,Mas Vnr Area,Exter Qual,Exter Cond,Foundation,Bsmt Qual,Bsmt Cond,Bsmt Exposure,BsmtFin Type 1,BsmtFin SF 1,BsmtFin Type 2,BsmtFin SF 2,Bsmt Unf SF,Total Bsmt SF,Heating,Heating QC,Central Air,Electrical,1st Flr SF,2nd Flr SF,Low Qual Fin SF,Gr Liv Area,Bsmt Full Bath,Bsmt Half Bath,Full Bath,Half Bath,Bedroom AbvGr,Kitchen AbvGr,Kitchen Qual,TotRms AbvGrd,Functional,Fireplaces,Fireplace Qu,Garage Type,Garage Yr Blt,Garage Finish,Garage Cars,Garage Area,Garage Qual,Garage Cond,Paved Drive,Wood Deck SF,Open Porch SF,Enclosed Porch,3Ssn Porch,Screen Porch,Pool Area,Pool QC,Fence,Misc Feature,Misc Val,Mo Sold,Yr Sold,Sale Type,Sale Condition,SalePrice

## 🛠️ Techniques Used

- Data exploratory analisys (EDA)
- Feature Selection
- Regression Lineal, Lasso, RandomForest, XGBoost
- Tunning of hiperparametros with GridSearchCV

## 📈 Results

- RMSE: 24549
- MAE: 16000
- R²: 0.91
- Most important features: Lot Area, Gr Liv Area,  Total Bsmt SF, BsmtFin SF 1

## 🧠 Lessons learn

The most influential features were ralated to the pyshical chatacteristics of the house, such as the area of key sections of the property. Interestingly, one feture indicating the month in wich the house was sold a noticeable price increase during the summer months, according to the SHAP analysis.
This behavior suggest that externals factors,such as seasonality, can alse affect a property´s sale price. this insight provides a valuable starting point for futher improving the model´s predictive performance

## 🚀 How to run this project

Follow these steps to run the project on your local machine:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Miguel9Angel/home_prices_predictor.git
cd home_prices_predictor
```

### 2️⃣ Requirements
pip install -r requirements.txt

### 3️⃣ Run the notebook
jupyter notebook notebooks/house_price_prediction.ipynb

## 📁 Repository estructure

```text
HOUSE_PRICE_PREDICTION/
├── assets/
│   └── model_evaluation.png
├── data/
│   ├── AmesHousing.csv
│   └── DataDocumentation.txt
├── notebooks/
│   └── house_price_prediction.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

## 📜 Licence

This project is licensed under the [Licencia MIT](./LICENSE).  
You are free to use, modify, and distribute this code, provided that proper credit is given.

--------------------------------------------------------------------------------------

## 🙋 About me

My name is Miguel Angel Soler Otalora, a mechanical engineer with a background in data science and artificial intelligence. I combine the analytical and structured thinking of engineering with modern skills in data analysis, visualization, and predictive modeling.

This project is part of my portfolio to apply for roles as a Data Analyst or Data Scientist, and it reflects my interest in applying data analysis to real-world problems.

📫 You can contact me on [LinkedIn](https://linkedin.com/in/miguel-soler-ml) or explore more projects on [GitHub](https://github.com/Miguel9Angel).