# Infosys_Springboard_TextMorph_Advanced_Text_Summarization_and_Paraphrasing

# 🧠 TextMorph
##AI-Powered Content Simplification, Summarization & Paraphrasing Suite
Transforming complex content into clear, concise, and accessible communication.

---

## 🔗 Quick Links

| Category          | Link                |
| ----------------- | ------------------- |
| 📽️ Demo Video     | Yes       |
| 🧩 Source Code    | This Repository     |
| 🐳 Docker Support | Yes            |
| 🧠 AI Models      | BART · PEGASUS · T5 |

---

## 📌 Table of Contents

* About the Project
* Problem Statement
* Key Features
* Architecture
* Tech Stack
* Models Used
* Installation
* Usage
* Admin Dashboard
* Datasets
* Screenshots
* License

---

## 📖 About the Project

This project is an AI-powered platform designed to:

* Simplify complex text
* Generate summaries
* Paraphrase content
* Analyze readability

It integrates secure authentication, NLP models, and analytics dashboards into a single system.

---

## 🎯 Problem Statement

Understanding long and complex content is difficult and time-consuming.

This system helps by:

* Improving readability
* Reducing text length
* Rewriting content clearly
* Assisting faster learning

---

## 🚀 Key Features

### 👤 User Features

* 🔐 JWT Authentication with OTP reset
* 📊 Readability Analyzer (Flesch, SMOG, Fog, Coleman)
* ✂️ AI Summarization
* 🔁 Paraphrasing Engine
* 📂 PDF & Text Upload
* 📈 Interactive Charts
* 🧑 Profile Management (email, password, avatar)
* 💬 Chat Interface
* 🕘 History Tracking

---

### 🛠 Admin Features

* 👥 User Management (delete, promote, lock)
* 📊 Analytics Dashboard
* 📈 Model & Feature Usage Tracking
* 🌐 Language Usage Analysis
* ☁️ Feedback Analysis (WordCloud)
* 📥 Data Export (logs, feedback)
* 🔍 Activity Monitoring

---

## 🧩 Architecture

```text
User → Streamlit UI → Backend → AI Models
                     ↓
                 PostgreSQL
```

---

## 🛠 Tech Stack

* Frontend: Streamlit
* Backend: Python
* Database: PostgreSQL
* AI Models: Transformers (BART, PEGASUS, T5)
* Security: JWT, bcrypt
* Visualization: Plotly
* File Handling: PyPDF2

---

## 🤖 Models Used

* BART – Summarization
* PEGASUS – Advanced summarization
* T5 – Paraphrasing
* TextStat / NLTK – Readability analysis

---

## ⚙️ Installation

```bash
git clone https://github.com/PreethBalachandran/Infosys_Springboard_TextMorph_Advanced_Text_Summarization_and_Paraphrasing
cd project
pip install -r requirements.txt
```

---

## 🔐 Environment Setup

Create `.env` file:

```env
JWT_SECRET=your_secret_key
EMAIL_ADDRESS=your_email
EMAIL_PASSWORD=your_password

DB_NAME=your_db
DB_USER=postgres
DB_PASSWORD=postgres
DB_HOST=localhost
DB_PORT=5432
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📝 Usage

1. Login/Register
2. Enter or upload text
3. Choose summarization or paraphrasing
4. View readability results
5. Analyze and download output

---

## 🛡 Admin Dashboard

Admin panel provides:

* User control
* System analytics
* Feature usage tracking
* Feedback insights
* Data export

---

## 📊 Datasets

* Custom dataset for summarization
* Augmented dataset for training

Evaluation Metrics:

* ROUGE
* BLEU
* Readability improvement

---

## 📸 Screenshots

* Login Page
* Dashboard
* Readability Analyzer
* Summarization Output
* Admin Dashboard
* WordCloud

---
👥 Team
Name	Role	Responsibility
Kona Ravi Kumar	Frontend Developer	UI design, Streamlit interface, user experience
Preetha B	Backend Developer	Authentication system, database integration, API logic
Manikanta Tripurani	Documentation	README, reports, project documentation
Kummari Sampath	ML Engineer	Model integration, NLP processing, training & evaluation

## 📜 License

MIT License
Free to use and modify with proper credit.
