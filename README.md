#  Migraine Prediction System using Machine Learning

A machine learning-based migraine prediction system developed using real-world survey data, data preprocessing, feature engineering, and predictive modeling techniques.

[![Prediction](https://img.shields.io/badge/View%20migraine_Pridiction-Get%20Pridiction-0A66C2?style=for-the-badge&logo=github&logoColor=white)](https://saadsarfraz438.github.io/migraine-prediction-ml/)

---

##  Project Overview

This project aims to predict the likelihood of migraines based on lifestyle habits, health conditions, and migraine triggers collected through a structured survey.

The system processes raw survey responses, cleans and transforms the dataset into machine-learning-ready format, and applies predictive models to classify migraine risk.

This project was completed in multiple phases, including **survey data collection, preprocessing, feature engineering, and model preparation**.

---

##  Objective

The main goal of this project is to prepare a real-world healthcare dataset for machine learning and build a migraine prediction system that can help identify migraine patterns early.

The project focuses on:

- Data cleaning and preprocessing
- Feature engineering
- Converting survey responses into numerical values
- Preparing a machine-learning-ready dataset
- Predicting migraine likelihood based on user inputs

---

## Dataset Information

### Dataset Source
Survey-based migraine dataset collected through **Google Forms**.

### Dataset Files
- `Part 1`: Raw survey responses (`100 responses`)
- `Part 2`: Processed and engineered dataset (`CSV format`)
- `Part 3`: Colabbook (python code)

### Features Included
The dataset contains migraine-related factors such as:

- Sleep patterns
- Stress levels
- Screen time
- Water intake
- Physical activity
- Migraine history
- Lifestyle habits
- Symptoms and triggers

### Label (Target Variable)
**Migraine Status / Migraine Prediction**

This column was selected as the target variable because it represents the health outcome to be predicted.

---

##  Project Workflow

### 1. Data Collection
- Created a structured migraine survey using **Google Forms**
- Collected real-world responses from participants
- Stored responses in Excel format

---

### 2. Data Understanding
Performed dataset analysis including:

- Total number of rows and columns
- Identification of:
  - Numerical data
  - Categorical data
  - Text-based data
- Selection of target label

---

### 3. Data Cleaning
Applied multiple preprocessing techniques:

- Removed unnecessary columns
  - Timestamp
  - Names / IDs

- Fixed inconsistent values
  - Converted ranges into numeric values
  - Removed spelling inconsistencies
  - Removed extra spaces

Examples:

| Original Value | Converted Value |
|---------------|----------------|
| 5–6           | 5.5            |
| 6 to 7        | 6.5            |
| 8–9           |8.5             |

- Handled missing values:
  - Numerical columns → replaced with average values
  - Categorical columns → replaced with most frequent value

---

### 4. Feature Engineering
To make data understandable for machine learning models:

#### Categorical Encoding
Text responses converted into numerical values.

Example:

| Text Value | Numeric Value |
|------------|---------------|
| Rarely     |  0            |
| Sometimes  |  1            |
| Often      |  2            |



#### Multiple Choice Handling
Columns containing multiple answers were:

- Split into separate columns
- Converted into binary values

Example:

| Symptom | Value |
|----------|-------|
| Headache | 1     |
| Nausea   | 0     |

#### Range Conversion
Converted response ranges into single numerical values.

Example:

| Range  | Converted |
|--------|-----------|
| 5–6    | 5.5       |
| 8–9    | 8.5       |

---

### 5. Final Dataset Preparation

The final dataset contains:

 Numerical columns only  
 Engineered features  
 Cleaned and normalized data  
 Clearly separated:

- **Input Features (X)**
- **Target Variable (Y)**

The processed dataset is saved in:
```csv
 migraine_prediction.csv 
```
---

### 6. Machine Learning Model

Machine learning algorithms were applied to train the migraine prediction system.

---

##### Models explored include:

Decision Tree Classifier
Random Forest Classifier
Logistic Regression 

The model predicts whether a person is likely to experience migraines based on survey inputs.

---
```
###  Technologies Used
Python
Pandas
NumPy
Scikit-Learn
Microsoft Excel
Google Forms
Google Colab / Jupyter Notebook
```
---

```
### Project Structure
├── data/
│   ├── migraine_prediction_survey.xlsx
│   ├── migraine_prediction.csv
│
├── notebook/
│   └── model_training.ipynb
│
├── src/
│   ├── preprocessing.py
│   └── feature_engineering.py
│
├── reports/
│   └── preprocessing_report.pdf
│
├── README.md

```
---

### Future Improvements

Planned enhancements include:

Web-Based Prediction System (working)

###### Users will be able to:

Open a prediction link
Fill out the migraine survey
Get instant migraine prediction results

#### Possible deployment options:

Flask
Streamlit
FastAPI
Local System Execution

#### Users can also:

Download the project
Run it on their own PC
Input personal survey data
Receive migraine predictions locally

---

### In Progress
Increase dataset size
Improve prediction accuracy
Add advanced ML models
Explore deep learning approaches

---

### Project Goal

To build a smart migraine prediction system that helps users identify migraine risks early and take preventive measures based on lifestyle and health indicators.

---

### Contribution
 Contributions are welcome.Feel free to fork the repository, improve the preprocessing pipeline, or enhance the prediction model.

### support
- GitHub Issues - Bug reports and feature requests
- GitHub Discussions - Questions and community chat
- Reach out via:
  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saadsarfraz.se@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/saad-sarfraz-389450350/)
[![Twitter / X](https://img.shields.io/badge/X-black?style=for-the-badge&logo=x)](https://x.com/Saadsarfraz438)

