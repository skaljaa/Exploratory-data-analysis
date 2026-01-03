# 🏠 House Price Prediction

A machine learning regression project to predict California house prices.

## 📊 Dataset
- **Source:** California Housing Dataset (1990 US Census)
- **Size:** 20,640 samples, 9 features
- **Target:** Median house value ($)

## 🔍 Features
| Feature | Description |
|---------|-------------|
| median_income | Median income in block group |
| housing_median_age | Median house age |
| total_rooms | Total rooms in block group |
| total_bedrooms | Total bedrooms in block group |
| population | Block group population |
| households | Number of households |
| latitude/longitude | Location coordinates |
| ocean_proximity | Distance to ocean (categorical) |

## 🛠️ Project Steps
1. Exploratory Data Analysis
2. Visualization (heatmap, scatter, geo map)
3. Outlier detection & handling
4. Missing value treatment
5. Model training & evaluation

## 📈 Results
| Model | R² Score |
|-------|----------|
| Linear Regression | ~0.65 |
| Random Forest | **~0.81** |
| Gradient Boosting | ~0.78 |

## 🧰 Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 🚀 Usage
```bash
pip install pandas numpy matplotlib seaborn scikit-learn missingno
jupyter notebook HousePricePrediction.ipynb
```
