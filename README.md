# **The Impact of Public Sentiment on Bitcoin Returns**

This repository contains the code for a project that explores the use of **sentiment analysis** and **machine learning models** to predict Bitcoin price movements. The project focuses on analyzing public sentiment from Twitter and other financial indicators to gain insights into Bitcoin market trends. 

## **Features**

- **Sentiment Analysis**: Extract sentiment from Bitcoin-related tweets using libraries like TextBlob, VADER, and Pattern.
- **Correlation Analysis**: Cluster variables and identify relationships using advanced correlation heatmaps.
- **Feature Engineering**: Includes lagged features, percentage change metrics, and sentiment-based features.
- **Machine Learning Models**: Evaluate models like Decision Tree, AdaBoost, XGBoost, and CatBoost for prediction.
- **Explainability with SHAP**: Gain insights into the impact of features like Fear and Greed Index, Wikipedia visits, and sentiment on predictions.

---

## **Project Workflow**

1. **Data Preparation**
   - Clean and preprocess Bitcoin-related tweets.
   - Normalize data and generate lagged features for better predictions.

2. **Exploratory Data Analysis**
   - Analyze trends in tweet frequency, sentiment scores, and Bitcoin price.
   - Visualize correlations using heatmaps and clustering.

3. **Model Training**
   - Train models with an 80/20 train-test split.
   - Evaluate models on test data to find the best-performing algorithm.

4. **Explainability**
   - Use SHAP (Shapley Additive Explanations) to interpret model predictions and understand key drivers of price movements.
  
Read the detailed article [here](https://www.linkedin.com/pulse/impact-public-sentiment-bitcoin-returns-part-1-hirad-dolatzadeh-4fgtf/?trackingId=SCuOSjBZQxSKHt587brTyg%3D%3D) for more insights.

---

## **Key Results**

- **Best Model**: AdaBoost achieved the highest accuracy (62%) in predicting Bitcoin price movements. 
- **Key Insights**:
  - Changes in the **Fear and Greed Index** have a significant impact on predictions.
  - Closing price trends and sentiment from tweets (via VADER) are critical indicators.
  - An increase in **Bitcoin Wikipedia page views** is positively correlated with Bitcoin returns.

---

## **Contributions**

Contributions are welcome! If you have ideas to improve the model, add new features, or optimize performance, feel free to submit a pull request.

---

## **Acknowledgments**

- Data Sources: [Public Bitcoin-related tweets](https://www.kaggle.com/datasets/hiraddolatzadeh/bitcoin-tweets-2021-2022), Fear and Greed Index, Wikipedia visit counts.
- Tools Used: Python, Pandas, Scikit-learn, SHAP, Seaborn, Matplotlib.

---

Happy predicting! 😊 

