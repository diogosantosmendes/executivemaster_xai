## Abstract
This project investigates the impact of bias in Machine Learning models for predicting academic success using the LSAC Bar Passage Dataset. Logistic Regression, Decision Tree, and Random Forest classifiers were developed and compared, evaluating both predictive performance and the influence of sensitive attributes such as race, gender, and family income. Model interpretability was assessed through intrinsic methods and Explainable Artificial Intelligence (XAI) techniques, including SHAP, LIME, and ELI5, providing both global and local explanations of model decisions. The results show that improved predictive performance does not eliminate bias learned from historical data, highlighting the importance of explainability in identifying and understanding these patterns. Finally, the project includes an ethical analysis and a hypothetical assessment of the system's compliance with the European AI Act and the General Data Protection Regulation (GDPR).

## Keywords: 
Machine Learning, Explainable Artificial Intelligence (XAI), Algorithmic Bias, Fairness, Logistic Regression, Decision Tree, Random Forest, AI Act, GDPR.


### To run
(on Windows)
```
py -3.11 -m venv torch-env
.\torch-env\Scripts\Activate.ps1
pip install -r requirements.txt
```