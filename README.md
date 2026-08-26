# Automation Portfolio

Production workflows and AI systems for operational problems — intake, routing, qualification, and follow-through — built with n8n, Make, Zapier, and LLMs.

Each project is a complete, documented workflow: problem, architecture, decision logic, and setup. Domains include financial services, real estate, operations, and service businesses.

---

## Scope

I design systems that replace brittle, manual processes. That includes the happy path, the edge cases, failure handling, and the operational outcome the team actually needs.

**AI agents and chatbots**
- Conversational agents with memory and tool use
- RAG pipelines with semantic search
- Voice-note transcription and processing
- Lead capture and qualification

**Business process automation**
- End-to-end workflows in n8n, Make, and Zapier
- Multi-step branching, retries, and error handling
- CRM integration and data hygiene
- Notifications and follow-up sequences

**Data and operations**
- Google Sheets, Airtable, and Notion as operational stores
- Email classification and routing
- Calendar booking and scheduling
- Document ingestion and knowledge-base setup

---

## Stack

| Layer | Tools |
|---|---|
| Automation | n8n, Zapier, Make |
| LLMs | OpenAI, Groq, Claude, Gemini |
| Retrieval | Supabase (pgvector), MongoDB |
| Data / CRM | Google Sheets, Airtable, HubSpot, Notion |
| Messaging | Telegram, Gmail, Slack, WhatsApp Business API |
| Speech | OpenAI Whisper, Groq Whisper |
| Integration | Webhooks, REST APIs |

---

## Projects

Each folder includes importable workflow JSON, a README covering problem and logic, and credential / ID setup notes.

| Project | Folder | Stack | Domain |
|---|---|---|---|
| [AI Property Assistant](./Ai-Agent-Chatbot) | `Ai-Agent-Chatbot` | n8n, OpenAI, Groq, Supabase, Telegram, Google Calendar | Real estate |
| [Loan Eligibility & Offer Management](./loan-eligibility-automation) | `loan-eligibility-automation` | n8n, Gmail, Google Sheets | Financial services |
| [Structured Enquiry & Booking](./Structured-Enquiry-Booking-System) | `Structured-Enquiry-Booking-System` | n8n, Telegram, Google Sheets | Service business |
| [Vendor Onboarding & Headcount](./Global-Vendor-Onboarding-Automation) | `Global-Vendor-Onboarding-Automation` | n8n, Notion, email | International ops |
| [CMS Content Upload](./Cms-Content-Upload) | `Cms-Content-Upload` | n8n, Google Sheets, Strapi | Content operations |

---

## Using these workflows

Typical contents of a project folder:

- Workflow JSON for import into n8n
- Architecture and logic documentation
- Credential and API configuration
- Adaptation notes for a different use case
- Known failure modes from implementation

### Setup

1. Import the workflow JSON into your n8n instance.
2. Attach credentials for each connected service.
3. Replace environment-specific IDs (spreadsheets, databases, calendars, webhooks).
4. Adjust branching and copy for your process.
5. Run against sample data, then promote.

Do not deploy with placeholder credentials or production data until the flow has been tested end to end.

---

## Engagement

Available for freelance, contract, and advisory work on automation architecture and delivery.

What I optimise for: maintainable workflows, explicit error handling, documentation a team can operate without me, and systems that stay correct as volume grows.

- **LinkedIn:** [linkedin.com/in/joseph-a-712733216](https://www.linkedin.com/in/joseph-a-712733216/)
- **Email:** jcabanobi1@gmail.com
- **X:** [x.com/bigjoejs](https://x.com/bigjoejs)

---

Stars on the repo are appreciated if something here is useful.
