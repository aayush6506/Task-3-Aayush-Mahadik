# 💼 AI Career Navigator

### AI-Driven Personalized Job Recommendation Platform

AI Career Navigator is an intelligent job recommendation platform designed to help users explore career opportunities that align with their **skills, experience, industry interests, preferred location, and salary expectations**.

By analyzing user preferences and comparing them with available job opportunities, the system generates personalized recommendations and ranks jobs based on their overall suitability.

---

## 🚀 Live Application

👉 **Launch AI Career Navigator**

https://task-3-aayush-mahadik-gjj92pqd6sekj5fq9xqk4q.streamlit.app/

Experience the application directly through the deployed Streamlit web app.

---

## 🎯 Project Goal

The primary goal of this project is to develop an AI-powered recommendation system that goes beyond traditional job searching by providing customized career suggestions tailored to each user's profile.

Instead of displaying generic job listings, the system evaluates multiple factors and recommends the most relevant opportunities.

The platform provides:

* Personalized job recommendations
* Skill compatibility analysis
* Identification of matching skills
* Skill gap insights
* Recommendation scores
* Detailed recommendation explanations

---

## 🧠 Recommendation Methodology

The recommendation engine combines **skill-based similarity analysis** with **preference-based filtering** to generate accurate job suggestions.

### 1. Skill Similarity Analysis

Job requirements are transformed into numerical feature vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

The user's skill set is then compared with job skill requirements using **Cosine Similarity**, allowing the system to measure how closely a user's skills align with a particular role.

### 2. Preference Evaluation

The system further evaluates job opportunities based on:

* Preferred Industry
* Experience Level
* Desired Location
* Salary Expectations

### 3. Recommendation Scoring

A weighted scoring mechanism is used to rank jobs according to their relevance.

**Final Recommendation Score =**

* 50% × Skill Similarity
* 20% × Industry Match
* 15% × Experience Match
* 10% × Location Match
* 5% × Salary Compatibility

Jobs with higher scores are considered stronger matches and appear higher in the recommendation list.

---

## 🔍 Sample User Profile

Example user inputs:

### Skills

* Python
* SQL
* Machine Learning

### Experience Level

* Entry Level

### Preferred Industry

* Software Development

### Preferred Location

* Bangalore

### Expected Minimum Salary

* ₹80,000

Based on these inputs, the system evaluates available opportunities and recommends the most suitable career options.

---

## ✨ Key Highlights

### 🎯 Personalized Job Matching

Provides job recommendations tailored to individual user preferences and qualifications.

### 🧩 Skill Alignment Analysis

Compares user skills with job requirements to identify strong matches.

### 📈 Skill Gap Detection

Highlights additional skills that can improve eligibility for desired roles.

### 💡 Recommendation Insights

Explains the reasoning behind each recommended job opportunity.

### 📊 Match Score Calculation

Generates a recommendation score for every job listing.

### 🌐 Interactive Web Interface

Offers an easy-to-use and responsive user experience through Streamlit.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy
* Streamlit
* TF-IDF Vectorization
* Cosine Similarity

---

## 📂 Project Directory Structure

```text
AI-Career-Navigator/
│
├── app.py
│   └── Streamlit application and recommendation engine
│
├── AI_Career_Navigator.ipynb
│   └── Model training and experimentation
│
├── job_recommendation_dataset.csv
│   └── Job recommendation dataset
│
├── job_data.pkl
│   └── Processed job information
│
├── tfidf_vectorizer.pkl
│   └── Trained TF-IDF vectorizer
│
├── job_skill_matrix.npz
│   └── TF-IDF skill matrix
│
└── requirements.txt
    └── Project dependencies
```

---

## 👨‍💻 Project Title

**AI Career Navigator**

An AI-powered personalized job recommendation platform developed using **Python, Scikit-learn, and Streamlit** to help users discover career opportunities that best match their skills, preferences, and professional goals.
