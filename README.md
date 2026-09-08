Smart Recruitment Assistant

Machine Learning project that predicts whether a candidate/employee is likely to look for a new job, based on HR demographic and experience data. Helps HR teams prioritize retention efforts.

Dataset
19,158 records, 14 features (education, experience, company info, etc.)

Approach
Data cleaning + preprocessing pipeline (ColumnTransformer, OneHotEncoder, StandardScaler)
Custom encoding for ordinal features (experience, education level, company size) and city frequency encoding
Models: Logistic Regression, Random Forest (tuned)
Best result: ~80% accuracy

Team
Mohamed Alhosiny
Mohamed Ashraf
Mohamed Salah

Live Demo

https://recruitment-assistant--mohamedel7osiny.replit.app/
