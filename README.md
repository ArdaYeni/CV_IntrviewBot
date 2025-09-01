<img width="1894" height="823" alt="image" src="https://github.com/user-attachments/assets/508acf63-f8f6-424c-bbc6-ba457d46b88e" />
# Career Conversation Bot

An interactive chatbot that analyzes your CV and answers questions related to your career path, skills, and experiences.  
This project is available as a live demo on **Hugging Face Spaces**:  
👉 [Career Conversation Bot on Hugging Face](https://huggingface.co/spaces/ardaye/career_conversation)

---

## 🚀 Overview
The **Career Conversation Bot** is designed to help simulate interview scenarios and career-related Q&A by parsing a CV/resume.  
It allows users to:
- Ask questions about their past experience and education.
- Explore strengths and areas of expertise.
- Prepare for interviews by practicing realistic questions.
- Gain quick insights into how their CV can be interpreted.

---

## ⚙️ Features
- **CV Analysis**: Reads and processes a CV to extract key information (education, skills, projects, and work experience).
- **Career Q&A**: Answers custom questions about the CV.
- **Interactive Interface**: Deployed on Hugging Face Spaces for easy access.
- **Privacy-Friendly**: Local `.env` file for API keys and secrets (never pushed to GitHub).

---

## 🛠️ Tech Stack
- **Python** (backend logic)
- **Streamlit/Gradio** (UI, depending on implementation)
- **Hugging Face Spaces** for deployment
- **NLP Models** (to parse and answer questions)

---

## 📂 Project Structure
```bash
career-conversation-bot/
│── app.py              # Main app entry point
│── requirements.txt    # Python dependencies
│── .env.example        # Environment variable template (no real secrets!)
│── .gitignore          # Ensures .env and other sensitive files are not pushed
│── README.md           # Project documentation
