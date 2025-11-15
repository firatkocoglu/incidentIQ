⚙️ IncidentIQ

📘 Documentation
📄 Detailed project documentation & roadmap available on Notion:
#### 👉 [IncidentIQ – Notion Page](https://www.notion.so/IncidentIQ-AI-Powered-Incident-SLO-Management-Platform-2960fe48dd988018bb05f1fc9461a2be?source=copy_link)


### AI-powered Incident & SLO Management Platform

IncidentIQ is a developer-first reliability platform that ingests logs and metrics, detects anomalies, tracks service-level objectives (SLOs), and generates AI-based root-cause explanations using RAG (Retrieval-Augmented Generation).
It helps developers and DevOps teams detect, analyze, and resolve system issues faster — with explainable intelligence.

⸻

### 🚀 Features
	•	📥 Log & Metric Ingestion — Collect structured telemetry from multiple services
	•	📊 Anomaly Detection — Detect unusual spikes or failures in real time
	•	🎯 SLO Tracking — Monitor availability, error budgets, and burn rate
	•	🚨 Incident Lifecycle — Automatic incident creation, acknowledgment, resolution
	•	📡 Alert & Escalation — Slack / Email / Webhook notifications and on-call routing
	•	🧠 AI RCA Assistant — Context-aware root-cause analysis using RAG + pgvector
	•	🕵️ Observability — Full tracing and logging with OpenTelemetry + Serilog

⸻

### 🧱 Tech Stack

Backend: 
Database: PostgreSQL + pgvector + TimescaleDB
Messaging: RabbitMQ + MassTransit
Cache: Redis
Scheduling: Hangfire / Quartz
AI: OpenAI API (RAG-based explanations)
Observability: OpenTelemetry + Serilog

🏗️ Architecture

Clean Architecture + Event-Driven Design
Clients → Ingress API → Outbox → Event Bus
             ↓                     ↓
         PostgreSQL            Core Services
     (Logs, Metrics)   ─→  Anomaly / SLO / Incident / Alert / AI RCA
Each service communicates through domain events, enabling scalability and fault isolation.

🧾 Roadmap
	•	Log & Metric APIs
	•	Anomaly Detection Engine
	•	SLO Engine & Error Budget
	•	Incident Lifecycle
	•	Alert Router & Escalation
	•	AI RCA Assistant (RAG)
	•	Dashboard UI

⸻

🧑‍💻 Author

Fırat Koçoğlu
Software Engineer 
📎 [GitHub](https://github.com/firatkocoglu) | [LinkedIn](https://linkedin.com/in/firatkocoglu)


