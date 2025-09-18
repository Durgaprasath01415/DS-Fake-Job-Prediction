# 🧰DS-Fake-Job-Prediction✍🏽📑

### Problem Statement:
    
      In this project, we have build a machine learning model that detects fake job postings based on textual information such as job descriptions, company names, locations, and requirements. The model will help job portals and applicants identify and avoid fraudulent job offers.

### Dataset: Fake Job Postings Prediction
      
      https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction


### Approach:
    
    1. Data Collection
    
      ●	Used the Fake Job Postings dataset from Kaggle.
      
      ●	It contains structured and unstructured features including job titles, descriptions, locations, and labels indicating whether the posting is fake.
   
    2. Data Preprocessing
      
      ●	Handled missing values and irrelevant columns
      
      ●	Cleaned text: remove HTML tags, punctuation, stopwords, and lowercase
      
      ●	Tokenization and lemmatization
    
    3. Feature Extraction
      
      ●	Used TF-IDF vectorization

      ● Used SMOTE to balance the imbalance dependent data
      
      ●	Combine multiple features using a unified feature matrix
    
    4. Model Building and Training
      
      ●	Train models such as Logistic Regression, Support Vector Machines (SVM), Gradient Boosting Classifier and XGBoost Classifier
      
      ●	Have handled class imbalance to the training/validation using imblearn

    5. Model Evaluation
      
      ●	Focus on Precision, Recall, and F1-Score since false positives can severely impact user trust
      
      ●	Plot Confusion Matrix to assess class-wise performance
      
      ●	Consider using ROC-AUC score for final model validation
    
    6. Prediction and Deployment
      
      ●	Test the model on new/unseen job postings
      
### Results: 
      
      Achieved 99% precision and 99% recall on the test set with Support Vector Classification

