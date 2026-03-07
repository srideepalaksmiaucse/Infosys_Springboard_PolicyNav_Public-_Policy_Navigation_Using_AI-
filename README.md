# Infosys Springboard – Policy Navigation Using AI

## Project Overview

This project is developed as part of the **Infosys Springboard Virtual Internship 6.0 – Batch 13** under the **Artificial Intelligence domain**.

Public policy documents are often lengthy, complex, and difficult for users to navigate or understand. The objective of this project is to leverage **Artificial Intelligence (AI), Natural Language Processing (NLP), and intelligent document analysis techniques** to simplify the interaction with policy documents.

The system enables users to securely access the platform, upload and analyze documents, and interact with policies through AI-powered tools such as intelligent question answering, summarization, readability analysis, translation, and knowledge graph visualization.

The development of the system has been structured into **three progressive milestones**, each introducing new capabilities and improvements.

---

# Milestone 1 – Secure User Authentication System

## Description

Milestone 1 focused on building the **core authentication infrastructure** required for secure user access. A robust authentication mechanism ensures that only authorized users can interact with the application and access the policy navigation features.

The authentication system was implemented using **Streamlit for the interface** and **JWT (JSON Web Token) for secure session management**. A database-backed system using **SQLite** was used to store and validate user credentials.

This milestone established the foundation for all future system features.

## Features Implemented

- User registration with input validation
- Secure login using JWT authentication
- Dashboard access after successful login
- Forgot password functionality using security question verification
- Session handling for authenticated users
- Error handling for invalid credentials
- Secure credential storage in SQLite database

## Technologies Used

- Python
- Streamlit
- JWT (JSON Web Token)
- SQLite
- Ngrok (used during development for demonstration)

## Outcome

Milestone 1 successfully implemented a **secure and reliable user authentication system**, providing the foundation for further development of advanced policy navigation features.

---

# Milestone 2 – Advanced Security and Readability Analysis Dashboard

## Description

Milestone 2 significantly enhanced the system by introducing **advanced security mechanisms** and a **Readability Analysis Dashboard** for document evaluation.

While Milestone 1 focused on authentication, Milestone 2 strengthened security with **OTP-based verification, password protection mechanisms, and login rate limiting**.

Additionally, the platform introduced analytical capabilities that allow users to **evaluate the readability and complexity of uploaded policy documents**, helping users understand how difficult a document may be to interpret.

## Security Enhancements

The following security features were implemented to improve system reliability and protect user accounts:

- OTP-based authentication for account signup
- OTP verification for password reset
- Secure 6-digit OTP generation with expiration
- Limited OTP verification attempts to prevent misuse
- Password strength validation to enforce strong credentials
- Login rate limiting to prevent brute-force attacks
- Secure password hashing using Bcrypt
- Modern dark-themed interface for improved usability

## Readability Analysis Dashboard

To assist users in evaluating policy documents, the system analyzes uploaded text using established readability formulas.

### Readability Metrics Implemented

- Flesch Reading Ease
- Flesch-Kincaid Grade Level
- SMOG Index
- Gunning Fog Index
- Coleman-Liau Index

These metrics provide insights into the difficulty level of policy documents and help determine the education level required to understand the text.

## Text Statistics

The system also performs detailed text analysis including:

- Word count
- Sentence count
- Character count
- Syllable count

## Visualization

The analysis results are displayed using **interactive dashboards powered by Plotly**, allowing users to visually interpret the complexity and readability of policy documents.

## Technologies Used

- Python
- Streamlit
- SQLite
- JWT
- Bcrypt
- PyPDF2
- Textstat
- Plotly
- SMTP (Email integration for OTP delivery)

## Outcome

Milestone 2 strengthened the platform’s **security architecture** while introducing **analytical capabilities that allow users to better understand policy documents** through readability evaluation.

---

# Milestone 3 – AI Powered Policy Navigation System

## Description

Milestone 3 introduces **advanced Artificial Intelligence capabilities** that transform the platform into an intelligent policy exploration system.

This milestone integrates **Natural Language Processing (NLP), Retrieval Augmented Generation (RAG), Knowledge Graph generation, multi-language support, and document intelligence tools**.

Users can now interact with policy documents in a more intuitive and intelligent way through AI-assisted modules.

---

## AI Policy Assistant (Question Answering System)

The AI Policy Assistant allows users to ask natural language questions related to policy documents.

### Implementation Approach

The system utilizes **Retrieval Augmented Generation (RAG)** architecture:

1. Policy documents are converted into semantic embeddings
2. Embeddings are stored using **FAISS vector search**
3. Relevant document sections are retrieved based on the query
4. AI generates a contextual answer based on retrieved information

### Benefits

- Context-aware policy answers
- Efficient semantic document search
- Intelligent interaction with policy documents

---

## AI Policy Summarizer

This module automatically generates **concise summaries of lengthy policy documents**, helping users quickly grasp key policy points.

### Features

- Extracts the most relevant information from policy text
- Produces simplified summaries
- Helps users quickly understand complex documents

---

## Entity Knowledge Graph

The system extracts entities and relationships from policy documents and visualizes them as a **knowledge graph**.

### Implementation

- Named Entity Recognition using NLP techniques
- Relationship mapping between extracted entities
- Graph generation using **NetworkX**
- Interactive visualization using **PyVis**

### Benefits

- Visual exploration of policy structures
- Improved understanding of relationships between policy concepts

---

## Multi-Language Support

To improve accessibility, the platform supports multiple languages.

### Supported Languages

- English
- Hindi
- Tamil
- Telugu
- Kannada
- Marathi
- Bengali

Users can translate policy content and interact with the system using these languages.

---

## Global Web Search

The platform includes a **web search module** that retrieves external information related to policies.

### Features

- Retrieves relevant web results
- Displays summarized information
- Expands policy research beyond uploaded documents

---

## Readability Analyzer Integration

The readability analysis system introduced in Milestone 2 is fully integrated into the AI platform, allowing users to evaluate policy complexity while interacting with the documents.

---

## Additional User Features

### User Dashboard
Displays system information including newly added policies and user data.

### Activity History
Tracks user actions such as queries, translations, and document analysis.

### Feedback System
Allows users to provide feedback and suggestions for improving the platform.

---

## Technologies Used in Milestone 3

- Python
- Streamlit
- Sentence Transformers
- FAISS
- SpaCy
- NetworkX
- PyVis
- Plotly
- PyPDF
- SQLite
- JWT
- Bcrypt

---

# Project Impact

The **AI Policy Navigation System** aims to improve the accessibility and usability of public policy documents by transforming them into an interactive, AI-powered knowledge platform.

Through intelligent search, summarization, readability analysis, translation, and visualization tools, the system enables users to understand complex policy information more effectively.

The platform demonstrates how **AI-driven technologies can enhance transparency and accessibility in public policy information systems.**

---

# Intern Information

Name: **M Srideepalakshmi**  
Domain: **Artificial Intelligence**  
Program: **Infosys Springboard Virtual Internship**

---

# License

This project is licensed under the **MIT License**.
