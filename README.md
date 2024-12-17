# Mortality Prediction in ICU Heart Failure Patients
## 1. Introduction
### 1.1 Problem Overview:
The prediction of in-hospital mortality in heart failure patients admitted to the intensive care unit (ICU) remains a significant challenge in healthcare. Early detection of high-risk patients can lead to more effective treatment interventions and improved patient outcomes. This study utilizes the MIMIC-III dataset, a comprehensive ICU patient database, to identify key predictors of in-hospital mortality in heart failure patients. The analysis employs machine learning-based models and statistical techniques to uncover patterns and relationships in the data.

### 1.2 Scientific Questions:
The study investigates the following key scientific questions:
1. Can we identify early signs of mortality based on patient demographic, clinical, and laboratory data?
2. Is stacking providing a better performance compared to bare base learners?

### 1.3 Data Source Reference:
Zhou, Jingmin et al. (2021). Prediction model of in-hospital mortality in intensive care unit patients with heart failure: machine learning-based, retrospective analysis of the MIMIC-III database. Dryad, Dataset, https://doi.org/10.5061/dryad.0p2ngf1zd.

### 1.4 Summary of Data Analysis:
Preliminary findings suggest that key variables, including vital signs, comorbidities, and laboratory results, significantly contribute to predicting mortality risk. Machine learning models, such as logistic regression, decision trees, and neural network, were employed to utilize these variables for predictions.

### 1.5 Roadmap of the Report:
The report is structured as follows: Section 2 details the data cleaning and preprocessing steps. Section 3 presents the methodology and model selection and then discusses the results and findings. Section 4 contains technical details and other supporting information.

## 2. Methods
### 2.1 Data Summary
The dataset used in this study is the Hospital Mortality Dataset. It is designed to support predictive modeling for in-hospital mortality in ICU patients with heart failure. The dataset consists of 51 variables for a cohort of ICU patients and is structured into four main categories: demographic characteristics, vital signs, comorbidities, and laboratory test results.
(1) Demographic Characteristics: Includes age, sex, ethnicity, weight, and height.
(2) Vital Signs: Describes key measurements such as heart rate, systolic and diastolic blood pressure, respiratory rate, body temperature, and oxygen saturation.
(3) Comorbidities: Contains records of conditions such as hypertension, atrial fibrillation, ischemic heart disease, diabetes mellitus, chronic kidney disease, and COPD.
(4) Laboratory Variables: Encompasses hematological and metabolic markers such as blood urea nitrogen, creatinine, glucose, electrolytes, and other critical clinical values.

The dataset is comprehensive and diverse, with a mix of continuous and categorical variables. While most data are complete, some laboratory variables have missing values. This dataset serves as a valuable resource for developing machine learning models aimed at predicting mortality outcomes in critical care settings.



