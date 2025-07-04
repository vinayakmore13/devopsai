# 🤖 DevOps Chatbot

A simple chatbot interface built using HTML, CSS, and JavaScript — connected to an `n8n` backend via webhook. It’s containerized with Docker and deployed manually or via Jenkins on AWS EC2. ☁️🐳⚙️

---

## 🔍 What It Does

- 💬 Frontend chatbot interface
- 📤 Sends user messages to `n8n` webhook
- 📦 Dockerized for easy deployment
- ⚙️ CI/CD pipeline using Jenkins (triggered manually)
- ☁️ Hosted on EC2 instance

---

## 📦 Project Structure

📁 devopsai/
├── index.html → Chatbot UI (Frontend)
├── script.js → Chat logic (calls n8n)
├── style.css → Styling
├── Dockerfile → Docker setup
└── Jenkinsfile → CI/CD Pipeline

---

## 🔧 Tech Stack

- 💬 **HTML + CSS + JS** — Chatbot frontend
- 🔗 **n8n Webhook** — Backend automation
- 🐳 **Docker** — Containerization
- 🤖 **Jenkins** — CI/CD automation
- ☁️ **AWS EC2** — Cloud hosting

---

## 🚀 How It Works

1. User sends message 💬
2. Frontend calls `n8n` webhook 🌐
3. `n8n` returns a smart reply 🤖
4. Docker packages the UI 🐳
5. Jenkins auto-deploys on EC2 via pipeline ⚙️

---

## 🛠 Setup Instructions

### 🔹 Build Locally with Docker

```bash
docker build -t simple-chatbot .
docker run -d -p 80:80 simple-chatbot

🔹 Deploy with Jenkins
Jenkins pulls from this repo
Builds image via Dockerfile
Runs container on EC2 using Jenkinsfile

DevOps + Frontend + Automation = ❤️
By Vinayak 🙌






