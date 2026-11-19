<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f172a,100:6366f1&height=140&section=header&text=Aditya%20Ambade&fontSize=44&fontColor=ffffff&fontAlignY=50&desc=AI%20engineer%20%C2%B7%20RAG%20and%20agents%20%C2%B7%20production%20LLM%20systems&descAlignY=72&descSize=16" width="100%"/>

**I build AI systems that retrieve, reason and automate, and I measure whether they actually work.**

[![Portfolio](https://img.shields.io/badge/Portfolio-ambade.me-6366f1?style=flat-square&logo=googlechrome&logoColor=white)](https://ambade.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ambadeaditya-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ambadeaditya)
[![Email](https://img.shields.io/badge/Email-aditya.ambade@outlook.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:aditya.ambade@outlook.com)

</div>

<br/>

## About

I'm an AI engineer in India with a B.Tech in Computer Science (2026). I work on production LLM systems end to end: schema-constrained model calls, deterministic logic around them, evaluation and cost tracking, and the FastAPI and PostgreSQL backends they run in.

| | |
|---|---|
| **Now** | Junior AI Automation Engineer on a client engagement, GIFT City (08/2026 to now) |
| **Building** | [Nyaya Search](https://github.com/aadi-novice/nyaya-search): improving retrieval quality against a published evaluation |
| **Looking for** | AI engineer, applied AI and forward-deployed roles, in India, remote or abroad |
| **Learning** | Rust, system design, Japanese (about JLPT N5) |

<br/>

## Featured work

### [Nyaya Search](https://github.com/aadi-novice/nyaya-search)
*Cited legal research over Indian Supreme Court judgments, where code, not the model, checks every quote.*

Layout-aware parsing and paragraph-level chunking of 13,007 judgments (296,151 chunks), hybrid BM25 + pgvector search with reciprocal rank fusion and Qwen3 reranking, a refusal threshold, and a FastAPI service with a web page. Every answer sentence quotes a retrieved passage word for word, and code verifies the quote before the sentence is shown. It runs on one 6 GB GPU with free tools.

Measured on a frozen question set (44 development, 40 unanswerable, 20 adversarial), development numbers, not a final test:

| Check | Result |
|---|---|
| Citation violations | **0** in 186 sentences |
| Unanswerable questions refused | **100%** |
| p95 answer latency | **9.4 s** |
| RAGAS faithfulness / context precision / context recall | **0.89 / 0.80 / 0.76** |
| Right judgment in top 5 after reranking | 73% (target 75%, not met yet) |

The goals it misses are listed in the repo next to the ones it meets.

`Python` `FastAPI` `PostgreSQL` `pgvector` `BM25` `RAGAS`

### [Intervue](https://github.com/aadi-novice/intervue)
*Multi-tenant AI recruitment and interview platform.*

115+ REST endpoints on FastAPI, PostgreSQL + pgvector and Celery/Redis, with RBAC, API keys and webhooks. Structured LLM outputs, rubric scoring with versioned prompts, and an AI gateway that logs tokens, cost and latency per call. 570+ backend tests.

`FastAPI` `pgvector` `Celery` `Pydantic`

### Customer-facing AI chatbot (client work)
*Rebuilt as a tested standalone service.*

An LLM fills a JSON schema, a deterministic state machine decides, and a second LLM phrases the reply behind output checks, replacing a 400,000-character n8n workflow. About $0.003 per 10-turn conversation. Private client code.

### Hybrid search at NeuralVedaX
*Enterprise retrieval.*

A 35,000-edge knowledge graph built from 8,000+ documents, and a BM25 + FAISS retrieval engine with cross-encoder reranking over 2,000+ regulatory licenses. Deployed with FastAPI, Docker, PostgreSQL and Neo4j.

### [Totem](https://gettotem.app)
*An Android focus app you switch off by scanning a real object.*

Flutter UI with native Kotlin locking and QR-triggered blocking. Early access; Google Play launch pending.

<br/>

## Experience

| When | Role | Where |
|:--|:--|:--|
| 08/2026 to now | **Junior AI Automation Engineer** | Client engagement, GIFT City |
| 02/2026 to 08/2026 | AI/ML Developer | NeuralVedaX, Vadodara |
| 05/2025 to 08/2025 | Agentic AI Developer | Techmero, Vadodara |

<br/>

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,rust,fastapi,postgres,docker,react,nextjs,neo4j,pytorch,git&perline=10" />

</div>

**AI / ML:** LLM applications and agents, structured outputs, RAG, hybrid search, reranking, evaluation (RAGAS), embeddings, knowledge graphs, FAISS, pgvector, PydanticAI, LangChain
**Backend:** Python, FastAPI, SQLAlchemy, Celery, Redis, PostgreSQL, Neo4j

<br/>

## Open source

- **Graphify:** fixed a rendering bug on graphs with 1,000+ nodes
- **Pyrefly (Meta):** fixed an LSP hover issue with `ParamSpec`

<br/>

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=aadi-novice&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aadi-novice&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<br/>

## Outside the editor

Anime, trekking, chess, music, and slowly learning Japanese.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366f1,100:0f172a&height=60&section=footer" width="100%"/>

</div>
