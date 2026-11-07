# Hi, I'm Mahi Sharma

**AI Engineering student (B.E. AI & ML, Atria Institute of Technology, 2027) based in Bengaluru.**
I build LLM-powered applications and ML systems with Python and FastAPI , and I'm looking for AI / ML Engineer internships.

[LeetCode](https://leetcode.com/u/Mahi31sh/) · [LinkedIn](https://www.linkedin.com/in/mahi-sharma-31sh/) · [Email](mailto:mahisharma31102004@gmail.com)

---

## What I work on

- LLM applications: natural-language interfaces over structured data, with guardrails on model output
- Applied ML: fraud and risk modelling, drift monitoring, explainability (SHAP)
- Backend engineering: REST APIs, auth, databases, tests
- Security-oriented tooling: phishing detection, log analysis, threat-intel lookups

## Featured projects

### [QueryPilot](https://github.com/Mahi31sh/QueryPilot)
Natural-language-to-SQL analytics app. A question is matched against the database schema, the relevant tables go to an LLM (Groq API) to generate SQL, and the result comes back as a table or chart.
- SQL guardrails: single statement, SELECT-only, keyword denylist, enforced row limit, and read-only transaction execution
- Retry loop that feeds database errors back to the LLM for correction
- JWT auth, query history, React + TypeScript dashboard with bar, line, pie and KPI views
- **Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, React, TypeScript, Tailwind, Groq API

### [Cross-Merchant Network Risk Engine (RiskMesh)](https://github.com/Mahi31sh/Cross-Merchant-AI)
Built for the Razorpay AI Buildathon (Track 02, AI Risk Manager). Links one actor's signals across merchants into a graph, scores network risk, and shows analysts the evidence behind each score. Runs on **synthetic data**.
- HMAC-tokenized identifiers (no raw phone/email/device IDs after ingestion)
- Entity resolution, graph construction with community detection, LightGBM risk model with calibration, SHAP explanations
- Minimum-evidence gate to limit false positives on households and shared devices
- Role-scoped FastAPI endpoints and a Streamlit analyst demo
- **Stack:** Python, pandas, scikit-learn, LightGBM, NetworkX, SHAP, FastAPI, Streamlit

### [SentinelForge](https://github.com/Mahi31sh/SentinelForge)
Cybersecurity copilot that routes a message to the right analysis engine and explains the result.
- Phishing analysis of URLs and message text (rule-based and ML-based)
- Log analysis for brute-force and related patterns, mapped to MITRE ATT&CK
- VirusTotal and AbuseIPDB lookups when API keys are configured
- LLM explanations via Groq, with a local Ollama fallback
- **Stack:** Python, FastAPI, scikit-learn, Groq API, vanilla JS frontend

### [Fraud Governance & Drift Detection System](https://github.com/nish1606/Drift_detection) (team project)
Final-year team project: a fraud-scoring system that monitors the model itself with drift detection, SHAP/LIME explainability and policy-based governance actions (alert, fallback, freeze, retrain flag).
- **My part:** initial backend scaffold, response actions (rollback, freeze, alerting, retraining flag), schemas, preprocessing, Docker setup, test scaffolding
- **Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, React, Docker

## Skills

| Area | Tools |
|---|---|
| Languages | Python, SQL, TypeScript / JavaScript, C++ |
| Backend | FastAPI, Flask, SQLAlchemy, PostgreSQL, SQLite, JWT auth |
| ML | scikit-learn, LightGBM, SHAP, pandas, NumPy, Hugging Face Transformers |
| LLM | Groq API, prompt design, output validation |
| Frontend | React, Tailwind CSS, Streamlit |
| Tools | Git, Docker, pytest |

## Certifications

Google Cybersecurity Professional Certificate · Cisco Cybersecurity Fundamentals · IBM Cybersecurity Fundamentals

## Beyond code

Secretary and Joint Secretary, IEEE Student Branch, Atria Institute of Technology (event coordination).

All projects run locally; none are currently deployed. Setup instructions are in each repository's README.
