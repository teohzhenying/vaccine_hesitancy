<h1>Vaccine Hesitancy Prediction using Machine Learning and Explainable AI</h1>

<h2>Overview</h2>
<p>
This project investigates vaccine hesitancy prediction among healthcare workers using machine learning, ensemble learning and explainable AI (XAI). The aim is to identify the most important factors influencing whether a healthcare worker would agree to a subsequent vaccine booster.
</p>

<h2>Key Features</h2>
<ul>
  <li><b>Data pre-processing:</b> cleaning, encoding and normalization</li>
  <li><b>Feature selection:</b> ANOVA + Chi-Square, Information Gain, SFS and SBS</li>
  <li><b>Machine learning models:</b> KNN, Decision Tree, Naive Bayes, MLP and SVM variants</li>
  <li><b>Ensemble learning:</b> Random Forest, Bagging, Boosting and XGBoost</li>
</ul>

<h2>Explainable AI</h2>
<p>
SHAP and LIME were used to explain model predictions. To improve explanation consistency, this project introduces <b>LocalWeightFusion</b> and <b>GlobalWeightFusion</b>, which combine explainability results into more stable feature importance rankings.
</p>

<h2>Evaluation</h2>
<ul>
  <li>Kendall Tau</li>
  <li>Rank-Biased Overlap (RBO)</li>
  <li>Recall@K</li>
</ul>

<p>
The fusion methods produced more stable rankings compared to individual explainability methods.
</p>

<h2>Dataset and Privacy</h2>
<p>
The original raw preprocessing data received is not included due to privacy concerns. The files in this repository contain processed, encoded, normalised, aggregated, or feature-selected datasets used for model training and explainability analysis.
</p>

<h2>Repository Structure</h2>
<ul>
  <li><b>pre-processing vaccine data/</b> – data preparation</li>
  <li><b>feature_selection/</b> – feature selection experiments</li>
  <li><b>FS_all/</b> – base models using all features</li>
  <li><b>FS_agg/</b> – aggregated feature models</li>
  <li><b>ensemble-learning/</b> – ensemble learning experiments</li>
  <li><b>fusion xai/phase_4/</b> – local XAI fusion</li>
  <li><b>fusion xai/phase_5/</b> – global XAI fusion</li>
  <li><b>fusion xai/results/</b> – final feature importance rankings</li>
</ul>

<h2>Note</h2>
<p>
This repository focuses on research, explainability analysis and methodology development rather than deployment as a production healthcare system.
</p>
