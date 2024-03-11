# Python-Mobile-Fraud-Detection-Project
The rising number of smartphone holders has caused mobile payment systems to gain popularity over the last decade. Despite the improved transaction convenience and accessibility, the digitization of mobile payment services has heightened fraud risks, causing millions of losses in revenue and recoverable funds. The mainstreaming of artificial intelligence (AI) technology, such as machine learning (ML) models, provides a viable mechanism to automatically detect fraudulent mobile money transactions. However, ML models suffer from difficult-to-understand black box predictions since the rationale behind those predictions is not provided.

# Methodology
This project adopts a novel approach by implementing two XAI techniques, SHAP and LIME, on a synthetic mobile money dataset to investigate the possibility of making a mobile payment fraud detection model explainable. Three models, Random Forest (RF), XGBoost, and Multilayer Perceptron (MLP), were implemented and compared to determine the best model for integration with XAI techniques.

**1) Data selection -** The synthetic Pay Sim dataset from Kaggle which contains over 6 million simulated mobile money transaction is selected. 
**2) Data pre-processing -** Irrelevant variables and observations are removed to improve data quality and reduce model complexity.
**3) Data transformation -** Feature engineering, encoding and class balancing techniques are applied to convert the data into a suitable format for data mining.
**4) Data mining -** XGBoost, RF and MLP are applied due to their wide and successful use in mobile payment fraud detection literature.
**5) Interpretation and evaluation -** The best model is determined using various evaluation metrics such as accuracy, precision, recall and AUC scores. XAI techniques, specifically SHAP and LIME are then applied 
                                       to the best model and evaluated due to their ability in providing stable and interpretable explanations in past studies. 

# Programming Language and Libraries
This project was implemented in Python, utilizing various libraries such as Pandas and Numpy for data manipulation, Matplotlib and Seaborn for data visualization as well as Scikit-learn for machine learning models.

# Findings
1) In this study, the XGBoost model, which was tuned using grid search, outperformed other models by achieving the highest accuracy and recall scores of 99.88% and 99.80%, respectively.
2) Empirical findings demonstrate that SHAP and LIME can generate explanations that can be easily understood.
3) LIME is found to be unstable and produces less accurate explanations compared to SHAP.
