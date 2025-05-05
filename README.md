# 🐰 HoppeR

**AI-enhanced HR support platform with real-time ticketing, intelligent automation, and live chat capabilities.**  
Streamlines employee–HR communication for hybrid and remote workforces.

---

## 🚀 Features

- 📋 Create, update, and track HR support tickets
- 🧠 24/7 AI chatbot (GPTBots) for instant answers to HR FAQs
- 💬 Real-time employee ↔ HR chat via Socket.io
- 🔍 Smart ticket filtering, priority sorting, and status updates
- 🏷️ AI-powered ticket sentiment analysis and routing
- 🛡️ Role-based access for Employees, HR, and Managers
- 📦 Containerized deployment with full CI/CD on Render

---

## 🧰 Tech Stack

| Layer            | Tech Used                     |
|------------------|-------------------------------|
| Frontend         | Angular, TypeScript           |
| Backend API      | Node.js (Express)             |
| AI Integration   | GPTBots (Chatbot), Sentiment Analysis APIs |
| Database         | MongoDB                       |
| Realtime Engine  | Socket.io                     |
| DevOps           | Docker, Render (CI/CD)        |

---

## 💼 Use Case

HoppeR addresses common inefficiencies in HR support systems:
- ❌ Delayed or one-sided HR communication
- ❌ Limited ticket visibility for employees
- ❌ No real-time or automated self-service options

✅ HoppeR solves this with:
- A full ticket lifecycle dashboard  
- Smart auto-assignment & follow-up  
- Instant 24/7 responses via AI  
- Secure, intuitive communication tools

---

## 🖼️ Screenshots

<p float="left">
  <img src="docs/HoppeR SS 1.png" width="45%" />
  <img src="docs/HoppeR SS 2.png" width="45%" />
</p>

<p float="left">
  <img src="docs/HoppeR SS 3.png" width="45%" />
  <img src="docs/HoppeR SS 4.png" width="45%" />
</p>

---

## 🔐 Key Modules
## Ticket Management
- Submit, edit, and resolve tickets

## Chatbot (GPTBots)
- Natural language support for HR policy questions
- Integrated fallback → ticket creation or live chat
- Privacy-aware, no exposure of sensitive data

## Real-time Messaging
- WebSocket-powered chat for fast HR response
- Employee/HR presence awareness
- Offline fallback message system

---

## 🧪 Testing the Live Deployment
- 🔗 Try HoppeR: https://hopper-deployment.onrender.com
- 🧪 Test Credentials:
- Login: EMP004
- Password: 1234

Allow up to a minute for the Render server to spin up ⏳

---

## 🧠 Methodology
- Built as part of a capstone project to explore:
- AI-assisted HR automation
- Real-time enterprise systems
- Scalable containerized deployment
- Hybrid-role UX design (employee + admin)

---

## 📄 License & Attribution
MIT License © 2024 Evan White

> HoppeR is a functional prototype for educational and demonstration purposes.
It represents an intelligent approach to modern HR system design.
