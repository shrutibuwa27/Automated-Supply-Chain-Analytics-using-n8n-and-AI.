# Supply Chain Insights AI with n8n

## 🧠 What Problem This Solves
Manual analysis of supply chain data is slow and inconsistent. This project automates
data ingestion, AI-driven analysis, and insight generation.

## 🛠 Solution Overview
- n8n workflow automates data retrieval and processing
- AI (Quadratic / LLM) analyzes and generates insights
- Outputs structured insights ready for business decisions

## 🔍 Architecture
![Workflow Diagram](docs/workflow_diagram.png)

## 🧩 How It Works
1. **Trigger:** Data ingest from CSV/API
2. **Transform:** n8n nodes clean + forward to AI
3. **AI Analysis:** Quadratic/LLM evaluates patterns/trends
4. **Output:** Generates insight report

## 🚀 Run It Locally
1. Clone the repo
2. Import JSON into n8n
3. Create `.env` from `.env.example`
4. Start n8n

## 🎯 Tech Stack
- n8n
- Quadratic / AI service
- CSV/Database (your chosen data source)
