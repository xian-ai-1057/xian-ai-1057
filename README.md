## Hi, I'm Kee Chiong Hean

AI Engineer in banking. I build LLM and RAG systems that have to run inside regulated environments: on-prem models, auditable answers with citations, and a human reviewer in the loop.

- **Focus:** enterprise LLM applications, RAG quality and citations, AI governance, agent frameworks
- **Day to day:** Python, FastAPI, Ollama / vLLM / OpenAI-compatible endpoints, LiteLLM, MCP, SQLite / Postgres
- **Languages:** English, Mandarin (native), Malay

### Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| [**AgentHarness**](https://github.com/xian-ai-1057/AgentHarness) | Open-source, model-agnostic agent harness. Agents defined in YAML + Markdown, tools from Python functions or MCP servers, user approval before risky actions, multi-user web UI, RAG and skills. Ships with Docker. [Docs](https://agent-harness-docs-ten.vercel.app) | Python, TypeScript, LiteLLM, MCP |
| [**showreceipts**](https://github.com/xian-ai-1057/showreceipts) | Citation layer for any RAG pipeline: normalises `[n]` markers, removes fabricated citations, and adds a model-free quality report that flags unsupported sentences, numbers and dates. | Python, CLI, OpenAI-compatible / Ollama |
| [**rag_checker**](https://github.com/xian-ai-1057/rag_checker) | Human review console for RAG answers: separates retrieval errors from answer errors, records corrections, exports to Excel. | FastAPI, Jinja2, SQLite |
| [**ai-news-site**](https://github.com/xian-ai-1057/ai-news-site) | AI news pipeline with validated ingestion, embeddings and hybrid (full-text + vector) Chinese search. | TypeScript, Supabase, Next.js |
| [**sg-fintech-agenda**](https://github.com/xian-ai-1057/sg-fintech-agenda) | Singapore FinTech Festival 2026 agenda explorer with a scraper and a LangChain Q&A agent. [Live](https://xian-ai-1057.github.io/sg-fintech-agenda/) | Selenium, React, LangChain |

### What I care about

- **Answers you can audit.** Every claim should point to a source, and unsupported numbers should be visible before a human signs off.
- **Data stays where it belongs.** Local and on-prem models first, cloud only when policy allows.
- **AI governance as engineering.** Rule checks, risk scoring and review workflows that make compliance faster, not slower.

[LinkedIn](https://www.linkedin.com/in/chionghean-kee-952030342)
