# 🏨 AI Hospitality Intelligence Platform (End-to-End Competitor & Marketing Ecosystem)

A full-stack, AI-driven market intelligence and proposal generation platform designed specifically for the luxury hospitality industry. This project seamlessly integrates **n8n Automation**, **Vector Databases (Pinecone)**, **AppSheet (Backend)**, and a modern **Web App (Base44)** to create a 360-degree AI marketing assistant.

## 🚀 System Architecture & Ecosystem

This platform operates through three main layers:

### 1. 🕷️ Data Acquisition Layer (n8n Automated Pipelines)
The system runs 3 parallel automated workflows to gather and analyze market data:

<img width="1267" height="372" alt="Screenshot 2569-04-06 at 00 52 45" src="https://github.com/user-attachments/assets/fcf477e3-fe79-4862-ba8a-4da431be1fcc" />

- **Pipeline A (Social Media Monitor):** Scrapes daily Facebook/IG posts from competitors, analyzes trends, and sends HTML email reports. It also powers a Telegram AI Agent ("Luxury Hotel Marketing Specialist") that acts as an interactive consultant.

<img width="1025" height="280" alt="Screenshot 2569-04-06 at 00 55 29" src="https://github.com/user-attachments/assets/9088cb1a-252c-42db-9d62-5c652527725c" />

- **Pipeline B (Tourism News & Event Impact):** Reads RSS feeds for regional tourism news (Hua Hin, Chiang Mai, Phuket) and uses an LLM to evaluate the "Impact Score" (Opportunity/Threat) and Sentiment.

<img width="1034" height="308" alt="Screenshot 2569-04-06 at 00 47 35" src="https://github.com/user-attachments/assets/692895f6-ff13-4491-adeb-833b66023639" />

- **Pipeline C (Ad Campaigns Tracker):** Automatically extracts active Facebook Ads from competitors and uses AI to decode their Strategy, Key Offers, and Marketing Tone.

### 2. 🧠 AI Brain & Storage Layer (Pinecone & Google Sheets)
All scraped data, news analyses, and ad strategies are embedded and stored in a **Pinecone Vector Database**. This allows the AI agents to perform RAG (Retrieval-Augmented Generation) to give highly accurate, data-driven marketing advice. Structured logs are maintained in Google Sheets.

### 3. 💻 Application & Interface Layer

<img width="1440" height="778" alt="Screenshot 2569-04-06 at 00 58 14" src="https://github.com/user-attachments/assets/0b765896-713b-460d-a9a1-7e22decb7e03" />

- **Backend (AppSheet):** Acts as the operational hub and **AI Proposal Generator**, turning the raw competitor data into actionable marketing proposals.

<img width="1440" height="778" alt="Screenshot 2569-04-06 at 01 00 51" src="https://github.com/user-attachments/assets/d014791e-db17-48c5-a158-9ceb8d3bb5dd" />

- **Frontend (Base44):** A custom-built, user-friendly Web App interface that allows hotel staff to interact with the insights and generated proposals seamlessly.
- **Telegram AI Agent:** A conversational interface for instant marketing consultations based on real-time vector data.

## ✨ Key Business Impact
- Eliminates hours of manual competitor research.
- Identifies market gaps and seasonal opportunities automatically.
- Generates ready-to-use, hyper-targeted marketing content and proposals based on real competitor data, not just AI hallucinations.

## 🛠️ Tech Stack & Integrations
- **Automation Engine:** n8n (Advanced workflows with Split in Batches, APIs, and Sub-workflows)
- **Data Scraping:** Apify API (Facebook & Instagram Scrapers)
- **AI & LLMs:** OpenAI (GPT-4o / GPT-5-mini) + LangChain Agents
- **Vector DB:** Pinecone
- **Backend & Logic:** AppSheet / Google Sheets
- **Frontend App:** Base44 (Vibe Coding UI)
- **Interfaces:** Telegram API, Gmail API

---
*Developed by Non Poramat | Showcasing Enterprise-grade Citizen Development and AI Integration*
