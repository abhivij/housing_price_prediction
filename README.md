# 🏠 Housing Price Prediction 

**📝 Task** : Predict house sales price based on 79 explanatory variables describing different aspects of houses in Ames, Iowa.

**📏 Evaluation metric** : Root-mean square error(RMSE) between logarithm of predicted value and logarithm of observed sales price

ℹ️ Please refer to https://www.kaggle.com/c/house-prices-advanced-regression-techniques for more details

-------------------------------------------------------------------------------------------------------

📈 **Best Public Score (RMSE on log prices) : 0.11756**
- Achieved using a voting ensemble combining **XGBoost**, **LightGBM**, and **CatBoost** regression pipelines.
- Tuned hyperparameters for each individual model pipeline using **Optuna**.
- The public score was computed on the test set without access to ground-truth sales prices.
- ⚠️Note: Several top submissions in the competition used an external dataset that closely matched the test set, leading to near-perfect RMSE scores (~0.00044).

  -------------------------------------------------------------------------------------------------------

**Main contents**
- [Getting started notebook](https://github.com/abhivij/housing_price_prediction/blob/main/housing-price-prediction.ipynb)
- [Exploratory notebook to create a high-scoring notebook](https://github.com/abhivij/housing_price_prediction/blob/main/housing-price-prediction-part-2-exploratory.ipynb)
- [High-scoring notebook](https://github.com/abhivij/housing_price_prediction/blob/main/housing-price-prediction-part-2.ipynb)
- [Best submission screenshot](https://github.com/abhivij/housing_price_prediction/blob/main/Submission_result.png)

-------------------------------------------------------------------------------------------------------

The notebooks provided here can be directly accessed and run from :
- [Kaggle - Getting started notebook](https://www.kaggle.com/code/abhivij/housing-price-prediction)
- [Kaggle - Exploratory notebook](https://www.kaggle.com/code/abhivij/housing-price-prediction-part-2-exploratory)
- [Kaggle - High-scoring notebook](https://www.kaggle.com/code/abhivij/housing-price-prediction-part-2)





