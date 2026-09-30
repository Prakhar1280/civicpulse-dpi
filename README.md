🌐 CivicPulse — Multilingual DPI Governance Engine

Track 1: AI for Digital Public Infrastructure & Governance (BRICS Theme: Innovation)

Bridging grassroots citizen voice with national capital infrastructure expenditure across BRICS economies.

📌 Executive Summary

In emerging and BRICS economies, citizen development demands remain structurally isolated within fragmented regional channels (WhatsApp voice notes, vernacular SMS, community boards). As a result, municipal and national ministries allocate annual capital expenditure based on outdated survey data rather than live, real-world urgency.

CivicPulse is an open-standard Digital Public Good (DPG) that continuously ingests unstructured citizen grievances across any regional language or dialect, normalizes the data into canonical Digital Public Infrastructure (DPI) schemas, computes localized urgency and demographic impact scores, and surfaces actionable policy briefs for infrastructure planners.

🚀 Key Features

Multilingual Vernacular Ingest: Seamlessly processes text and voice transcripts in Hindi, Portuguese, Mandarin, Russian, and regional dialects with zero manual translation pipeline overhead.

Canonical DPI JSON Schemas: Standardizes unstructured complaints into cross-border, interoperable data payloads compatible with existing national governance portals.

Real-Time Urgency & Impact Scoring: Dynamically rates infrastructure severity (1–10 scale) to prevent critical failures (e.g., healthcare transit blockages, water pipeline bursts) from being lost in bureaucratic backlogs.

Policymaker Decision Support: Generates concrete budget allocation recommendations directly aligned with national infrastructure priorities.

🛠️ Architecture & Tech Stack

[ Citizen Ingest Layer ]
       │  (Vernacular Text, Audio, WhatsApp, SMS)
       ▼
[ Multilingual Preprocessing Gateway ]
       │
       ▼
[ Gemini 2.5 Flash Reasoning Engine ]
       ├── Zero-Shot Vernacular Translation
       ├── Dynamic DPI Sector Categorization
       └── Impact & Urgency Scoring (1-10)
       │
       ▼
[ Standardized Open DPI Schema (JSON) ]
       │
       ▼
[ Policymaker Hotspot & Budget Routing Dashboard ]


Frontend / Interface: Lightweight Single-Page Web Application, Tailwind CSS

AI Engine: Google Gemini Flash API (gemini-2.5-flash) via structured JSON schema enforcement

Standards: Open Digital Public Good (DPG) principles, zero PII retention, modular API contract

⚡ Live Demo & Quick Start

Live Prototype: https://prakhar1280.github.io/civicpulse-dpi/

Repository: https://github.com/Prakhar1280/civicpulse-dpi

Running Locally

No build tools or backend servers are required.

Clone this repository:

git clone https://github.com/Prakhar1280/civicpulse-dpi.git
cd civicpulse-dpi


Open index.html directly in any modern web browser:

# On Windows
start index.html


🌍 Cross-Border BRICS Scalability

Zero Model Retraining: Gemini's zero-shot multilingual reasoning natively understands linguistic nuances across India, Brazil, South Africa, Russia, and China.

Federated Governance Knowledge: Member nations can exchange priority-routing models and disaster mitigation playbooks while keeping underlying citizen telemetry private.

Pluggable Integration: Designed to interface with existing national stacks (e.g., India Stack, Pix/Gov.br, Open Banking/DPI frameworks).
