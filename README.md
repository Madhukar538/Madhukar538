# Hi, I'm Boda Madhukar Reddy

**Software Architect · Hyderabad, India**

I design high-throughput .NET APIs, build self-hosted AI platforms (RAG, MCP, Microsoft Agent Framework, hybrid search), and load-test everything with k6 and Grafana. Production-first: diagnose fast, fix right, prevent recurrence.

[![Website](https://img.shields.io/badge/dhucar.in-0b1220?style=for-the-badge&logo=googlechrome&logoColor=white)](https://dhucar.in)
[![Blog](https://img.shields.io/badge/Blog-0b1220?style=for-the-badge&logo=rss&logoColor=orange)](https://dhucar.in/rss.xml)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhukar-reddy-boda)
[![Résumé](https://img.shields.io/badge/Résumé_(PDF)-0b1220?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://dhucar.in/resume.pdf)

---

## Right now

- **Software Architect at Revalsys Technologies** (2021 – Present)
- Making our AI agent's answers about twice as fast by testing a new way to run the model on our own server.
- Writing about it all at **[dhucar.in](https://dhucar.in)**.

## Featured work

**[Multi-Tenant AI Chatbot Platform](https://dhucar.in/projects/multi-tenant-ai-chatbot)**: an embeddable RAG assistant on .NET 10. It uses Microsoft Agent Framework agents with MCP tools for database and docs access, pgvector retrieval, interactive map answers, passkey sign-in, server-bound licensing, and remote installs and upgrades.
→ After a latency audit and the move to Microsoft Agent Framework, most answers arrive in **about 13 seconds, down from 30–40**.

**Offline-First Procurement & Inspection App**: a Next.js PWA plus an Android shell for field procurement. It has one storage interface over Android SQLite and IndexedDB, master-data sync, and a transactional outbox that replays actions when the device is back online.

**Uptime & Incident Management Platform**: Uptime Kuma as a headless check engine behind a custom .NET 10 API and React admin. It covers incidents, maintenance windows, FCM push alerts, flapping suppression, self-healing hooks and ticketing.

**Also built:**
- a real-time IoT data platform (MQTT, Cassandra, fault-tolerant recovery);
- a Visual Studio IntelliSense extension for internal frameworks;
- a modular video-conferencing system;
- face authentication with liveness detection;
- the PWBAssistant NuGet package for Playwright-based table scraping.

**E-commerce and integrations** for Jockey, Speedo, Fossil India, Manyavar (Vedant Fashions) and LuxCozi.

More on [dhucar.in/projects](https://dhucar.in/projects).

## Latest writing

- [RTX 5090 vs DGX Spark for a Local AI Agent: Why Memory Bandwidth Won](https://dhucar.in/blog/rtx-5090-vs-dgx-spark-local-llm-inference)
- [Memory, Reach and Habits: How I Use an Obsidian Vault, MCP and Skills to Ship Production-Grade Code](https://dhucar.in/blog/ai-development-workflow-obsidian-mcp-skills)
- [Giving AI Assistants a Map of Your Codebase: An MCP Server for C# Code and SQL Server Schemas](https://dhucar.in/blog/mcp-server-code-database-intelligence)
- [How I Turned My MacBook into a Self-Hosted Vercel with Coolify, Cloudflare Tunnel & Terraform](https://dhucar.in/blog/turning-my-macbook-into-a-self-hosted-paas)
- [Why Our RAG Chatbot Took 40 Seconds to Answer, and the Plan to Make It 70% Faster](https://dhucar.in/blog/rag-chatbot-latency-audit)

All posts on [dhucar.in](https://dhucar.in), or follow the [RSS feed](https://dhucar.in/rss.xml).

## In the lab

- **Local LLM GPU benchmark:** an RTX 5090 vs a DGX Spark on the same agent request.
- **Hybrid product search** on Solr 9: BM25 + vectors + Reciprocal Rank Fusion.
- **On-demand ISR** between Next.js 16 and a .NET API.
- **MCP server** for C# code and SQL Server schema intelligence.
- **10-node bare-metal cluster** from mini PCs: Docker Swarm first, K3s later.

## Tech stack

| Area | Tools |
|---|---|
| **Languages** | C#, TypeScript, JavaScript, Python, SQL, C |
| **Backend** | .NET 10 / ASP.NET Core, Web API & MVC, Worker Services, Blazor, Node.js, FastAPI |
| **Frontend & mobile** | Next.js 16, React 19, Angular, Tailwind CSS, React Native, offline-first PWAs |
| **AI & LLMs** | RAG, Microsoft Agent Framework, Semantic Kernel, MCP, Ollama (Qwen3, Gemma), LiteLLM, mem0, LangChain, ONNX Runtime, WebLLM, whisper.cpp, OpenCV |
| **Search & vectors** | Solr 9 (kNN), hybrid BM25 + vector (RRF), pgvector, Qdrant |
| **Data & caching** | SQL Server, PostgreSQL, MongoDB, ClickHouse, SQLite, Redis, Memcached, EF Core, Dapper |
| **Messaging & realtime** | RabbitMQ, SignalR, gRPC, MQTT, WebRTC, Socket.IO, FCM |
| **DevOps** | Docker, Docker Swarm, K3s, Proxmox, Coolify, Cloudflare Tunnel, Terraform, Azure, Azure DevOps |
| **Quality & observability** | k6, Grafana, Uptime Kuma, Playwright, Roslyn analyzers, Postman |

## Contact

- Email: [madhukarreddyboda538@gmail.com](mailto:madhukarreddyboda538@gmail.com)
- Phone: [+91 95731 53479](tel:+919573153479)
- Website: [dhucar.in](https://dhucar.in)
- LinkedIn: [madhukar-reddy-boda](https://www.linkedin.com/in/madhukar-reddy-boda)
