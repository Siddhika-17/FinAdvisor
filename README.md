FinAdvisor: AI Agent for Digital Financial Literacy

🚀 Overview

FinAdvisor is an AI-powered digital financial literacy agent built for the IBM Hackathon. It leverages IBM Watsonx and Retrieval-Augmented Generation (RAG) to deliver personalized, multilingual, document-based answers about financial topics, making digital finance education more accessible—especially for underserved communities.


📌 Problem Statement

In a rapidly evolving digital economy, many people—particularly in rural or semi-urban areas—lack the knowledge to make informed financial decisions. Existing resources are often complex or not tailored to individual needs.

FinAdvisor addresses this by:

Understanding natural language queries about finance

Providing real-time, easy-to-understand, and contextual guidance

Educating users on topics like UPI, credit scores, budgeting, loans, investments, fraud prevention, and more

Supporting multiple languages

Delivering interactive and scenario-based learning


🛠️ Technologies Used

IBM Watsonx.ai Studio

IBM Granite Foundation Model (LLM)

Vector Index (RAG)

NLP techniques

IBM Cloud Object Storage

Documents from RBI, NPCI, and other financial authorities


☁️ IBM Cloud Services Used

Watsonx.ai Studio

IBM Granite Model

Watsonx Vector Index

IBM Cloud Lite Account

IBM Cloud IAM

IBM Cloud Object Storage


🎯 Wow Factors

Grounded answers from real RBI/NPCI documents via RAG

Built entirely on IBM Cloud

Handles unrelated queries politely

Multilingual and scalable

Educates users on scams, savings, stock markets, and more


👥 Target End Users

General public

Students and young professionals

Rural and semi-urban populations

NGOs, SHGs, government programs

Customer service centers

Educational institutions


⚙️ Setup Instructions

Clone the repository:

bash
Copy
Edit
git clone https://github.com/Siddhika-17/FinAdvisor.git
Set up IBM Watsonx.ai with necessary credentials

Upload financial documents (PDFs) to IBM Cloud Object Storage

Configure vector index and connect to your LLM

Deploy the AI agent via IBM Watsonx Studio


💬 Quick Start Questions

Users can start with:

"What is UPI?"

"How can I improve my credit score?"

"What is a safe way to invest?"

"Explain budgeting for students."


🔧 Tools & Testing

IBM Watsonx Studio for development and testing

Manual testing with real-life financial queries

Evaluation of response accuracy and politeness for off-topic questions


🌐 Deployment

The agent is deployed via IBM Watsonx and accessible through:

Chat interface

WhatsApp/mobile app (future scope)


📡 API Reference

API endpoints are available post-deployment for integration into mobile/web apps.


📚 Resources Used

RBI Financial Education PDFs

NPCI Guidelines

Financial policy documents from government sources


📈 Results

Successfully deployed AI agent that:

Retrieves grounded responses

Engages in multilingual conversations

Simulates real-life financial scenarios


✅ Conclusion

FinAdvisor empowers individuals with personalized, reliable financial literacy through AI. It bridges the digital divide and supports financial inclusion by using IBM’s cutting-edge cloud and AI technologies.


🌱 Future Scope

Integration with WhatsApp or mobile apps

Voice-driven queries via speech-to-text

Monthly financial summaries

Localized policy updates

Language expansion using Watson Language Translator


🧠 IBM Certifications

This project aligns with IBM SkillBuild and Watsonx Certifications.

🔗 GitHub Repository

GitHub - Siddhika-17/FinAdvisor

