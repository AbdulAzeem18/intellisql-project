# IntelliSQL: Intelligent SQL Querying with LLMs Using Gemini Pro

---

## 📌 Project Overview
IntelliSQL is an AI-powered SQL querying system that allows users to interact with databases using natural language. Instead of writing complex SQL queries manually, users can ask questions in plain English, and the system converts them into valid SQL queries using Google Gemini Pro (LLM) and executes them on a SQLite database.

---

## 🎯 Key Features
- Convert natural language questions to SQL queries
- Powered by Gemini Pro LLM
- Automatic SQL generation
- SQLite database integration
- Streamlit interactive web UI
- Query execution with result display
- Syntax assistance & optimization support

 ---
 
## 🧠 Use Cases
Intelligent Query Assistance:
- Helps users craft SQL queries easily
- Suggests correct SQL syntax
- Reduces manual effort

Data Exploration:
- Ask questions in plain English
- Retrieve filtered data instantly
- Discover insights quickly

---

## 🏗️ Architecture Flow
1. User enters question in UI
2. Input sent to backend
3. Gemini Pro processes prompt
4. Text converted to SQL
5. SQL runs on SQLite DB
6. Results displayed

---

## 🗂️ Project Structure
IntelliSQL/
app.py
sql.py
data.db
requirements.txt
.env
README.md

---

## ⚙️ Requirements
streamlit
google-generativeai
python-dotenv

---

## 🔑 API Key Setup
Create .env file:
GOOGLE_API_KEY=your_api_key_here

---

## 🗄️ Database
SQLite demo database with Students table.

---

## ▶️ Run App
pip install -r requirements.txt
streamlit run app.py

---

## 🔮 Future Enhancements
- Multi-DB support
- Charts & visualization
- Query explanation
- Query history 
---





