<div align="center">

# PolicyNav – AI Powered Policy Navigation Platform

Transforming complex government policy documents into clear, searchable insights using Artificial Intelligence.

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red)
![AI](https://img.shields.io/badge/AI-NLP-green)
![Vector Search](https://img.shields.io/badge/Vector%20Database-FAISS-orange)
![License](https://img.shields.io/badge/License-MIT-purple)

</div>

---

# Overview

PolicyNav is an AI-powered platform designed to simplify complex government policy documents using modern Artificial Intelligence techniques. The platform integrates Natural Language Processing (NLP), Retrieval Augmented Generation (RAG), vector search, and interactive dashboards to make policy documents easier to understand and explore.

Government policies are often lengthy and written in technical legal language. PolicyNav transforms these documents into accessible information through intelligent tools such as policy summarization, question answering, readability analysis, and multilingual translation.

This project was developed as part of the **Infosys Springboard Internship Program**.

---

# Table of Contents

- Overview  
- Problem Statement  
- Objectives  
- Key Features  
- System Architecture  
- Technology Stack  
- Repository Structure  
- Milestone Breakdown  
- Installation Guide  
- Usage Guide  
- Screenshots  
- Future Improvements  
- Team  
- License  

---

# Problem Statement

Government policy documents often contain complex language and extensive legal terminology that makes them difficult for the general public to understand.

Common challenges include:

- Large document size
- Complex legal language
- Lack of summarized insights
- Limited multilingual accessibility

PolicyNav addresses these challenges by applying AI technologies to analyze, summarize, and explain policy documents in an interactive and user-friendly manner.

---

# Objectives

The primary objectives of this project include:

- Simplifying complex policy documents using AI
- Enabling natural language interaction with policy information
- Generating concise summaries of lengthy documents
- Providing multilingual access to policy content
- Evaluating the readability and complexity of documents
- Visualizing relationships between policy concepts
- Providing analytics dashboards for administrators

---

# Key Features

## User Features

| Feature | Description |
|------|-------------|
| Secure Authentication | User registration and login with OTP verification |
| Policy Document Upload | Upload and process policy documents |
| AI Policy Assistant | Ask questions about policy documents using natural language |
| Policy Summarization | Generate concise summaries of long documents |
| Multi-language Translation | Translate policy information into multiple languages |
| Readability Analysis | Evaluate policy complexity using readability metrics |
| Knowledge Graph Visualization | Display relationships between policy concepts |
| Activity History | Track user interactions with the system |
| Feedback System | Users can submit ratings and suggestions |

---

## Admin Features

| Feature | Description |
|------|-------------|
| User Management | Promote, remove, or lock user accounts |
| Analytics Dashboard | Monitor platform usage and performance |
| Feedback Monitoring | Analyze user feedback |
| Activity Logs | Track system activity |
| Data Export | Export reports and system data |

---

# System Architecture

The following diagram illustrates the overall architecture of the PolicyNav system.

![PolicyNav System Architecture](system_architecture.png)

### Architecture Explanation

The system architecture consists of multiple layers that process policy documents and generate intelligent insights.

**Input Sources**

Policy documents and web-based data sources are collected as input for analysis.

**Document Ingestion and Preprocessing**

This stage extracts text from uploaded documents and performs preprocessing such as cleaning and multilingual translation.

**Data Storage**

Processed documents and embeddings are stored in a vector database and knowledge base using SQLite.

**Embedding Generation**

Text embeddings are generated using transformer-based models such as FLAN-T5 and BART.

**Knowledge Graph Layer**

This layer extracts entities and relationships from policy documents to build a knowledge graph representation of policy information.

**RAG Search Engine**

The Retrieval Augmented Generation pipeline processes user queries and retrieves relevant content using vector search.

**AI Processing and Generation**

The AI engine generates responses such as policy summaries and answers to user queries.

**User Interface**

The platform interface is built using Streamlit and provides dashboards for users and administrators.

**Security and Authentication**

Security features include OTP authentication, JWT token management, and password hashing.

---

# Technology Stack

## Frontend

Streamlit

## Backend

Python

## Artificial Intelligence / NLP

- Hugging Face Transformers
- Sentence Transformers
- SpaCy

## Vector Search

FAISS

## Visualization

- Plotly
- PyVis

## Database

SQLite

## Security

- JWT Authentication
- OTP Verification
- Bcrypt Password Hashing

---

# Repository Structure
<img width="392" height="590" alt="image" src="https://github.com/user-attachments/assets/6c4406c1-2525-44bf-af50-6ac8cbb4edf6" />


Each milestone folder represents a development stage of the project.

---

# Milestone Breakdown

## Milestone 1 – User Authentication System

Implemented a secure authentication system including:

- User registration
- Secure login
- Password recovery
- JWT session management
- User dashboard access

Technologies used:

- Python
- Streamlit
- JWT
- SQLite

---

## Milestone 2 – Security and Readability Dashboard

Enhancements introduced in this milestone:

- OTP-based authentication
- Password strength validation
- Login rate limiting
- Readability analysis dashboard

Readability metrics implemented:

- Flesch Reading Ease
- Flesch-Kincaid Grade Level
- SMOG Index
- Gunning Fog Index
- Coleman-Liau Index

---

## Milestone 3 – AI Policy Navigation System

Advanced AI capabilities introduced:

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

Final milestone features include:

- Admin dashboard
- User profile management
- Activity monitoring
- Data visualization
- Feedback analysis
- Data export functionality

---

# Installation Guide

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


The application will run at:
http://localhost:8501


---

# Usage Guide

1. Register or log in to the platform.
2. Upload a policy document.
3. Use AI tools to analyze the document.
4. Ask questions related to policy content.
5. Generate summaries or translations.
6. View readability analysis and visualizations.

Administrators can monitor system activity using the admin dashboard.

---

# Screenshots

Recommended screenshots to include:

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

- Voice-based interaction with policy documents
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

You are free to use, modify, and distribute this project with proper attribution.

---

