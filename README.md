# EE4685-Red-Wine-Quality-Prediction
**Lecture project of EE4685 Machine Learning, a Bayesian Perspective**

_Use Bayesian machine learning to predict the quality of wine quality_

Authors: Yanqi Hong | Hongrui Liu 

The red wine sector has witnessed a notable surge in recent times, driven by the increasing prevalence of social drinking. As a result, industry stakeholders are increasingly leveraging product quality certifications to differentiate their offerings. However, this certification process is typically labor-intensive and costly, relying on assessments conducted by human experts. To address these challenges, there is growing interest in employing machine learning models to control the quality assessment process. This experiment report is based on Portuguese "Vinho Verde" wine from UCI machine learning repository \texttt{https://archive.ics.uci.edu/ml/datasets/wine+quality}, which is widely used by machine learning researchers.

The red wine quality dataset comprises 1.5k entries, with each entry documenting 12 features of a particular type of red wine, such as pH, acidity, and density, among others, along with its quality rating. 
Furthermore, the red wine quality dataset has a skewed distribution in the "Quality" variable, with most samples in the medium category and fewer in excellent and poor categories, posing challenges for classification. 

Faced with these challenging datasets, our objective is to conduct a comparative analysis of the efficacy of different machine-learning algorithms. Specifically, we aim to predict the quality of red wine utilizing two primary approaches: binary classification and multiple classification. For binary classification, our methodology will include K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Gaussian Naive Bayes (GaussianNB), Logistic Regression (LR), and Random Forest (RF). For multiple classifications, in addition to those mentioned classification problems, we also use regression methods to predict the result, however, simple rounding is required dut to discrete labels. To be more specific, we will employ Linear Regression, LASSO, Ridge Regression, Bayesian Regression, ARD Regression, and Bayesian Neural Networks (BNN) for Regression. Additionally, neural network architectures such as Deep Neural Networks (DNN) and BNN will be incorporated into our investigation. By comparing these methodologies, we aim to find the best way to predict red wine quality.
