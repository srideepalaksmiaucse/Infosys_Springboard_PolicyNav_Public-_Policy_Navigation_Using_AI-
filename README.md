# 💠 PolicyNav
### AI-Powered Policy Navigation Platform

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![AI](https://img.shields.io/badge/Artificial_Intelligence-NLP-purple?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Vector_Search-FAISS-orange?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red?style=for-the-badge&logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### Transforming Complex Government Policies into Clear, Searchable Insights

</div>

---

# 🌟 Project Overview

**PolicyNav** is an AI-powered platform designed to simplify complex government policy documents using **Natural Language Processing (NLP)** and **Retrieval Augmented Generation (RAG)**.

The platform allows users to interact with policies intelligently through:

- AI-powered question answering  
- Policy summarization  
- Readability analysis  
- Multi-language translation  
- Knowledge graph visualization  
- Administrative analytics dashboards  

📌 Developed as part of the **Infosys Springboard Internship Program**

---

# 🎬 Demo Preview

<div align="center">

<img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" width="650">

</div>

This demo illustrates the system workflow:

1️⃣ User authentication  
2️⃣ Policy document upload  
3️⃣ AI processing and embeddings  
4️⃣ Question answering  
5️⃣ Analytics and visualization  

---

# 📚 Table of Contents

- Project Motivation  
- Key Features  
- System Architecture  
- AI Processing Pipeline  
- Security Architecture  
- Technology Stack  
- Repository Structure  
- Installation Guide  
- Usage Guide  
- Data Processing Workflow  
- Screenshots  
- Future Roadmap  
- Team  
- License  

---

# 🎯 Problem Statement

Government policy documents are often:

- Long and complex
- Written in legal language
- Difficult for citizens to interpret

Manual policy interpretation requires **significant time and expertise**.

### Our Solution

PolicyNav uses **AI and NLP technologies** to:

✔ simplify policy documents  
✔ generate summaries  
✔ answer policy questions  
✔ support multilingual accessibility  
✔ visualize policy relationships  

This enables **better transparency and accessibility of policy information**.

---

# 🚀 Key Features

## 👤 User Features

| Feature | Description |
|------|-------------|
| 🔐 Secure Authentication | JWT login with OTP verification |
| 📄 Policy Upload | Upload policy documents |
| 🤖 AI Policy Assistant | Ask questions in natural language |
| ✂️ Policy Summarization | Extract key insights |
| 🌍 Language Translation | Multi-language policy support |
| 📊 Readability Analyzer | Evaluate policy complexity |
| 🧠 Knowledge Graph | Visualize relationships |
| ⭐ Feedback System | User rating and suggestions |
| 🕘 Activity History | Track user interactions |

---

## 🛡 Admin Features

| Feature | Description |
|------|-------------|
| 👥 User Management | Promote, remove or lock users |
| 📊 Analytics Dashboard | Platform usage monitoring |
| 💬 Feedback Analysis | WordCloud visualization |
| 📜 Activity Logs | System monitoring |
| 📥 Data Export | Export reports |

---

# 🧩 System Architecture

```mermaid
graph TD

User[User Interface - Streamlit]

Auth[Authentication Layer]
OTP[OTP Verification]
JWT[JWT Token Manager]

Doc[Document Upload]
Process[Text Processing]

Embed[Sentence Transformers]
VectorDB[FAISS Vector Database]

RAG[RAG AI Engine]
Answer[AI Generated Response]

Graph[Knowledge Graph Generator]
Analytics[Analytics Dashboard]

User --> Auth
Auth --> OTP
Auth --> JWT

JWT --> Doc
Doc --> Process
Process --> Embed

Embed --> VectorDB
VectorDB --> RAG

RAG --> Answer

Process --> Graph
Answer --> Analytics
Graph --> Analytics

# License

This project is licensed under the **MIT License**.
