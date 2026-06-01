# AI-Powered-Job-Recommendation-System

## Kaggle Notebook 
https://www.kaggle.com/code/naiyakhalid/ai-powered-job-recommendation-system?scriptVersionId=323788069

## Project Overview
This project develops a content-based job recommendation system that matches user skills and interests with relevant job opportunities.

Using Natural Language Processing (NLP) techniques, job descriptions are transformed into numerical representations and compared with a user profile. Jobs are then ranked according to similarity scores, allowing personalized recommendations to be generated.

The project was developed using over 120,000 real-world LinkedIn job postings.

## Business Problem

Job seekers often face thousands of available opportunities and may struggle to identify roles that match their skills and career goals.

This project addresses that challenge by creating an AI-driven recommendation engine capable of identifying the most relevant jobs based on a candidate's profile.

## Dataset

LinkedIn Job Postings Dataset

* Over 120,000 job postings
* Job titles
* Job descriptions
* Company information
* Location information
* Experience levels

Source: Kaggle

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorization
* Cosine Similarity
* Matplotlib
* Jupyter Notebook

## Methodology

### 1. Data Preparation

* Loaded LinkedIn job postings dataset
* Selected relevant text features
* Removed missing descriptions
* Prepared job descriptions for NLP processing

### 2. User Profile Creation

A sample candidate profile was created containing skills related to data science and analytics.

Example skills:

* Python
* SQL
* Machine Learning
* Power BI
* Statistics
* Forecasting

### 3. Text Vectorization

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert job descriptions and user profiles into numerical vectors.

### 4. Similarity Calculation

Cosine Similarity was used to measure how closely each job matched the user profile.

### 5. Recommendation Generation

Jobs were ranked based on similarity scores and the highest-ranking opportunities were recommended.

## Results

The recommendation engine successfully identified data-related opportunities including:

* Power BI Developer
* Data Analyst
* Business Intelligence Analyst
* Analytics-focused positions

Results demonstrate how NLP techniques can support personalized job discovery and recommendation systems.

## Future Improvements

* User authentication and profile management
* Skill extraction using Named Entity Recognition (NER)
* Semantic search using embeddings
* Deep learning recommendation models
* Real-time recommendation API

## Author
Naiya Khalid
Master's Student in Data Science
Porto, Portugal

# **Want to Connect** 
[Linkedin](https:www.linkedin.com/in/naiya-khalid-纳亚-510981130) 🔗
[Kaggle](https:https://www.kaggle.com/naiyakhalid) 📊
[GitHub](https://github.com/naiyakhalid) 
