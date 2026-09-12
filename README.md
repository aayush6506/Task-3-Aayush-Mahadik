An AI-powered personalized career recommendation system that matches users with relevant job opportunities based on their skills, experience, industry, location, and salary preferences.

## 🚀 Overview

CareerCompass AI helps users discover career opportunities that align with their professional profile.

The system analyzes the user's skills and preferences, compares them with available job profiles, calculates a personalized compatibility score, and ranks the most relevant opportunities.

It also identifies **matching skills** and **skills that the user may need to develop** for each recommendation.

---

## ✨ Features

- 🤖 Personalized job recommendations
- 🧠 AI-based skill similarity matching
- 📊 TF-IDF + Cosine Similarity
- 🎯 Weighted recommendation scoring
- 💼 Experience-level matching
- 🏢 Industry preference matching
- 📍 Location preference matching
- 💰 Salary preference matching
- 📚 Skill-gap analysis
- 📈 Match percentage
- 🖥️ Interactive Streamlit web application

---

## 🧠 How the Recommendation Engine Works

The recommendation engine combines multiple factors to calculate the final score of each job.

### Recommendation Formula

```text
Final Score =
50% Skill Similarity
+ 20% Industry Match
+ 15% Experience Match
+ 10% Location Match
+ 5% Salary Score
