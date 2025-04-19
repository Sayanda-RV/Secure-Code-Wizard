# Secure-Code-Wizard
# 🛡 Secure Code Analyzer

A web app that analyzes code for security vulnerabilities and suggests safe versions using AI.

---

## 🚀 Features

- 🖥 Built with React.js frontend and Flask backend  
- 💻 Supports multiple languages (Python, JS, TS, C++, Java)  
- 🔍 “Analyze Code” scans for vulnerabilities via backend  
- 📊 Displays security score + issues with line numbers  
- 🔐 “Generate Secure Code” uses OpenAI API to fix code  
- 📋 Secure output shown with copy-to-clipboard support  

---

## 🧰 Tech Stack

- 🧑‍💻 React.js (frontend UI)
- 🐍 Flask (Python backend)
- 🔍 Regex scanner for static vulnerability checks
- 🤖 OpenAI GPT API (secure code generation)
- 📡 Axios for frontend-backend communication
- 🧪 Postman for API testing

---

## ⚙ Implementation Flow

- 🔘 “Analyze Code” sends code + language via POST to Flask
- 🐍 Flask sends input to scanner.py for regex vulnerability checks
- 📊 Score + issues with line numbers returned to UI
- ✨ “Generate Secure Code” triggers OpenAI GPT via backend
- 🧠 GPT returns rewritten secure version
- 📋 Read-only textarea shows secure code with copy option
- 📦 Backend tested using Postman (for JSON response validation)

---
