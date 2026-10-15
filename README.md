# data-science-project_mc661372
# Data Science Project

## 1. Problem / Research Question
This project explores patterns within event log data. The research question is: can we extract useful features from event logs and build a classification model to predict the target label, and discover key behavioural patterns from the event sequence?

## 2. Dataset source and usage permissions
- Dataset source: Event log CSV dataset provided for the course mini-project.
- Usage permission: This dataset is used solely for academic analysis in this course project. There is no personal identifiable information, passwords or restricted data contained in the dataset.

## 3. Methods and tools used
- Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- Methods: Data loading and cleaning, exploratory data analysis (EDA), feature engineering from event sequences, data visualisation, supervised machine learning classification, performance evaluation.

## 4. Key findings and one limitation
### Key findings
EDA shows that certain event types strongly correlate with the target outcome. Feature sets built from event timestamps and event sequences can produce a classifier with reasonable F1 score. The visualisations reveal clear differences in event distribution between positive and negative samples.

### Limitation
One limitation: The dataset is from a single sample period. The trained model may not generalise well to event logs collected under different time periods or different user groups.

## 5. Instructions for running the analysis
1. Clone this repository to your local machine:
```bash
git clone https://github.com/Tanyanhua2026/data-science-project.git
