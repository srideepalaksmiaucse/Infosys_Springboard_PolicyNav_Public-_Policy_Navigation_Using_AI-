<div align="center">

# PolicyNav
### AI-Powered Policy Navigation Platform

Transforming complex government policy documents into clear, searchable insights using Artificial Intelligence.

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red)
![AI](https://img.shields.io/badge/AI-NLP-green)
![Vector Search](https://img.shields.io/badge/Vector%20Database-FAISS-orange)
![License](https://img.shields.io/badge/License-MIT-purple)

</div>

---

# Overview

PolicyNav is an AI-powered platform designed to simplify complex government policy documents using Natural Language Processing (NLP), Retrieval Augmented Generation (RAG), and intelligent analytics dashboards.

Government policies are often long and difficult to understand. PolicyNav transforms these documents into accessible information through AI-powered tools such as summarization, question answering, readability analysis, and multilingual translation.

This project was developed as part of the **Infosys Springboard Internship Program**.

---

# Table of Contents

- Overview  
- Problem Statement  
- Key Features  
- System Architecture  
- Technology Stack  
- Repository Structure  
- Milestones  
- Installation  
- Usage  
- Screenshots  
- Future Improvements  
- Team  
- License  

---

# Problem Statement

Government policy documents often contain complex language and extensive legal terminology that makes them difficult for the general public to understand.

Common challenges include:

- Long and complex documents
- Difficult legal terminology
- Lack of simplified explanations
- Limited accessibility for non-technical users

PolicyNav addresses these issues using Artificial Intelligence to automatically analyze and interpret policy documents.

---

# Key Features

## User Features

| Feature | Description |
|------|-------------|
| Secure Authentication | User registration and login with OTP verification |
| Policy Upload | Upload and process policy documents |
| AI Policy Assistant | Ask questions about policies using natural language |
| Policy Summarization | Generate concise summaries |
| Language Translation | Translate policies into multiple languages |
| Readability Analysis | Evaluate document complexity |
| Knowledge Graph | Visualize relationships between policy concepts |
| Feedback System | Users can submit feedback |
| Activity History | Track user interactions |

---

## Admin Features

| Feature | Description |
|------|-------------|
| User Management | Promote, remove, or lock user accounts |
| Analytics Dashboard | Monitor platform usage |
| Feedback Monitoring | Analyze user feedback |
| Activity Logs | Track system activities |
| Data Export | Export reports and logs |

---

# System Architecture

The platform consists of the following components:

1. User Interface (Streamlit)
2. Authentication System
3. Document Processing Module
4. AI Processing Engine
5. Vector Database
6. Knowledge Graph Module
7. Analytics Dashboard

System workflow:

User → Authentication → Document Upload → Text Processing → Embedding Generation → Vector Database → AI Retrieval → Response Generation → Visualization

---

# Technology Stack

## Frontend
- Streamlit

## Backend
- Python

## Artificial Intelligence / NLP
- Sentence Transformers
- SpaCy

## Vector Database
- FAISS

## Visualization
- Plotly
- PyVis

## Database
- SQLite

## Security
- JWT Authentication
- OTP Verification

---

# Repository Structure
PolicyNav
│
├── milestone1
│ ├── README.md
│ └── springboard_Login_Page.ipynb
│
├── milestone2
│ ├── ReadMe.md
│ ├── app.ipynb
│ └── otp_authentication.ipynb
│
├── milestone3
│ ├── Final_Milestone3.ipynb
│ └── README.md
│
├── milestone4
│ ├── Milestone4.ipynb
│ └── README.md
│
├── LICENSE
└── README.md



Each milestone folder represents a stage in the development of the project.

---

# Milestones

## Milestone 1 – User Authentication System

Implemented a secure authentication system with:

- User signup
- Secure login
- Password recovery
- Session handling using JWT
- Dashboard access

Technologies used:

- Python
- Streamlit
- JWT
- SQLite

---

## Milestone 2 – Security and Readability Dashboard

Enhancements introduced:

- OTP-based authentication
- Password strength validation
- Login rate limiting
- Readability analysis dashboard

Readability metrics used:

- Flesch Reading Ease
- Flesch-Kincaid Grade Level
- SMOG Index
- Gunning Fog Index
- Coleman-Liau Index

---

## Milestone 3 – AI Policy Navigation System

Added advanced AI capabilities including:

- AI Policy Assistant using RAG
- Policy summarization
- Knowledge graph visualization
- Web search integration
- Language translation
- Readability analysis

Technologies used:

- Sentence Transformers
- FAISS
- SpaCy
- NetworkX
- PyVis

---

## Milestone 4 – Admin Analytics and User Dashboard

Final milestone introduced:

- Admin dashboard
- User profile management
- Activity monitoring
- Data visualization
- Feedback analysis
- Data export functionality

---

# Installation

## Prerequisites

- Python 3.9 or higher
- Git

---

## Clone the Repository
git clone <repository-url>
cd PolicyNav


---

## Install Dependencies
pip install streamlit
pip install sentence-transformers
pip install faiss-cpu
pip install plotly
pip install textstat


---

## Run the Application


streamlit run app.py


The application will be available at:
http://localhost:8501

---

# Usage

1. Register or log in.
2. Upload a policy document.
3. Use AI tools to analyze the document.
4. Ask questions related to the policy.
5. Generate summaries.
6. Translate policy content.
7. Explore readability analysis and visualizations.

Admin users can monitor system activity through the admin dashboard.

---

# Screenshots

Example screenshots to include:

- Login Page
- Signup Page
- OTP Authentication
- User Dashboard
- AI Policy Assistant
- Readability Analysis Dashboard
- Knowledge Graph Visualization
- Admin Analytics Dashboard

---

# Future Improvements

Possible future enhancements include:

- Voice-based interaction with policies
- Mobile application support
- Policy recommendation system
- Real-time government policy updates
- Integration with external policy databases

---

# Team

| Name | Role |
|-----|------|
| M Srideepalakshmi Muruganantham | AI Developer |
| Shambhavi Jha | Backend Developer |
| Mainuddeen | AI Engineer |
| Bhuvaneshwar Reddy Mandadapu | Backend Developer |
| Mansi Chaturvedi | Data Processing |
| Raam Prakash S | System Integration |
| Arjun L Nair | Platform Development |

---

# License

This project is licensed under the MIT License.

---
