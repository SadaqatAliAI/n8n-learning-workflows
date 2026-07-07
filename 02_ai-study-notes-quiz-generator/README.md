# 📚 AI Study Notes & Quiz Generator

An end-to-end AI-powered n8n workflow that generates comprehensive study notes and a multiple-choice quiz from a user-provided topic. The workflow automatically sends the generated study material to the user's email in two separate emails.

---

## 🚀 Features

* 📝 Accepts a study topic and email address through an n8n Form.
* 🤖 Generates structured AI-powered study notes.
* ❓ Creates a 10-question multiple-choice quiz based on the topic.
* 📧 Sends the study notes to the user's email.
* 📧 Sends the MCQ quiz to the user's email in a separate email.
* ⚡ Fully automated with no manual intervention.

---

## 🛠️ Technologies Used

* n8n
* OpenAI / LLM
* n8n Forms
* Gmail
* Prompt Engineering

---

## ⚙️ Workflow Overview

1. The user submits a study topic and email address.
2. The first LLM generates comprehensive study notes.
3. The second LLM generates a multiple-choice quiz.
4. The Notes Gmail node sends the study notes to the user's email.
5. The MCQs Gmail node sends the quiz to the user's email as a separate message.

---


## 📥 Installation

1. Download the `AI Study Notes & Quiz Generator.json` file.
2. Import it into your n8n instance.
3. Configure your LLM credentials.
4. Configure your Gmail credentials.
5. Activate the workflow.
6. Submit a study topic using the form.

---

## 💡 Use Cases

* 📖 Exam preparation
* 🎓 Student learning
* 💼 Professional certification study
* 📚 Self-learning
* 🧠 Interview preparation
* 🏫 Educational content generation

---

## 📜 License

This project is licensed under the MIT License.
