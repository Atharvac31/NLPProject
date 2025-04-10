# 📚 Job Description Matching


### Course: NLP (Semester 6) - Pillai College of Engineering

## 📖 Project Overview
This project is part of the Natural Language Processing (NLP) course for Semester 6 students at Pillai College of Engineering. The project, "Job Description Matching" focuses on developing an AI-powered system capable of parsing, analyzing, and extracting key information from resumes to assist in recruitment processes.
**# Job Description Matcherusing NLP 📄🔍

![NLP](https://img.shields.io/badge/Natural%20Language%20Processing-Project-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

Classifying job descriptions and candidate profiles based on relevance. This classification helps recruiters and hiring managers identify the best matches between job openings and candidates, ensuring efficient hiring processes.
## 🎯 Project Abstract
The recruitment process often involves manually matching job descriptions with candidate profiles, a task that can be time-consuming and prone to inefficiencies. This project seeks to develop a Natural Language Processing (NLP)- based job matching system designed to automate the classification of job descriptions and candidate profiles based on their relevance. The system analyzes and compares the textual content of job descriptions and candidate qualifications—including skills, education, and experience—to identify the best matches, improving the efficiency of the hiring process.
By employing TF-IDF vectorization for text representation and Cosine Similarity for measuring relevance, the model assesses how well a candidate’s profile aligns with job requirements. TF-IDF assigns importance to key terms, while Cosine Similarity computes the degree of match between the user input and various job descriptions. The model then ranks job opportunities based on their similarity scores, displaying the most relevant jobs at the top. Additionally, the system allows candidates to upload their resumes, automatically extracting relevant details and matching them against job descriptions for a seamless and accurate classification process.
This lightweight yet effective NLP approach ensures a fast and scalable recruitment process while maintaining high accuracy in candidate-job matching. By automating job classification, the system significantly reduces manual effort, accelerates hiring timelines, and enhances the objectivity of candidate selection. Ultimately, the project aims to streamline hiring workflows, enabling recruiters to efficiently identify top candidates and improve the overall recruitment experience.

---
## 🧠 Algorithms Used
### 📊 Machine Learning Algorithms
- Logistic Regression
- Random Forest
- XGBoost
- Naïve Bayes

### 🔥 Deep Learning Algorithms
- LSTM (Long Short-Term Memory)
- MLP (MultiLayer Perceptron)
- CNN (Convolutional Neural Network)

### 🤖 Language Models
- BERT (Bidirectional Encoder Representations from Transformers)
- RoBERTa

### 📝 Model Performance on Amazon Dataset
                   Model      Features  Test Accuracy
0           Naive Bayes        TF-IDF          0.875
1   Logistic Regression        TF-IDF          0.885
2                   SVM        TF-IDF          0.885
3         Random Forest        TF-IDF          0.850
4           Naive Bayes           BoW          0.885
5   Logistic Regression           BoW          0.885
6                   SVM           BoW          0.885
7         Random Forest           BoW          0.870
8           Naive Bayes  NLP-Features          0.295
9   Logistic Regression  NLP-Features          0.445
10                  SVM  NLP-Features          0.420
11        Random Forest  NLP-Features          0.380
12          Naive Bayes    TF-IDF+NLP          0.875
13  Logistic Regression    TF-IDF+NLP          0.885
14                  SVM    TF-IDF+NLP          0.300
15        Random Forest    TF-IDF+NLP          0.855
16          Naive Bayes  All-Features          0.885
17  Logistic Regression  All-Features          0.885
18                  SVM  All-Features          0.300
19        Random Forest  All-Features          0.860
---
