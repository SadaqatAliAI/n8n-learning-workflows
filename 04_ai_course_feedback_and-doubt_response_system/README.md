# 🤖 AI Course Feedback & Doubt Response System

An intelligent **n8n automation workflow** that collects student feedback and course-related doubts through a form, analyzes feedback sentiment using AI, generates personalized responses, sends professional HTML emails via Gmail, and stores all submissions in Google Sheets.

---

## 🚀 Features

* 📝 Accepts student submissions through an n8n Form.
* 📧 Requires an email address for automated responses.
* 💬 Supports:

  * Feedback only
  * Doubt only
  * Feedback + Doubt
* 🔀 Smart routing using Filter nodes.
* 😊 Performs AI-powered sentiment analysis on student feedback.
* 🤖 Generates personalized responses for feedback using an LLM.
* 📚 Generates detailed answers for course-related doubts, including code examples when applicable.
* ✉️ Sends professionally formatted HTML emails via Gmail.
* 📊 Stores student data, feedback, doubts, sentiment, and timestamps in Google Sheets.
* ⚡ Fully automated with no manual intervention.

---

## 🛠️ Tech Stack

* **n8n**
* **Large Language Model (LLM)**
* **AI Sentiment Analysis**
* **Gmail**
* **Google Sheets**
* **HTML Email Templates**

---

## 📧 Automated Email Responses

The workflow automatically sends professionally formatted HTML emails to students.

### 💚 Feedback Response

* Thanks the student for their feedback.
* Adapts the response based on positive or negative sentiment.
* Uses clean HTML formatting for a professional email experience.

### ❓ Doubt Response

* Explains concepts clearly.
* Includes definitions and step-by-step explanations.
* Provides practical examples.
* Includes formatted code blocks for programming-related questions.
* Encourages further learning.

---

## 📊 Data Stored in Google Sheets

Each submission includes:

* 📧 Student Email
* 💬 Feedback
* ❓ Doubt
* 😊 Sentiment Analysis
* 📅 Submission Date & Time

---

## 🎯 Use Cases

* Online Courses
* Coding Bootcamps
* Universities
* Learning Platforms
* AI-Powered Student Support
* Course Feedback Automation

---

## 🌟 Key Highlights

* AI-powered workflow automation
* Intelligent request routing
* Automated sentiment analysis
* Dynamic HTML email generation
* Professional code formatting in emails
* Google Sheets integration
* Scalable and production-ready design

---

## 🚀 Future Improvements

* 📎 File attachment support
* 🌍 Multi-language responses
* 📈 Analytics dashboard
* 🎫 Ticket generation for unresolved doubts
* 🔔 Slack or Discord notifications
* 🧠 Retrieval-Augmented Generation (RAG) for course-specific answers

---

## 👨‍💻 Built With

This project was built to practice **AI Automation**, **Workflow Design**, **Prompt Engineering**, and **n8n** while creating a real-world student support system.

If you found this project interesting, feel free to ⭐ the repository and share your feedback!
