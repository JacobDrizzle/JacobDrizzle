```text
~/portfolio/guest@terminal:$ whoami
Jacob Dorrill — AI Safety & ML Engineer
```

I build machine-learning systems and test how they behave. I'm in the final year of a BSc (Hons) in Software
Development at MTU Cork, with a final-year project in AI agent safety. Before that I shipped RAG, OCR, predictive
models and MCP-backed agents at CompuCal in Cork.

I'm looking for full-time roles in AI safety, ML engineering, software engineering and security.

[jacobdrizzle.dev](https://jacobdrizzle.dev) · [LinkedIn](https://www.linkedin.com/in/jacob-dorrill/) · [jd_git@protonmail.com](mailto:jd_git@protonmail.com)

## What I work on

- **AI safety and evaluation.** My final-year project is in AI agent safety. I'm interested in how to evaluate
  agents and keep tool-using agents within the scope they were given.
- **AI agents with scoped tool access.** MCP servers that gave internal agents real SQL and API access at CompuCal,
  plus multi-agent orchestration with CrewAI. The permissions, tools and evaluation are the hard part.
- **Software security.** Memory-safety exploits and their defences: stack overflows and format-string bugs on 32-bit
  Linux, worked through in GDB, and the mitigations that stop them (ASLR, NX, stack canaries).
- **Production ML.** RAG with pgvector and LangChain, CatBoost/XGBoost/LightGBM models benchmarked against real
  baselines, and OCR extraction from scanned PDFs.

## 🏆 9th ABC Challenge: Joint Gold

**[abc-challenge](https://github.com/JacobDrizzle/abc-challenge)** ·
[interactive 3D visualiser](https://jacobdrizzle.dev/ml/abc-challenge)

Team Motion Pending from MTU took joint first place, with the fewest parameters of any team. The model is a causal
temporal convolutional network that reads 4 s of head orientation from an XR headset and forecasts the next 200 ms,
for users it has never seen. It runs as a stream, one sample per call, and is small enough to run on the headset.

| | |
| --- | ---: |
| Trainable parameters | 7,555 |
| Error at 200 ms, 1,049 unseen test users | 4.50° (hold-last baseline 6.70°) |
| Latency, ONNX Runtime, 1 CPU thread | 35–77 µs |

PyTorch · ONNX Runtime · SO(3) quaternions · mirror-equivariant TCN · Three.js

## Experience

**CompuCal**, Cork: ML features for a regulated calibration-management platform

- RAG over internal documentation with pgvector and LangChain
- OCR pipelines for scanned certificates with Azure Document Intelligence
- Predictive-maintenance models with CatBoost and XGBoost
- MCP servers that gave internal agents real database and API access

## Other projects

- [**FED_Watcher**](https://github.com/JacobDrizzle/FED_Watcher): predicts short-term U.S. stock market moves from
  the sentiment of the Federal Reserve Chair's public announcements.
- [**Semantic-search-Postgres-DB**](https://github.com/JacobDrizzle/Semantic-search-Postgres-DB): semantic search
  over movie plots, with vector embeddings stored in PostgreSQL.
- [**Self-Driving-Car**](https://github.com/JacobDrizzle/Self-Driving-Car): a self-driving car simulation in plain
  JavaScript, with no external libraries.
- [**Portfolio**](https://github.com/JacobDrizzle/Portfolio): source for [jacobdrizzle.dev](https://jacobdrizzle.dev),
  built with Next.js, Tailwind and GSAP.

## Tech

| | |
| --- | --- |
| **ML & AI** | PyTorch, scikit-learn, CatBoost, XGBoost, LightGBM, pandas, NumPy |
| **GenAI & NLP** | LangChain, CrewAI, MCP, FinBERT, Transformers, OpenAI API, Gemini |
| **Backend** | Python, FastAPI, Node.js, TypeScript, Next.js, Go, Rust |
| **Cloud & data** | PostgreSQL, pgvector, Azure, AWS, Docker, Redis, GitHub Actions |
| **Security** | GDB, C, x86 assembly, memory-safety exploits, ASLR / NX / canaries, Linux |

## Education

- **BSc (Hons) Software Development**, Munster Technological University, Cork (final year). Final-year project in
  AI agent safety.
- **QQI Level 6 Advanced Software Development**, with distinction.
