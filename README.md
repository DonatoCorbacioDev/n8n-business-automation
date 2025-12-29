# n8n Business Automation Portfolio

A collection of real-world **n8n automation workflows** I built to demonstrate practical solutions for business process automation, AI integration, and multi-platform orchestration.

## What's Inside

This repo contains **5 progressive automation projects** I developed while learning n8n and exploring AI integration patterns:

| #   | Project                   | What It Does                                                                                             | Workflows                                 |
| --- | ------------------------- | -------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| 1   | **Email Automation**      | Auto-saves Gmail attachments to Google Drive and notifies via Slack                                      | [📁 View](./exercise-1-email-automation/) |
| 2   | **AI Content Generator**  | Reads topics from Google Sheets, generates SEO content with AI, publishes to Notion                      | [📁 View](./exercise-2-ai-content/)       |
| 3   | **LinkedIn Lead Finder**  | Scrapes LinkedIn profiles via Google Search, AI scores leads, stores in Airtable                         | [📁 View](./exercise-3-linkedin-leads/)   |
| 4   | **Smart Survey Pipeline** | Captures FormBricks surveys, AI classifies leads, triggers personalized emails + CRM tickets             | [📁 View](./exercise-4-survey-crm/)       |
| 5   | **RAG Chatbot**           | PDF-powered chatbot using Supabase vector search with automatic ticket creation for unanswered questions | [📁 View](./exercise-5-rag-chatbot/)      |

## Tech Stack

**Core:** n8n, Google Gemini AI, RAG (Retrieval-Augmented Generation)  
**Integrations:** Gmail, Slack, Notion, Airtable, Zendesk, Supabase, FormBricks, Dropbox  
**Techniques:** Vector embeddings, AI agents, error handling, scheduled workflows, webhook automation

## Setup

1. Import the JSON workflows into your n8n instance
2. Configure your own credentials (Gmail, Slack, etc.)
3. Replace placeholders:
   - `YOUR_GOOGLE_SEARCH_ENGINE_ID`
   - `YOUR_SLACK_WEBHOOK_URL_HERE`
   - Email addresses and workspace names
4. Test before activating

**Note:** All sensitive data (API keys, tokens) is stored via n8n credentials and NOT exposed in these files.

## Project Structure

n8n-business-automation/
├── README.md
├── exercise-1-email-automation/ # Gmail → Drive → Slack
├── exercise-2-ai-content/ # AI content generation pipeline
├── exercise-3-linkedin-leads/ # LinkedIn lead scraping + AI scoring
├── exercise-4-survey-crm/ # Survey → AI → CRM automation
└── exercise-5-rag-chatbot/ # RAG chatbot with Supabase

## Why I Built This

I wanted to explore **real business automation scenarios** beyond basic tutorials. Each workflow solves a practical problem:

- **Exercise 1-2:** Document management and content production automation
- **Exercise 3-4:** Lead generation and qualification with AI
- **Exercise 5:** Advanced AI chatbot with vector search and fallback handling

These projects helped me understand how to:

- Design multi-step automation flows
- Integrate AI models into business processes
- Handle errors gracefully
- Work with vector databases and RAG patterns

## What I Learned

- Building production-ready workflows requires proper error handling
- AI classification can automate decision-making (lead scoring, content routing)
- RAG chatbots need fallback strategies when answers aren't found
- n8n's node-based approach makes complex integrations manageable

## License

Open source for educational purposes. Feel free to learn from or build upon these workflows.

## Contact

Questions? Suggestions? Open an issue or reach out via GitHub.
