# 🚀 GenAI Internship Screener & ETL Data Pipeline (v1.2)

An autonomous data engineering pipeline designed to ingest, filter, serialize, and log localized professional roles in real-time. This system addresses the inefficiencies of manual board navigation by layering contextual Generative AI filtering over a hardened duplicate protection logic gate.

## 🏗️ System Architecture Overview
<img width="1762" height="728" alt="Screenshot 2026-06-18 113558" src="https://github.com/user-attachments/assets/a626c279-4285-4f3b-becf-aec577bccd3b" />


## 🛠️ Tech Stack & Key Elements
- **Orchestration:** Make.com Advanced Scenarios
- **Language Model Engine:** Google Gemini AI API
- **Data Sourcing:** HTTP RESTful API (SerpApi Engine)
- **Target Database:** Google Sheets API 

## ⚡ Core Operational Features
1. **Deterministic Prompt Ingestion:** Forcing model responses to skip natural prose and conform strictly to programmatic criteria parameters.
2. **JSON Serialization:** Extracting nested payload structures for clean system translations.
3. **Idempotency & Duplicate Guards:** Downstream routing halts if the primary tracking keys match existing rows, minimizing running platform operations.
4. **Formulaic Loading:** Utilizing explicit `=HYPERLINK()` structural scripts on data generation to maintain high UI dashboard cleanliness.
