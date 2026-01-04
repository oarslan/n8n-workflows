# My n8n Workflows 🚀

A collection of my custom automation workflows built with [n8n](https://n8n.io/).

## 📂 Workflows

### 1. [Gold AI Analyst](./gold-ai-analyst) 📉
An intelligent financial analyst agent that:
*   Tracks real-time gold prices (Gram, ONS).
*   Uses Anthropic's Claude to generate market commentary in Turkish.
*   Sends daily email reports.

### 2. [Price Tracker](./price-tracker) 🏷️
An automated shopping assistant that:
*   Tracks product prices on e-commerce sites.
*   Compares current price with target price and history.
*   Sends email alerts for discounts or when targets are hit.

### 3. [Github Trend Hunter](./github-trend-hunter) 🏹
A weekly newsletter generator that:
*   Finds trending GitHub repositories.
*   Summarizes them using AI.
*   Sends a formatted email report.

### 4. [Pgvector Rag Agent](./pgvector-rag-agent) 🤖
A RAG (Retrieval-Augmented Generation) agent that:
*   Uses **PostgreSQL (pgvector)** as a vector database.
*   Uses **Google Gemini** for embeddings and chat.
*   Performs semantic search on documents and answers questions in natural language.

## 🛠️ Setup

To use these workflows:
1.  Import the `.json` file from the respective folder into your n8n instance.
2.  Configure the necessary credentials (API keys, Google Sheets, etc.) as described in each project's README.

---
*Created by Özlem Arslan*
