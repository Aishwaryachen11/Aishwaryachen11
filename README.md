<h1>Hi, I'm Aishwarya! <br/><a href="https://www.linkedin.com/in/aishwarya-chennabathni/">Data Scientist</a>

<h2>👨‍💻 Introduction:</h2>

I’m an accomplished Data Scientist with over 6 years of experience designing, building, and deploying end-to-end AI & ML solutions across healthcare, logistics, insurance, real estate, and public sector domains.
My work blends technical depth with business impact, from predictive modeling and clustering to large-scale ML pipelines and explainable AI.

💡 What I Do:
Build and deploy supervised learning models: XGBoost, Gradient Boosting, Random Forests, Logistic Regression, LSTMs, RNNs for classification, forecasting, and behavioral segmentation.
Design unsupervised systems like K-Means, DBSCAN, and Hierarchical Clustering, validating their real-world utility through stratified supervised models with SHAP-based interpretation.
Apply statistical modeling: A/B testing, causal inference, uplift modeling, anomaly detection, and interpretability techniques using LIME for model insights.

⚙ Tech Stack:
Languages: Python, SQL
ML/DL Libraries: Pandas, NumPy, Scikit-learn, PyTorch, TensorFlow, Hugging Face, Statsmodels
Data Platforms: Snowflake, Redshift, BigQuery
MLOps & Cloud: AWS, GCP, MLflow, GitHub Actions, Cloud Run
Model Monitoring: Drift detection, alert-based retraining, SHAP, LIME, gradient diagnostics

🚀 Highlights:
Developed scalable ML pipelines with monitoring & automated retraining for triage simulation and policy planning.
Applied advanced feature engineering, PCA, L1/L2 regularization, and optimization with Optuna & Bayesian search.

<h2>💡 My projects </h2>

Welcome to my GitHub portfolio! Here are some of the projects I've worked on.

### Fashion MNIST Classification using Deep Neural Networks (Keras)
**Description:** Classified fashion items from the Fashion MNIST dataset using a custom feedforward neural network in TensorFlow/Keras. Applied best practices like dropout, early stopping, and optimizer tuning for robust generalization.

**Models / Tools / Techniques:** Feedforward NN · Python · TensorFlow · Keras · NumPy · Matplotlib  
Hyperparameter tuning · Dropout (30%) · Adam optimizer (lr=0.0005) · Early stopping · Learning curve visualization

