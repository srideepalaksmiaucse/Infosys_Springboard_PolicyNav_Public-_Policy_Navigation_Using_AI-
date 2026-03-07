# AI Policy Navigation System – Milestone 3

## Project Title
PolicyNav – AI Powered Policy Navigation Platform

---

## Overview

Milestone 3 focuses on enhancing the Policy Navigation System with advanced AI features that make government policy documents easier to understand and interact with.

The system integrates Natural Language Processing (NLP), Retrieval Augmented Generation (RAG), and Knowledge Graph techniques to allow users to explore policy information in an intelligent and user-friendly way.

The platform allows users to:

- Ask questions about policies using AI
- Generate summaries of policy documents
- Translate policy content into multiple languages
- Visualize entity relationships through knowledge graphs
- Analyze document readability
- Perform web searches for additional information

The goal is to make complex government policies easier to understand and accessible to users across different linguistic backgrounds.

---

## Supported Languages

The platform supports multiple Indian languages to improve accessibility.

Languages implemented:

- English
- Hindi
- Tamil
- Telugu
- Kannada
- Marathi
- Bengali

Users can ask questions, generate summaries, and translate policy content in these languages.

---

## Core Features Implemented in Milestone 3

### AI Policy Assistant (Multi-Language Q&A)

The AI Policy Assistant allows users to ask questions about policy documents.

Implementation:

- Uses Retrieval Augmented Generation (RAG)
- Policy documents are converted into vector embeddings
- FAISS is used for semantic search
- Relevant information is retrieved and used to generate answers

---

### AI Policy Summarizer

This module generates short summaries of long policy documents.

Features:

- Extracts key information from policy text
- Produces concise summaries
- Supports multiple languages

---

### Entity Knowledge Graph

The system generates a knowledge graph from policy documents.

Implementation:

- Entity extraction using NLP
- Relationship mapping between entities
- Graph generation using NetworkX
- Visualization using PyVis

This allows users to visually understand connections between policy concepts.

---

### Global Web Search

This feature allows users to search the web for additional information related to policies.

Features:

- Retrieves relevant web results
- Displays summarized information
- Helps users gather external context

---

### Language Translator

Users can translate policy content into supported languages.

Features:

- Multi-language translation
- Helps users understand policies in their native language

---

### Readability Analyzer

The readability analyzer evaluates the complexity of policy documents.

Metrics include:

- Sentence complexity
- Word difficulty
- Overall readability score

Results are visualized through interactive dashboards.

---

## User Portal Features

### User Dashboard
Displays:

- Latest policy updates
- Recently added policies
- User information

---

### My Activity History

Tracks user interactions such as:

- Questions asked
- Summaries generated
- Translations performed
- Web searches

---

### Feedback System

Users can submit feedback about the platform including:

- Experience rating
- Suggestions
- Feature requests

---

## Security Features

The system includes security features such as:

- OTP based authentication
- Secure login
- Session management using JWT

---

## Technologies Used

Frontend:
- Streamlit

Backend:
- Python

AI / NLP:
- Sentence Transformers
- SpaCy

Vector Search:
- FAISS

Visualization:
- PyVis
- Plotly

Graph Processing:
- NetworkX

Document Processing:
- PyPDF

Authentication:
- OTP
- JWT

Database:
- SQLite

---

## System Workflow

1. User logs in using OTP authentication  
2. Policy documents are processed and converted into embeddings  
3. Users interact with the system through various modules:

- AI Policy Assistant
- Policy Summarizer
- Knowledge Graph
- Language Translator
- Web Search
- Readability Analyzer

---

## Application Screenshots

User Dashboard  
![Dashboard](screenshots/dashboard.png)

AI Policy Assistant  
![Assistant](screenshots/assistant.png)

AI Policy Summarizer  
![Summarizer](screenshots/summarizer.png)

Knowledge Graph  
![Graph](screenshots/graph.png)

Language Translator  
![Translator](screenshots/translator.png)

Global Web Search  
![Web Search](screenshots/websearch.png)

Feedback System  
![Feedback](screenshots/feedback.png)

Activity History  
![History](screenshots/history.png)

---

## Milestone 3 Outcome

Milestone 3 successfully integrates advanced AI capabilities into the Policy Navigation System.

The system now allows users to:

- Interact with policies using natural language
- Understand complex policy documents through AI summaries
- Access policy information in multiple languages
- Visualize relationships using knowledge graphs
- Analyze readability of policy documents

These improvements make policy information more accessible, understandable, and interactive for users.
