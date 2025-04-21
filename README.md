# 🧠 AI Resume Analyzer using NLP & Streamlit

An intelligent web application built with **Streamlit** that parses resumes using NLP techniques, analyzes candidate profiles, recommends improvements, and suggests relevant online courses based on skills.

---

## 🚀 Features

- 📄 **Resume Upload & Parsing**: Upload a PDF resume to extract Name, Email, Mobile Number, Education, Experience, and Skills using `pyresparser`.
- 🧠 **Job Role Prediction**: Automatically identifies the best-fit job field like Data Science, Web Development, Android Dev, etc., using skill-based classification.
- 📚 **Course Recommendations**: Displays top online courses tailored to the predicted job field.
- 📊 **Resume Scoring**: Evaluates resumes based on important components like Objective, Projects, Certifications, etc.
- ✅ **Checklist of Suggestions**: Highlights missing sections with recommendations to improve resume quality.
- 🔐 **Admin Login**: Secure admin portal to view and manage parsed resume data stored in MySQL.
- 📈 **Dashboard Insights** (for Admin):
  - Pie chart of user job domains
  - Bar chart of user experience levels
  - Candidate resume stats (Name, Email, Predicted Field, Score)

---

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Backend**: Python, NLP libraries
- **Database**: MySQL
- **NLP Tools**: `pyresparser`, `spacy`, `nltk`, `re`, `pandas`
- **Visualization**: `matplotlib`, `streamlit-aggrid`

---


