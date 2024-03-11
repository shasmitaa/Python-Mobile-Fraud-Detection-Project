# Python-Mobile-Fraud-Detection-Project

# Introduction
The rising number of smartphone holders has caused mobile payment systems to gain popularity over the last decade. Despite the improved transaction convenience and accessibility, the digitization of mobile payment services has heightened fraud risks, causing millions of losses in revenue and recoverable funds.

# Background
The mainstreaming of artificial intelligence (AI) technology, such as machine learning (ML) models, provides a viable mechanism to automatically detect fraudulent mobile money transactions. Nevertheless, ML models suffer from difficult-to-understand black box predictions since the rationale behind those predictions is not provided.

# Problem Statement
Explainable AI (XAI) presents a solution to this problem. It is a form of human-centric AI that provides greater comprehension of black box predictions while improving transparency and trust in AI systems.

# Methodology
This project adopts a novel approach by implementing two XAI techniques, SHAP and LIME, on a synthetic mobile money dataset to investigate the possibility of making a mobile payment fraud detection model explainable. Three models, Random Forest (RF), XGBoost, and Multilayer Perceptron (MLP), were implemented and compared to determine the best model for integration with XAI techniques.

# Programming Language and Libraries
This project was implemented in Python, utilizing various libraries such as Scikit-learn for machine learning models, SHAP and LIME for explainable AI techniques, and Pandas for data manipulation.

# Finding
In this study, the XGBoost model, which was tuned using grid search, outperformed other models by achieving the highest accuracy and recall scores of 99.88% and 99.80%, respectively.

The XAI techniques were then evaluated based on explainability, meaningfulness, and explanation accuracy, which are the three XAI principles outlined by the National Institute of Standards and Technology (NIST).

Empirical findings demonstrate that SHAP and LIME can generate explanations that can be easily understood. Nevertheless, LIME is found to be unstable and produces less accurate explanations compared to SHAP.

# Conclusion
The results demonstrate that SHAP outperforms LIME since it complies with all three NIST’s XAI principles. The outcome of the study suggests that SHAP explanations can be applied by fraud analysts and mobile payment service providers for making effective and trustworthy decisions.
