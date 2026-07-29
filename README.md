<div align="center">

<img src="assets/banner.svg" alt="Abdallah Hosni — AI Engineer. LLM, RAG and Graph RAG. Production-focused AI systems." width="100%">

<br>

**AI Engineer & Full-Stack Developer — Egypt**

I build AI systems that are meant to survive contact with real users: guardrailed, tested, documented, and deployed.

</div>

---

### The problem I work on

Most AI demos break the moment they meet production. A model that answers well in a notebook still has to be constrained, validated, monitored, and made safe to run against real data.

That gap is my work. I treat model output as untrusted input, put an explicit boundary in front of it, and make the system prove itself with tests before it ships.

### What I'm building right now

- Guardrailed **text-to-SQL** — AST-level SQL validation instead of keyword filters
- **Graph RAG** and knowledge-graph retrieval over messy, real-world records
- **Bilingual (Arabic / English)** NLP pipelines
- Agentic workflows with **bounded, auditable** tool use

---

## Selected work

### [safe-text-to-sql](https://github.com/Abdo1119/safe-text-to-sql) &nbsp;·&nbsp; [Live demo](https://safe-text-to-sql-jopyjpvxd2y2cgvhv63zrn.streamlit.app/)

Natural-language analytics over a SQL database, built so that model-generated SQL can never be trusted blindly.

Generated SQL is parsed into an AST and checked by policy — single read-only statement, schema allowlist, no mutations, no data-modifying CTEs, no system catalogs, enforced row limits — then executed through a read-only connection with a fail-closed authorizer. Ships with a deterministic offline provider so the whole pipeline runs, and is tested, without any API key.

`Python` `Gemini` `SQLGlot` `Streamlit` `Docker` `pytest` · 184 offline tests · CI green · MIT

### [airport-lost-found-ai](https://github.com/Abdo1119/airport-lost-found-ai)

Bilingual, human-in-the-loop lost-item matching for airport operations — explainable scoring, Graph RAG, and image matching, with a complete local demo mode.

Built as a full production-shaped system rather than a notebook: API, database, cache, typed frontend, containers, and infrastructure definitions.

`Python` `FastAPI` `PostgreSQL` `Redis` `Graph RAG` `Computer Vision` `React` `TypeScript` `Docker` `Azure` · MIT

---

## Stack

**AI & ML**
<br>
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=5FD0F5&labelColor=0D1117)
![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=flat-square&logo=pytorch&logoColor=E23636&labelColor=0D1117)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=flat-square&logo=langchain&logoColor=5FD0F5&labelColor=0D1117)
![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=flat-square&logo=opencv&logoColor=E23636&labelColor=0D1117)
![Gemini](https://img.shields.io/badge/Gemini-0D1117?style=flat-square&logo=googlegemini&logoColor=5FD0F5&labelColor=0D1117)
![Azure AI](https://img.shields.io/badge/Azure_AI-0D1117?style=flat-square&logo=microsoftazure&logoColor=5FD0F5&labelColor=0D1117)

**Backend & Data**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=5FD0F5&labelColor=0D1117)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=5FD0F5&labelColor=0D1117)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=E23636&labelColor=0D1117)
![Neo4j](https://img.shields.io/badge/Neo4j-0D1117?style=flat-square&logo=neo4j&logoColor=5FD0F5&labelColor=0D1117)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=5FD0F5&labelColor=0D1117)

**Interfaces**
<br>
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=5FD0F5&labelColor=0D1117)
![React](https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=5FD0F5&labelColor=0D1117)
![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=F2F6FC&labelColor=0D1117)
![Streamlit](https://img.shields.io/badge/Streamlit-0D1117?style=flat-square&logo=streamlit&logoColor=E23636&labelColor=0D1117)

<div align="center">
<br>

<img src="assets/languages.svg" alt="Language mix across application repositories: Python 72.3%, TypeScript 23.6%, Bicep 1.8%, JavaScript 1.2%, Shell 0.5%, other 0.7%." width="470">

</div>

---

## Off-duty

Big Marvel fan — less for the capes, more for the workshop scenes. The appeal was never the suit; it was someone building, testing, and iterating until the thing actually held up under load.

That's the same instinct I bring to engineering: **build it, then try hard to break it before anyone else does.**

Outside that: chess, football, and reading about how large systems fail.

---

## Contact

<a href="mailto:fortunecodec@gmail.com">
<img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=E23636&labelColor=0D1117" alt="Email"></a>
<a href="https://github.com/Abdo1119">
<img src="https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=F2F6FC&labelColor=0D1117" alt="GitHub"></a>

<!-- Add your LinkedIn once ready, then uncomment:
<a href="https://www.linkedin.com/in/YOUR-HANDLE/">
<img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=5FD0F5&labelColor=0D1117" alt="LinkedIn"></a>
-->

Open to AI engineering roles and freelance work on production LLM, RAG, and computer-vision systems.

<div align="center">
<br>
<sub><i>Model output is untrusted input until something proves otherwise.</i></sub>
</div>
