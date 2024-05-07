# Breast Cancer Prediction Project

## Introduction

Breast cancer remains one of the most prevalent and concerning health issues globally. The goal of this project is to test different machine learning models on the Coimbra dataset and determine the best-performing one across multiple metrics. Subsequently, the selected model will be utilized for binary classification, distinguishing between healthy individuals and breast cancer patients. Furthermore, the project aims to extract and analyze the strongest predictors identified by the chosen model to enhance understanding and diagnosis of breast cancer.

## Data Set Information

The dataset comprises 9 predictors and a binary dependent variable indicating the presence or absence of breast cancer. These predictors include age, BMI, glucose levels, insulin levels, HOMA, leptin levels, adiponectin levels, resistin levels, and MCP-1 levels.

## Model Performance

Our chosen Gradient Boosting model demonstrates strong overall performance, with a Test Accuracy of 83.33% and an F1 Score of 80.00%. The model accurately identifies high-risk cases of breast cancer and exhibits promising feature importance, highlighting glucose levels, age, resistin levels, insulin levels, and BMI as influential factors.

## Clinical Recommendations

We recommend integrating the Gradient Boosting model into clinical practice as a screening tool to prioritize high-risk patients for further examination. Additionally, continuous monitoring of false positive and false negative rates is crucial for improving model reliability over time.

## Ethical Considerations

Ethical considerations, including patient privacy and transparency in predictions, are paramount. Clinicians must prioritize patient confidentiality and informed consent while utilizing the model for diagnostic purposes.

## Note on Data Instances and Accuracy

Increasing the number of data instances is recommended to further enhance the model's accuracy and improve diagnostic capabilities.

## Bibliography

- [Breast Cancer Coimbra Dataset](https://archive.ics.uci.edu/dataset/451/breast+cancer+coimbra)
- [Austria, Yolanda et al. "Comparison of Machine Learning Algorithms in Breast Cancer Prediction Using the Coimbra Dataset." International journal of simulation: systems, science & technology (2019)](https://www.researchgate.net/publication/337193772)
- [Patrício, Miguel, et al. "Using Resistin, glucose, age and BMI to predict the presence of breast cancer." BMC Cancer 18 (2018)](https://doi.org/10.1186/s12885-018-4886-9)

## Installation

To install the required dependencies, run the following command:

```bash
pip install -r requirements.txt

