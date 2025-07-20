# 🧠 AI Resume Screener

An AI-powered tool to help HR teams upload, screen, and shortlist candidate resumes automatically — complete with analytics, chatbot interface, and email integration.

---

## 📌 Problem Statement

Build a chatbot to screen resumes, shortlist top candidates, and manage initial interactions.
---

## 🛠 Tech Stack

### 🖥 Frontend

React.js – Interactive UI and chatbot interface

Tailwind CSS – Styling and layout

EmailJS – Send email invites directly from the frontend

Chart.js + react-chartjs-2 – Data visualization for resume analytics


### 🧠 Backend

Python – Resume parsing & matching logic

Flask – RESTful backend for handling resume & JD processing

spaCy – Custom-trained NLP model for extracting key sections (NER)

scikit-learn – Resume scoring based on similarity

PyPDF2 / python-docx – Reading resumes in PDF and DOCX formats

pandas – For data handling and scoring logic



---

## 📄 Features

### ✅ 1. Multi-Resume Upload

Upload multiple resumes (PDF/DOCX)

Automatically parses and stores resume details


### 🧠 2. NLP-Based Resume Parsing

Custom-trained spaCy model

Extracts: Name, Education, Experience, Skills


### 📝 3. Job Description Parsing

Paste or type JD dynamically

Extracts required skills, education, and experience


### ⚖ 4. Resume Scoring System

Weighted scoring based on skill/edu/exp match

Custom weightage input by HR (out of 100)


### 💬 5. AI Chatbot Interface

Interact with the tool via chatbot

View top candidates, shortlist, and invite via email


### 📧 6. Email Integration

Select and send personalized invites to candidates


### 📊 7. Resume Analytics Dashboard

Total resumes processed

Score distribution, skill frequency, cutoff %


## 🧪 Future Scope

Voicebot version of the chatbot

PDF export of shortlist reports

Integration with ATS systems

Candidate feedback scoring

## 🚀 How to Run the Project

### 1. Backend (Flask API)

```sh
cd backend
python app.py
```

### 2. Frontend (React App)

```sh
cd frontend
npm install   # Only needed once, or if dependencies change
npm start
```

If you see an error about `react-scripts` not found, make sure your `package.json` has:

```
"react-scripts": "^5.0.1"
```

and run `npm install` again in the `frontend` directory.

### 3. (Optional) Run Both Frontend & Backend Together

If you want to run both with a single command from the project root, install `concurrently`:

```sh
npm install concurrently --save-dev
```

Then use:

```sh
npm start
```

This will start both the backend and frontend (if your root `package.json` is set up for it).

---

## 🤝 Author

Ranjan Kumar

---

