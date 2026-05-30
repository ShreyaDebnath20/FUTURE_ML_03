# AI Resume Screening

## Project Overview
This project predicts recruiter hiring decisions using machine learning techniques based on candidate resume information. The goal is to automate resume screening and identify key factors influencing recruiter decisions.

## Dataset
- Source: Kaggle AI Resume Screening Dataset
- Features:
  - Name
  - Skills
  - Experience (Years)
  - Education
  - Projects Count
  - Salary Expectation
  - AI Score
  - Recruiter Decision (Target)

## Project Structure

| Folder/File                 | Description                                 |
| --------------------------- | ------------------------------------------- |
| `data/`                     | Dataset files                               |
| `notebooks/`                | Jupyter notebooks for analysis and modeling |
| `01_data_exploration.ipynb` | Exploratory Data Analysis                   |
| `02_preprocessing.ipynb`    | Data cleaning and preprocessing             |
| `03_model_training.ipynb`   | Random Forest model training                |
| `04_results.ipynb`          | Model evaluation and results                |
| `models/`                   | Saved machine learning models               |
| `reports/`                  | Generated reports and outputs               |
| `src/`                      | Source code files                           |
| `main.py`                   | Main execution script                       |
| `requirements.txt`          | Project dependencies                        |
| `README.md`                 | Project documentation                       |

## Exploratory Data Analysis
- Examined dataset structure
- Checked missing values
- Analyzed feature distributions
- Explored target class balance

## Data Preprocessing
- Removed duplicate records
- Selected relevant features
- Encoded categorical variables
- Prepared target labels

## Model Training
Algorithm Used:
- Random Forest Classifier

## Results

| Metric | Score |
|----------|----------|
| Accuracy | 100% |

## Feature Importance
1. AI Score (0-100)
2. Experience (Years)
3. Projects Count
4. Salary Expectation ($)

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Author
Shreya Debnath
