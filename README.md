# Hey there, I'm César Sibila! 👋

**Data & AI Engineer · RAG Architect · GNN Researcher · Desktop Software (Tauri/Rust)**

I am a Data & AI Engineer focused on building scalable data pipelines, automating complex processes, and deploying production-grade AI systems. I also build native desktop apps with Tauri + Rust. Currently an Intern at **Izii Soluções Tecnológicas**, Tech Lead for **Project Metis**, and founder of **[Mora Org](https://github.com/Mora-Org)** — an open-source collective building software with intention.

---

### 🌐 My Web CV & Portfolio
**The best place to see my full trajectory and live demos:**
👉 **[cesarsibila.vercel.app](https://cesarsibila.vercel.app/)**

---

### 🛠️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) |
| **AI & ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![PyTorch Geometric](https://img.shields.io/badge/PyTorch_Geometric-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=flat-square&logo=google&logoColor=white) ![Langflow](https://img.shields.io/badge/Langflow-1C3C3C?style=flat-square&logo=langflow&logoColor=white) ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-FF6F00?style=flat-square&logo=huggingface&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-Architecture-blue?style=flat-square) |
| **Data & Infra** | ![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) |
| **Desktop** | ![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) |
| **Automation** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/CI/CD-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |

---

### 🌟 Featured Repositories

- **⚡ [Metis](https://github.com/Czar210/metis-backend):** A full-stack LoL analytics platform (p-0.9.22). Features champion pages with build/matchup/synergy analytics, z-score tier ranking, match scoreboard with interactive timeline charts, a custom design system with PT/EN i18n, and a Medallion data pipeline (Riot API → Cloudflare R2 → Supabase). AI-powered tactical coaching via **Gemini 2.5 Flash** with RAG guardrails; an agentic hybrid-search pipeline (KNN + BM25/RRF) via OpenRAG (Langflow + OpenSearch + Docling) is in active development. Stack: FastAPI, Next.js, Polars, pgvector, GitHub Actions.
- **🕵️ [GNN Fake News](https://github.com/Czar210/GNN-Fake-News):** Academic research project (TCC — PUCSP). Fake news detection on Bluesky via network topology, comparing GCN, GAT, and GraphSAGE architectures against textual baselines. Trained on UPFD FakeNewsNet + GossipCop datasets and applied to real AT Protocol firehose data. Includes ablation studies, cross-dataset benchmarks, GNNExplainer interpretability analysis, multilingual topology tests (PT/EN/DE), and a full interface (Next.js + FastAPI + Supabase). Key finding: topology alone reaches F1=0.81 on GossipCop; dual-model rule (textual + topological) hits F1=0.97. Stack: PyTorch Geometric, sentence-transformers, Docker.
- **📚 [cdia-m7-PUCSP](https://github.com/Czar210/cdia-m7-PUCSP):** PUCSP CDIA M7 coursework. MLOps pipeline with synthetic data generators for credit/churn/fraud domains — scikit-learn models trained and published to [HuggingFace](https://huggingface.co/Zaras210) via GitHub Actions. Also includes a production-grade FastAPI restaurant service with Pydantic v2 and routers.
- **🗄️ [Atlas](https://github.com/Czar210/dynamic-sql-editor):** Open-source headless CMS for modern admin panels, born from a Scientific Initiation (IC) project. Build typed tables visually — each schema becomes a real physical DB table. Features multi-tenant isolation, 3-tier access (master/admin/moderator), JWT + QR Auth, 6 themes × 4 modes, SQL/CSV/XLSX import, and public API toggle. Stack: Next.js, FastAPI, SQLAlchemy, Neon Postgres. Part of **Mora Org**.
- **✍️ [Glyph](https://github.com/Czar210/PEG):** Open-source desktop software for visual authoring and advanced typography (formerly PEG). Currently at Phase 5/9 — export pipeline in development; Phases 0–4 (canvas engine, lettering, GIF, store) are done. Features per-character control, organic text effects (tremor, neon flicker), video-as-fill clipping masks, active pause blocks (VHS noise, black screen), and GPU-accelerated export (NVENC/AMF). Two tracks: **Core** (stable, lightweight) and **Obsidian** (experimental AI video inpainting via VOID Engine, 12GB+ VRAM). Stack: Tauri (Rust), Next.js, Fabric.js, FFmpeg. Part of **Mora Org**.
- **📋 [LattesDirector](https://github.com/Czar210/LattesDirector):** Native desktop app (Tauri v2) that connects your Google Calendar to your Lattes academic CV via a local AI agent (OpenClaw via WebSocket). Monitors diffs between real calendar events and Lattes entries, and presents a side-by-side approval dashboard — no manual bureaucracy. Features glassmorphism UI with Framer Motion, typed OpenClaw contracts (`CalendarEvent`, `LattesSuggestion`, `DiffPayload`), isolated Gov.br auth via InAppBrowser, and a security red-teaming suite (Playwright) that validates auth tokens never leak to `window`. Stack: Rust, React 19, Zustand, Vite, Playwright. Part of **Mora Org**.
- **🎾 [Heimdall](https://github.com/Czar210/Heimdall):** End-to-end tennis analysis pipeline that democratizes Hawk-Eye-style stats using a single phone or YouTube video. Uses **TrackNetV2** (U-Net CNN that processes 3 consecutive frames to track fast, motion-blurred objects — far superior to YOLO for this domain), homography matrices to convert 2D pixel coordinates to real 3D court meters, and a physics engine that detects hits/bounces via velocity derivatives and classifies **topspin vs. slice** via the Magnus effect ($g > 9.8\, m/s^2$ = topspin, $g < 9.8$ = slice). Stack: Python, OpenCV, PyTorch, Pandas, Savitzky-Golay/Kalman filters.
- **🗺️ [Travel-Salesman-Problem](https://github.com/Czar210/Travel-Salesman-Problem):** A collection of heuristic and exact algorithms for the classic TSP, including implementations of greedy nearest-neighbor, 2-opt local search, and dynamic programming approaches.
- **🃏 [Ze_Pelintra](https://github.com/Czar210/Ze-Pelintra):** A study on Parallel Computing and Monte Carlo Tree Search (MCTS) applied to the Brazilian card game "Truco" — exploring how parallelism affects game-tree search depth and decision quality.

---

### 📈 GitHub Stats

<p align="left">
<img src="https://github-readme-stats-theta-hazel-98.vercel.app/api?username=Czar210&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="César's GitHub Stats" height="180px"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Czar210&layout=compact&theme=tokyonight&hide=html,css" alt="Top Languages" height="180px"/>
</p>

---

### 📫 Connect with me:
- **LinkedIn:** [linkedin.com/in/cesarsibila](https://linkedin.com/in/cesarsibila)
- **HuggingFace:** [huggingface.co/Zaras210](https://huggingface.co/Zaras210)
- **Mora Org:** [github.com/Mora-Org](https://github.com/Mora-Org)
- **Email:** [cesarsibila210@gmail.com](mailto:cesarsibila210@gmail.com)

*"Turning raw data into strategic intelligence."*
