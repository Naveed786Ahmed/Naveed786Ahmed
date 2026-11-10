# Naveed Ahmed

**AI Engineer | RAG Systems · LLM Applications · Intelligent Automation · Agentic AI**

I build AI applications that connect language models with business workflows, internal knowledge, and external systems.

My work focuses on retrieval-augmented generation, structured LLM outputs, API-driven integrations, and workflow orchestration. I'm particularly interested in the engineering challenges behind reliable AI systems—from maintaining context and managing asynchronous execution to validating outputs and keeping humans involved in critical decisions.

**[Portfolio](https://naveed-ahmed-portfolio.vercel.app/)** · **[LinkedIn](https://www.linkedin.com/in/naveed-ahmed-8340b6281/)**

---

## Engineering Focus

**LLM & RAG Systems**  
Document ingestion, embedding pipelines, semantic retrieval, grounded generation, source attribution, and response evaluation.

**AI Automation & Orchestration**  
Event-driven workflows, structured data extraction, webhook coordination, persistent execution state, and human-in-the-loop approvals.

**Agentic Applications**  
Tool-integrated LLM workflows, contextual decision-making, agent orchestration patterns, and controlled interactions with external services.

**Backend & Integration Engineering**  
Python services, REST APIs, database integration, authentication-aware workflows, and containerized development.

---

## Selected Engineering Work

### [Enterprise HR Onboarding & Document Automation](https://github.com/Naveed786Ahmed/HR-Onboarding-Automation-Engine)

*Event-driven onboarding automation with persistent workflow state and human approval controls.*

Designed an n8n-based onboarding workflow that coordinates AI-assisted resume processing, candidate records, document signing, and manager approvals across multiple external services.

The core engineering challenge was managing long-running processes without depending on a continuously active workflow execution. Candidate state is persisted in Supabase PostgreSQL, allowing subsequent DocuSign and Slack webhook events to advance the process.

**Implementation highlights**
- Structured resume extraction using OpenAI with schema-constrained outputs.
- Database-backed candidate state transitions and audit records.
- Asynchronous DocuSign signature handling through webhook-triggered workflows.
- Interactive Slack approval and rejection paths.
- Simulated IT provisioning following manager approval.

**Stack:** n8n · OpenAI API · Supabase PostgreSQL · DocuSign · Slack API · Webhooks

[Source Code & Architecture](https://github.com/Naveed786Ahmed/HR-Onboarding-Automation-Engine) · [System Walkthrough](https://youtu.be/gcYUnXp-SOg)

### Enterprise RAG Knowledge Assistant

*Document-grounded question answering with source traceability.*

- Built a document ingestion and retrieval pipeline using LangChain, OpenAI embeddings, and vector storage.
- Preserved document and page metadata to support source-level citations.
- Implemented grounded response generation with a fallback for questions unsupported by retrieved context.
- Integrated the retrieval workflow with a FastAPI backend and designed an evaluation process using RAGAS.

**Stack:** Python · FastAPI · LangChain · OpenAI API · ChromaDB · Docker

### AI Customer Support Email Gateway

*Knowledge-grounded email automation with escalation controls.*

- Designed an email-processing pipeline that separates support requests from unrelated messages.
- Connected classified requests to a retrieval workflow for knowledge-grounded response generation.
- Added escalation logic for requests lacking sufficient supporting information.
- Preserved Gmail conversation context through message and thread identifiers.

**Stack:** n8n · OpenAI API · Pinecone · Gmail API · Webhooks

### B2B Conversational Lead Qualification Agent

*Conversational lead qualification integrated with CRM workflows.*

- Built an AI-assisted qualification flow for collecting and structuring prospect information.
- Implemented deterministic routing based on qualification outcomes.
- Connected conversational interactions with HubSpot CRM through API-driven workflows.
- Incorporated conversation state handling and duplicate-record checks.

**Stack:** n8n · OpenAI API · Telegram · HubSpot CRM · Webhooks

---

## Technical Stack

| Area | Technologies |
|---|---|
| **AI & LLM Development** | OpenAI API, LangChain, RAG, Embeddings, Structured Outputs |
| **Languages & Backend** | Python, FastAPI, JavaScript, TypeScript, Node.js |
| **Automation & Integration** | n8n, REST APIs, Webhooks, Human-in-the-Loop Workflows |
| **Data & Retrieval** | ChromaDB, Pinecone, Supabase, PostgreSQL, MongoDB |
| **Development & Infrastructure** | Docker, Git, GitHub, Postman |

### Agentic AI — Ongoing Technical Development

My broader technical development includes agent SDKs, memory architectures, multi-agent design patterns, Model Context Protocol (MCP), agent-to-agent communication (A2A), evaluation methodologies, and distributed agent orchestration concepts.

These areas complement my hands-on work with LLM applications, retrieval systems, and automated workflows.

---

## Engineering Approach

I approach AI development as a software engineering problem, not just a model integration task.

- **Ground outputs in evidence.** Use retrieval, source attribution, and explicit fallback behavior where accuracy matters.
- **Keep workflows predictable.** Separate probabilistic model decisions from deterministic business rules.
- **Design for interruptions.** Account for retries, duplicate events, asynchronous execution, and external API failures.
- **Maintain human control.** Introduce approval or escalation steps where automation should not make the final decision.
- **Make systems understandable.** Favor clear architecture, structured data contracts, and documented integration boundaries.

---

## Connect

I'm interested in AI engineering opportunities and collaborations involving LLM applications, RAG systems, agentic workflows, and business automation.

**[Portfolio](https://naveed-ahmed-portfolio.vercel.app/)** · **[LinkedIn](https://www.linkedin.com/in/naveed-ahmed-8340b6281/)** · **[GitHub](https://github.com/Naveed786Ahmed)**
