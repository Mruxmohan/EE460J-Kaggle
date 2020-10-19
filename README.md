# EE460J-Kaggle
Ongoing prep for 10/19/20-10/24/20 kaggle competition

Kaggle Comps (Binary classifications with categorical data):
<ul>
  <li>Cat in the Dat: https://www.kaggle.com/c/cat-in-the-dat</li>
  <li>Cat in the Dat ii: https://www.kaggle.com/c/cat-in-the-dat-ii</li>
  <li>VSB Power Line Fault Detection: https://www.kaggle.com/c/vsb-power-line-fault-detection/overview/evaluation</li>
  <li>IEEE-CIS Fraud Detection: https://www.kaggle.com/c/ieee-fraud-detection/overview/evaluation/</li>
  <li>Satander Customer Transaction Prediction: https://www.kaggle.com/c/santander-customer-transaction-prediction/notebooks</li>
  <li>Remaining Comps (31 total): https://www.kaggle.com/search?q=tag%3A%22binary+classification%22+in%3Acompetitions</li>
</ul>

Helpful Articles: 
<ul>
  <li>Tips & Tricks for Tabular Data (Binary Classifiers): https://medium.com/neptune-ai/tabular-data-binary-classification-all-tips-and-tricks-from-5-kaggle-competitions-51667b21876e</li> 
  <li>Feature Selection with Categorical Data: https://machinelearningmastery.com/feature-selection-with-categorical-data/</li> 
  <li>Categorical Data Encoding: https://www.analyticsvidhya.com/blog/2020/08/types-of-categorical-data-encoding/</li> 
  <li>ROC and Precision-Recall Curves: https://machinelearningmastery.com/roc-curves-and-precision-recall-curves-for-classification-in-python/</li>
  <li>L1 vs. L2 Regularization: https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c</li>
</ul>

Tricks with larger Datasets:
<ul>
  <li>Faster data loading with pandas</li>
  <li>Data compression techniques</li>
</ul>

Data Exploration (for feature engineering):
<ul>
  <li>TBD</li>
  <li>TBD</li>
  <li>TBD</li>
</ul>

Data Preparation:
<ul>
  <li>Imputate missing vals with most freq val of each column: df = df.apply(lambda x:x.fillna(x.value_counts().index[0]))</li>
  <li>Tackle class imbalance</li>
  <li>Encoding techniques for categorical data</li>
</ul>

Feature Selection:
<ul>
  <li>Tree explainer using SHAP</li>
  <li>Use sklearn (6 ways from article)</li>
</ul>

Decide Best Models/Evaluate:
<ul>
  <li>Parameter Tuning with Hyperopt: https://medium.com/district-data-labs/parameter-tuning-with-hyperopt-faa86acdfdce#:~:text=uniform%20is%20a%20built%2Din,for%20tree%20of%20Parzen%20estimators.&text=This%20fmin%20function%20returns%20a%20python%20dictionary%20of%20values.</li>
  <li>Random Forest/XGBoost/CatBoost/LightGBM/Logistic Regression</li>
  <li>CatBoost Params: https://towardsdatascience.com/https-medium-com-talperetz24-mastering-the-new-generation-of-gradient-boosting-db04062a7ea2</li>
  <li>Weighted average or stacked generalization ensemble</li>
  <li>AUC Weight Optimization</li>
</ul>
