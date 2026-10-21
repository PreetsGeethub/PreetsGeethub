<div align="center">

# Hey, I'm Pritam Kumar 👋

### AI Engineer · GenAI & LLM Applications · Full-Stack Development

I build practical AI-powered products—from tool-using LLM agents and RAG pipelines to the APIs and interfaces that make them useful.

[![GitHub](https://img.shields.io/badge/GitHub-PreetsGeethub-181717?style=for-the-badge&logo=github)](https://github.com/PreetsGeethub)
[![LeetCode](https://img.shields.io/badge/LeetCode-400%2B%20solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/preet_leetcode)
[![Live Project](https://img.shields.io/badge/Live%20Project-KK%20Store-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.kkstore.in/)

</div>

---

## 👨‍💻 About me

- 🎓 MCA graduate (2026), University of Rajasthan.
- 🤖 Focused on **AI engineering, LLM applications, agentic workflows, and retrieval-augmented generation**.
- 🛠️ Building **KK Store AI Shopping Assistant**—an AI assistant connected to real e-commerce APIs and product data.
- 🔎 Interested in tool calling, semantic search, RAG evaluation, reranking, MCP, and reliable AI integrations.
- 🌐 Comfortable working across Python/FastAPI, React/Next.js, Node.js, PostgreSQL, and deployment tooling.
- 🧩 I enjoy turning AI prototypes into end-to-end product experiences, including the UI, backend integration, and infrastructure.
- 🧠 Solved **400+ LeetCode problems** and completed Striver's A2Z DSA Sheet.

## 🚀 Featured projects

### [KK Store — AI Shopping Assistant](https://github.com/PreetsGeethub/kkstore) · [Live storefront](https://www.kkstore.in/)

A full-stack e-commerce platform with an AI shopping assistant.

- Built an LLM agent that uses tools to search the live catalog and retrieve product details through backend APIs.
- Implemented semantic product search with embeddings, Qdrant, and metadata filtering.
- Built a policy RAG pipeline with dense retrieval and cross-encoder reranking. On a 20-query test set: **100% Recall@3, 94% Recall@1, and 0.97 MRR@3**.
- Added policy retrieval as an agent tool alongside product and order tools.
- Deployed an OAuth-protected remote MCP server with allow-list access control and connected it to Claude through WorkOS AuthKit.
- Containerized and deployed the service on a VPS behind Nginx; automated checks, Docker builds, and GHCR publishing with GitHub Actions.
- Implemented Redis-backed multi-turn conversation state and automated tests with pytest.
- Built a custom customer-facing AI assistant experience with an animated robot introduction and conversational UI.

**Stack:** Python, FastAPI, MCP, OAuth 2.0, WorkOS, Claude, OpenRouter/Ollama, RAG, Qdrant, Redis, PostgreSQL, Prisma, Node.js, Next.js, Docker, Nginx, GitHub Actions.

### [ResumeAnalyzer](https://github.com/PreetsGeethub/ResumeAnalyzer)

An AI-powered resume analysis platform built with FastAPI and React.

- Parses PDF/DOCX resumes and extracts structured skills, experience, and education using Pydantic.
- Uses Gemini for resume scoring and job-description matching.
- Includes matched/missing skill summaries, cookie-based authentication, saved analysis history, and a React dashboard.

**Stack:** Python, FastAPI, Pydantic, Gemini API, PostgreSQL, React, Alembic.

### [QuickDrive](https://github.com/PreetsGeethub/quickDrive)

A secure cloud file-sharing platform with JWT-based per-folder access control.

- Built a full-stack file-sharing backend with Prisma and PostgreSQL.
- Load-tested core routes with k6: **0 failures across 620 requests at 50 concurrent users**.

**Stack:** Node.js, Express, Prisma, PostgreSQL, Supabase, k6.

### Talk to Your Docs — Hybrid PDF RAG Assistant

A hybrid PDF question-answering project using dense retrieval and BM25, Reciprocal Rank Fusion, and Cohere reranking. Retrieved passages are shown to help users verify generated answers.

**Stack:** Python, Streamlit, LlamaIndex, Hugging Face, BM25, RRF, Cohere Rerank, OpenRouter.

---

## 🧰 Tech stack

### AI / GenAI
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-5B4BDB?style=flat-square)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-20232A?style=flat-square)
![OpenRouter](https://img.shields.io/badge/OpenRouter-412991?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-111111?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Concepts:** LLM tool/function calling, agent orchestration, embeddings, semantic search, hybrid retrieval (dense + BM25), RRF, cross-encoder reranking, retrieval evaluation (Recall@K, MRR), structured outputs.

### Full-stack development
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Data, infrastructure & testing
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

**Also familiar with:** C++, SQL, MongoDB, MySQL, Firebase, Supabase, Postman, Git, Linux, and Vercel.

## 📈 GitHub stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=PreetsGeethub&show_icons=true&hide_border=true&rank_icon=github" alt="Pritam's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PreetsGeethub&layout=compact&hide_border=true" alt="Most used languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PreetsGeethub&hide_border=true" alt="GitHub contribution streak" />
</div>

## 🤝 Connect

- **GitHub:** [@PreetsGeethub](https://github.com/PreetsGeethub)
- **LeetCode:** [preet_leetcode](https://leetcode.com/preet_leetcode)
- **Email:** [pritamjangir62@gmail.com](mailto:pritamjangir62@gmail.com)
- **Live project:** [kkstore.in](https://www.kkstore.in/)

---

<div align="center">

*Learning by building. Shipping useful AI. Improving one iteration at a time.* 🚀

</div>
