# Heart Disease Health Indicators Dataset


## About the Dataset

### Context

Heart Disease is among the most prevalent chronic diseases in the United States, impacting millions of Americans each year and exerting a significant financial burden on the economy. In the United States alone, heart disease claims roughly 647,000 lives each year — making it the leading cause of death. The buildup of plaques inside larger coronary arteries, molecular changes associated with aging, chronic inflammation, high blood pressure, and diabetes are all causes of and risk factors for heart disease.

While there are different types of coronary heart disease, the majority of individuals only learn they have the disease following symptoms such as chest pain, a heart attack, or sudden cardiac arrest. This fact highlights the importance of preventative measures and tests that can accurately predict heart disease in the population prior to negative outcomes like myocardial infarctions (heart attacks) taking place.

### Content

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. For this project, a dataset was obtained from the BRFSS for the year 2015, containing 253,680 survey responses. These responses are used primarily for the binary classification of heart disease.

**Dataset Characteristics:**
- Number of Responses: 253,680
- Features: 22
- Class Imbalance: 229,787 respondents do not have/have not had heart disease, while 23,893 have had heart disease.

You can access the dataset from [this Kaggle dataset link](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset/data).

## Data Notebook

For a detailed exploration and analysis of the Heart Disease Health Indicators Dataset, you can refer to the associated Jupyter Notebook available on Kaggle:

[Data Notebook on Kaggle](https://www.kaggle.com/fajemisinadeniyi/heart-disease/edit)

This notebook provides insights into data cleaning, feature engineering, and additional details related to the dataset.

## Project Objectives

1. **To what extent can survey responses from the BRFSS be used for predicting heart disease risk?**
2. **Can a subset of questions from the BRFSS be used for preventative health screening for diseases like heart disease?**

## Getting Started

To get started with the project and access the dataset, you can download it from the following link:

[Heart Disease Health Indicators Dataset on Kaggle](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset/data)

Simply click on the link to access the dataset and download it for your analysis and projects.

## Data Analysis

We performed data analysis and model development in Python. Key steps include:

- Data cleaning and preprocessing.
- Model development using various classifiers, including Logistic Regression, Decision Trees, Random Forest, AdaBoost, Gradient Boosting, and XGBoost.
- Model evaluation based on accuracy, precision, and recall.
- Model fusion to achieve a balance between precision and recall.

## Model Selection

Choosing the right model depends on the specific goals and constraints of the application. We considered high recall models, high precision models, and a fusion approach to balance the two.

## Model Evaluation

We used classification reports and confusion matrices to evaluate the models. Our selected model achieved an accuracy of 88%, a recall of 0.47, and a precision of 0.37. These metrics are critical in understanding the model's performance.

## Feature Importance

We calculated and visualized feature importances for both Logistic Regression and Gradient Boosting models. Understanding the impact of different features can provide valuable insights into heart disease risk factors.

## License

This dataset is not owned by the project author and is subject to its own license. Please refer to the original dataset for licensing information.

## Contributors

- [Your Name](https://github.com/Neecrownsmith) - Project Creator and Data Analyst

## Feedback and Contributions

We welcome feedback, contributions, and collaborations. If you have any suggestions or would like to contribute to this project, please [create an issue](link_to_issues) or [submit a pull request](link_to_pull_requests).
