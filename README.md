# Cyber-Attack Type Prediction and Human Factors in Critical Infrastructure

## Project Overview
This project investigates the use of machine learning models to predict cyberattack types and explores how human factors influence the security of critical infrastructure systems.

The research focuses on two main areas. On one hand, it evaluates different machine learning algorithms using the Global Cybersecurity Threats (2015–2024) synthetic dataset to identify cyberattack types. On the other hand, it investigates the impact of human factors, particularly security awareness, training, and insider threats, through a survey of IT students in Jordan.

## Research Objectives
The project aims to:

- Evaluate machine learning models for cyberattack type prediction.
- Compare the performance of Random Forest, Support Vector Machine (SVM), XGBoost, K-Nearest Neighbors (KNN), and Naive Bayes.
- Investigate the importance of security awareness and training.
- Explore how insider threats affect critical infrastructure security.
- Provide recommendations based on the research findings.

## Data Collection
The research uses both primary and secondary data.

### Primary Data
Primary data was collected through a Google Forms survey consisting of eight closed-ended questions. The survey received 37 responses from IT students at universities in Jordan.

The questions focused on cybersecurity awareness, security training, confidence in organizational security, and the risks associated with insider threats.

### Secondary Data
The secondary dataset was obtained from Kaggle: Global Cybersecurity Threats (2015–2024).

It contains more than 3,000 records and includes information such as country, year, attack type, target industry, financial loss, affected users, attack source, vulnerability type, defense mechanism, and incident resolution.

The dataset is synthetic and represents simulated cybersecurity incidents.

## Research Methodology
The research follows a quantitative approach and uses both survey analysis and machine learning experiments.

### Data Preprocessing
The secondary dataset was prepared using Python. The preprocessing steps included:

- Checking for missing values.
- Encoding categorical variables using label encoding.
- Separating the features and target variable.
- Standardizing the data.
- Splitting the dataset into 80% training data and 20% testing data.

### Machine Learning Models
Five machine learning algorithms were evaluated:

- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- K-Nearest Neighbors (KNN)
- Naive Bayes

### Evaluation Metrics
The models were evaluated using four metrics:

- Accuracy
- Precision
- Recall
- F1-score

## Results and Discussion
### Machine Learning Results

Random Forest achieved the highest accuracy among the evaluated models, while K-Nearest Neighbors achieved the lowest.

| Model | Accuracy |
|---|---:|
| Random Forest | 18.67% |
| SVM | 17.67% |
| XGBoost | 16.33% |
| KNN | 15.00% |
| Naive Bayes | 17.83% |

Overall, the models demonstrated weak classification performance. The research discusses the limitations of the synthetic dataset and the lack of detailed technical features as possible factors affecting the results.

### Survey Results
The survey explored the role of human factors in cybersecurity. The findings highlighted the importance of security awareness and training, as well as the risks associated with insider threats.

The research recommends improving employee training and awareness, strengthening access control, and introducing policies and monitoring measures to address insider threats.

## Conclusion and Recommendations
The research demonstrates that predicting cyberattack types using the selected synthetic dataset remains challenging, with all five evaluated models achieving relatively low accuracy.

It also highlights the importance of human factors in cybersecurity, particularly security awareness, regular training, and insider threat prevention.

The recommendations include:

- Conducting regular cybersecurity awareness and training sessions.
- Implementing role-based access control.
- Improving policies and monitoring to address insider threats.
- Using higher-quality datasets with more realistic technical and operational features.
- Evaluating different machine learning models rather than relying on a single algorithm.

## Limitations and Future Improvements
The research has several limitations:

- The machine learning experiments use a synthetic dataset rather than real-world incident data.
- The survey included 37 IT students rather than employees working directly in critical infrastructure organizations.
- The human factors investigation focused mainly on training, awareness, and insider threats.
- The dataset lacks detailed technical information such as network traffic and packet-level features.

Future research could use real-world cybersecurity datasets, collect responses from cybersecurity professionals and critical infrastructure employees, and investigate additional human and technical factors.

## Technologies and Tools Used
- Python
- Pandas
- Scikit-learn
- XGBoost
- Google Forms
- Kaggle

## Project Information
- **Project Type:** Academic Project
- **Course:** Computing Research
- **Semester:** Fall 2025/2026

## License
© 2026 Mohammad Aldeghemat. All rights reserved.
