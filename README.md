🧠 NovaMind AI Marketing Pipeline

Automated system that generates blog and newsletter content with AI, syncs with a CRM (Zoho), and analyzes engagement performance.

⸻

⚙️ Architecture Overview

Flow:
Topic Input → AI Content Generation → CRM Sync → Performance Simulation → AI Insights

Key steps:
	1.	Generate blog + persona newsletters via OpenAI.
	2.	Create/update contacts and log campaigns in Zoho CRM.
	3.	Simulate open/click/unsubscribe metrics.
	4.	Use AI to summarize performance insights.

⸻

🧩 Tools & APIs
	•	OpenAI API (GPT-4o-mini) → Content generation & analytics
	•	Zoho CRM API (v2) → Contacts, Notes, campaign logs
	•	Python → requests, pandas, numpy for data handling
	•	Storage → JSON & CSV files in /artifacts/

⸻

💡 Assumptions
	•	Mock CRM contacts (no real emails).
	•	Engagement data randomly simulated.
	•	API keys stored as environment variables.
