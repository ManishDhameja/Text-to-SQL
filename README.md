# 🧠 Text-to-SQL with LLaMA-3 & LangChain

This project is a hands-on LLM-powered Text-to-SQL application that translates natural language questions into SQL queries and retrieves answers from a SQL database. Built using LangChain, LLaMA-3 via Groq API, and Streamlit for the frontend.

---

## 🚀 Features

- Converts natural language to SQL using LLaMA-3
- Executes SQL queries on a local database
- Interactive frontend using Streamlit
- Quick and easy setup

---

## 📦 Install Dependencies

### Using pipenv:
pipenv install
pipenv install streamlit langchain-groq

### Or using pip:
pip install streamlit langchain-groq

### ✅ Note: Make sure you have a .env file with your Groq API key:
GROQ_API_KEY=your_api_key_here

### ▶️ Run the App
streamlit run main.py

---

## 🧪 Example Questions Tested

Here are some sample natural language questions the app handles:

- What are the average marks class-wise?
- Name of the student who scored the highest marks?
- Name of the student who scored the lowest marks?
- Name of the student with the second-highest marks in the DEVOPS course?
- Names of students along with their marks who scored the second-highest, course-wise?

---

## 🛠️ Tech Stack

- **LLaMA-3** (via Groq)
- **LangChain**
- **Streamlit**
- **SQLite** (for demonstration)