**Highlights:**  ~89.2% test accuracy · Minimal overfitting · Custom 3-layer architecture · Integrated dropout & early stopping

 [**Open Colab**](https://github.com/Aishwaryachen11/Fashion-mnist-classification-keras/blob/main/Fashion_MNIST_Portfolio_Project.ipynb)   [**GitHub Repo**](https://github.com/Aishwaryachen11/Fashion-mnist-classification-keras)

### Telco Customer Churn Prediction using Logistic, Random Forest, XGBoost

**Description:** Predicted telecom customer churn using Logistic Regression, Random Forest, and XGBoost, with SHAP-based explainability to identify key churn drivers for targeted retention strategies.

**Models / Tools / Techniques:**  Logistic Regression · Random Forest · XGBoost (tuned & regularized) · Python · Pandas · NumPy · Scikit-learn · SHAP · Matplotlib  
Data cleaning · OneHotEncoding · StandardScaler · Class imbalance handling · Hyperparameter tuning · Regularization · Early stopping

**Highlights:** Highest recall (0.791) using regularized XGBoost with minimal overfitting · SHAP insights identified top churn drivers (contract type, tenure, monthly charges, service add-ons)

[**Open Colab**](https://github.com/Aishwaryachen11/telco-customer-churn-prediction_XGBoost/blob/main/Customer_churn_XGBoost%2C_Random_Forest.ipynb)  [**GitHub Repo**](https://github.com/Aishwaryachen11/telco-customer-churn-prediction_XGBoost)

### SARIMA Time Series Forecasting – AirPassengers

**Description:** Forecasted monthly airline passenger counts using a SARIMA model to capture both trend and seasonality. Performed stationarity checks, differencing, parameter tuning, and evaluated model accuracy with RMSE and MAPE.

**Models / Tools / Techniques:** SARIMA · Python · Pandas · Statsmodels · Matplotlib  
ADF test · First-order & seasonal differencing · Seasonal ARIMA parameter tuning · Time series visualization

**Highlights:** RMSE: 15.56 · MAPE: 4.57% (high accuracy) · Successfully modeled strong yearly seasonality · Produced clear forecast vs actual visualizations

[**Open Colab**](https://github.com/Aishwaryachen11/SARIMA-TimeSeries-AirPassengers-Forecasting/blob/main/SARIMA_AirPassengers_Project.ipynb)   [**GitHub Repo**](https://github.com/Aishwaryachen11/SARIMA-TimeSeries-AirPassengers-Forecasting)

### Sentiment Analysis on Amazon Fine Food Reviews

**Description:**  
Performed sentiment classification (Positive, Negative, Neutral) on the Amazon Fine Food Reviews dataset. Built Logistic Regression and Multinomial Naive Bayes models with TF-IDF features, handled class imbalance, and used SHAP to explain model predictions.

**Models / Tools / Techniques:**  
Logistic Regression · Multinomial Naive Bayes · Python · Pandas · NumPy · Scikit-learn · NLTK · SHAP · Matplotlib  
Text preprocessing (stopword removal, lemmatization) · TF-IDF (unigrams + bigrams) · Class imbalance handling · Model explainability

**Highlights:**  
~85% accuracy · Logistic Regression gave best overall balance between precision/recall · SHAP revealed top impactful words for each sentiment · Live prediction demo with confidence scores

[**Open Colab**](https://github.com/Aishwaryachen11/Sentiment-Analysis---Amazon-Customer-reviews/blob/main/Sentiment_Analysis_Customer_reviews.ipynb)   [**GitHub Repo**](https://github.com/Aishwaryachen11/Sentiment-Analysis---Amazon-Customer-reviews)

## 💳 Credit Card Default Prediction – American Express Dataset

**Description:**  
Predicted credit card defaults using American Express credit risk data. Built and compared multiple ML models (Logistic Regression, Decision Tree, Random Forest, KNN, XGBoost) to identify high-risk customers, improve portfolio management, and provide actionable financial insights.

**Models / Tools / Techniques:**  
Logistic Regression · Decision Tree · Random Forest · KNN · XGBoost · Python · Pandas · NumPy · Scikit-learn · Seaborn · Matplotlib  
Data preprocessing (missing value handling, feature scaling, stratified sampling) · Class imbalance handling · Feature importance analysis · ROC/AUC evaluation

**Highlights:**  
XGBoost & Random Forest achieved highest accuracy and ROC AUC · Key predictors: credit score, credit limit usage, net yearly income · Insights for targeted credit policies and risk-based pricing

[**Open Colab**](https://github.com/Aishwaryachen11/Credit_Card_Default_Analysis/blob/main/Credit_Card_Default_Prediction.ipynb)   [**GitHub Repo**](https://github.com/Aishwaryachen11/Credit_Card_Default_Analysis)

## ⚖ Named Entity Recognition (NER) for Legal Documents – ECtHR Cases

**Description:**  
Built NER models to extract legal-specific entities (CASE_NUMBER, ARTICLE_REF, PERSON, COUNTRY, ORG, LAW) from European Court of Human Rights case documents. Implemented complete pipeline from text extraction and annotation preparation to model training, evaluation, and error analysis.

**Models / Tools / Techniques:**  
BiLSTM · Legal-BERT · HuggingFace Transformers · Pandas · seqeval  
Data preprocessing · Tokenization & BIO tagging · Doccano/Label Studio integration · Train/dev/test split by document · Model evaluation & confusion analysis

**Highlights:**  
Developed domain-specific label schema · Prepared dataset in CoNLL BIO format · Achieved robust entity extraction with Legal-BERT · Added error analysis and simple rule-based explainability

[**Open Colab**](https://github.com/Aishwaryachen11/ECtHR-Legal-NER/blob/main/NER_Legal_Documents.ipynb)   [**GitHub Repo**](https://github.com/Aishwaryachen11/ECtHR-Legal-NER)


### 6. 🔍 SQL_Data-Exploraton of COVID-19 Data

**Description:** Analysis of COVID-19's global impact, examining infection rates, mortality rates, and vaccination progress across different countries and continents using SQL.

You can view the results of the BigQuery query [here](https://console.cloud.google.com/bigquery?sq=891015959491:6dce298f69b84930b10767858997b1b8).

**[View Repository](https://github.com/Aishwaryachen11/SQL_Data-Exploraton)** 

<h2> 🤳 Connect with me:</h2>

Feel free to reach out if you have any questions or would like to collaborate on a project!

[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="Aishwarya Chennabathni | Gmail" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />][gmail]

[linkedin]:https://www.linkedin.com/in/aishwarya-chennabathni/
[gmail]:mailto:aishwarya.chen11@gmail.com

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
