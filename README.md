# 💊 MedOrder AI

**AI-powered pharmaceutical order automation & call intelligence system**  
Built with n8n, OpenAI API, AssemblyAI, and Google Sheets

---

## 🧬 Overview

**MedOrder AI** is an intelligent automation system designed for pharmaceutical warehouses and medical suppliers that handle a high volume of phone-based orders.

The system combines:

- 🎧 Call processing automation
- 🧠 AI-powered conversation analysis
- 📝 Speech-to-text transcription
- 📦 Structured order extraction
- 📊 Real-time call analytics

---

## 🏥 Architecture (High-Level Flow)

Incoming Call  
↓  
AssemblyAI (Speech-to-Text)  
↓  
OpenAI (AI Order Understanding)  
↓  
Structured Data Extraction  
↓  
Google Sheets Database  
↓  
Analytics & Reporting Layer

---

## ⚙️ Core Systems

### 1️⃣ MedOrder AI (Order Processing Engine)

Main system responsible for handling pharmaceutical orders:

- receives call links or audio recordings
- transcribes audio into text
- extracts medical orders (drugs, quantities, pharmacy info)
- structures data into JSON format
- updates Google Sheets database

![MedOrder AI](/images/medOrderAI.png)

---

### 2️⃣ Call AI Agent 📊

Dedicated AI agent for analytics and insights:

- call volume statistics
- conversation quality analysis
- extraction of key performance metrics
- chat-based reporting interface
- “Get call stats” tool integration

![Call AI Agent](/images//callAIAgent.png)

👉 Used as an internal analytics assistant for operational insights

---

## 🧠 AI Pipeline

- 🎙 Speech-to-Text → AssemblyAI
- 🧠 NLP Processing → OpenAI GPT
- 📦 Data Structuring → AI agents + JSON parsing
- 📊 Storage → Google Sheets
- ⚡ Automation → n8n workflows

---

## 🧪 Problem (Before AI)

Pharmaceutical warehouses face:

- ⏱ delays in order processing
- ❌ human errors in manual data entry
- 💸 high operational costs from call center staff
- 📉 lack of call analytics
- 📞 lost customers due to slow response times

---

## 🚀 Solution (After AI)

MedOrder AI fully automates the process:

- ⚡ instant call processing
- 🧠 AI-powered order understanding
- 📊 automatic analytics generation
- 📦 structured data without manual input
- 💰 reduced operational costs

---

## 📊 Business Impact

### Before (AS-IS)

- 5 call center operators
- slow order processing
- manual data entry
- high operational costs

### After (TO-BE)

- 2 operators + AI system
- ~60% cost reduction
- automated workflows
- scalable without additional staff

---

## 🧠 Key Features

- 🏥 Medical order extraction (drugs, quantities, pharmacy data)
- 🎧 Call transcription (AssemblyAI)
- 🧠 AI order interpretation (OpenAI)
- 📊 Call analytics dashboard (AI Agent)
- 📦 Google Sheets integration
- 🔁 Fully automated n8n workflows

---

## 📈 Key Results

- ⚡ 3–5x faster order processing
- 💰 ~60% reduction in operational costs
- 🎯 Reduced human error rate
- 📊 Real-time call analytics
- 📦 Structured pharmaceutical data pipeline

---

## 🛠 Technologies

- n8n
- OpenAI API
- AssemblyAI
- Google Sheets API
- JavaScript
- JSON
- HTTP Webhooks
- AI Agents

---

## 🔮 Future Improvements

- 🧬 CRM integration for pharmacy systems
- 📞 AI voice agents (fully automated calls)
- 📊 advanced BI analytics dashboard
- 🔄 real-time inventory synchronization
- 🌐 multi-channel communication (Telegram / WhatsApp / calls)

---

## 🎯 Project Presentation

📊 Full MedOrder AI presentation:

👉 [Open Presentation](https://docs.google.com/presentation/d/1K8r66IE1sSUxMFZsY4tbzUR-tgNXoFJT)

## 👨‍⚕️ Author

**Mariana Koval**  
Junior Fullstack Developer & AI Automation Engineer

- 🔗 LinkedIn: https://linkedin.com/in/mariana-koval-fullstack-developer
- 💻 GitHub: https://github.com/Mariana331

---

## 💡 Summary

**MedOrder AI = AI-powered pharmaceutical operations layer**

Transforms raw phone calls into structured medical orders and analytics, reduces manual work, and enables scalable automated pharmacy workflows.
