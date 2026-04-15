
# 🚀 AI Resume Screening System with LangChain & LangSmith

## 📌 Overview
This project is an AI-powered Resume Screening System built as part of the **Data Science Internship – February 2026**.

The system evaluates candidate resumes against a given job description using **LLMs (Groq)** and provides:
- ✅ Skill Extraction
- ✅ Resume Matching
- ✅ Candidate Scoring (0–100)
- ✅ Explainable AI reasoning
- ✅ LangSmith tracing for monitoring & debugging

---

## 🎯 Objective
To build a modular LLM pipeline that:
- Extracts relevant information from resumes
- Matches it with job requirements
- Assigns a score
- Provides a clear explanation for the evaluation

---

## 🛠️ Tech Stack
- Python
- LangChain (LCEL)
- LangSmith (Tracing)
- Groq API (LLM - LLaMA3)
- VS Code / Jupyter Notebook

---

## ⚙️ Pipeline Flow

Resume → Skill Extraction → Matching → Scoring → Explanation


---

## 🧠 Features

### 1. Skill Extraction
Extracts:
- Skills
- Experience
- Tools

### 2. Matching Logic
- Compares resume with job description
- Identifies:
  - Matching skills
  - Missing skills

### 3. Scoring System
- Score range: **0–100**
- Based on:
  - Skill match percentage
  - Missing critical skills

### 4. Explainability
- Provides reasoning for each score
- Ensures transparency

---

## 🔍 LangSmith Tracing (Mandatory Feature)
- Tracks each pipeline step
- Helps debug outputs
- Shows:
  - Extract → Match → Score → Explain

---

## 🔑 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/your-username/resume-screening-ai.git
cd resume-screening-ai
```
### 2. Create Virtual Environment
```
python -m venv venv
venv\Scripts\activate
```
### 3. Install Dependencies
```
pip install -r requirements.txt
```

## ▶️ Run the Project
python main.py

## 📊 Sample Output
--- Resume 1 ---
Score: 90
Explanation: Strong match with most required skills...

--- Resume 2 ---
Score: 60
Explanation: Partial match, missing key skills...

--- Resume 3 ---
Score: 20
Explanation: Weak match, lacks required skills...

## 🧪 Test Data
3 resumes:
Strong candidate
Average candidate
Weak candidate
1 job description (Data Scientist role)
⚠️ Important Rules Followed
❌ No hardcoded outputs
❌ No hallucinated skills
✅ Modular pipeline
✅ LangSmith tracing enabled
✅ Explainable AI output

## 🌟 Key Learnings
Building production-level LLM pipelines
Prompt engineering for structured outputs
Debugging using LangSmith
Designing explainable AI systems

## 📌 Future Improvements
Add UI (Streamlit)
Improve scoring logic with weights
Add PDF resume parsing
Use vector database for better matching

## 📢 Final Note

This project demonstrates how GenAI can be used in real-world hiring systems to automate and improve resume screening efficiently 🚀
