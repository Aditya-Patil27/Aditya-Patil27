# Aditya Patil

Machine learning and AI backend engineer. Pune, India.

I work on the layer between a model and a system people can actually rely on — training and adapting models, then building the retrieval, memory, and orchestration around them. Most of what I build is generative-AI infrastructure with a fair amount of classical ML and computer vision underneath.

Currently interested in agent memory architectures that go beyond flat vector recall, and in retrieval pipelines that survive contact with messy real-world documents.

---

## Selected work

**[MDAV](https://github.com/Aditya-Patil27/MDAV)** — Multimodal document verification

Multi-signal authentication for government-issued documents. Visual and textual evidence are fused into a single verification verdict, with a tamper-evident audit trail behind it. Built as an academic project under Prof. Dr. Jyoti Kanjalkar.
`PyTorch` · `FastAPI` · `Next.js 14` · `PostgreSQL`

**[Chimera](https://github.com/Aditya-Patil27/chimera)** — An LLM council for email

Gmail-integrated client that routes each thread through a three-agent council — Drafter, then Critic, then Judge — instead of a single completion. Fast extractive summaries per thread, RAG over email history, and a background queue for sync.
`NestJS` · `FastAPI` · `React` · `RAG`

**[Universal Memory Agent](https://github.com/Aditya-Patil27/universal-memory-agent)** — Multi-agent orchestration with persistent memory

Supervisor, Coder, Researcher, and Verifier agents sharing conversation memory that survives restarts. Handles request routing between agents and rotates API keys automatically across providers.
`Python` · `Supabase` · `Groq` · `FastAPI`

**[BlueGuard](https://github.com/Aditya-Patil27/marine_gurad)** — Maritime anomaly detection

Vessel monitoring over live AIS streams. Scores risk per vessel, flags route deviations from behavioural baselines, and detects dark vessels — ships that switch off their transponders, a common signal of illegal fishing.
`Python` · `Anomaly detection` · `Geospatial`

**[Hybrid PDF + Web QA](https://github.com/Aditya-Patil27/llm)** — Local-first retrieval

Extracts PDFs with PyMuPDF, embeds with `all-MiniLM-L6-v2`, indexes in FAISS, and fuses those hits with live web results before answering through a local Mistral-7B-Instruct. Runs fully offline, no API keys.
`FAISS` · `Sentence-Transformers` · `Mistral-7B` · `Streamlit`

**[CycleGAN](https://github.com/Aditya-Patil27/CYCLE_GAN)** — Unpaired image-to-image translation

CycleGAN written from scratch for the vangogh2photo task. Custom generator and discriminator, trained with cycle-consistency loss on unpaired domains.
`PyTorch` · `GANs` · `Computer vision`

---

## Working with

Python, PyTorch, scikit-learn, OpenCV, FAISS, Sentence-Transformers, Hugging Face Transformers
FastAPI, Flask, Node, NestJS, PostgreSQL, Supabase, Redis, Docker
TypeScript, React, Next.js
C++, Java

---

## Currently

Reading and building around inference optimisation — quantisation, batching, KV-cache reuse — and distributed multi-GPU training. Open to collaborating on applied ML and open-source agent tooling.

Happy to talk about retrieval pipelines, vector search, LLM routing, or anything PyTorch.

---

[Email](mailto:iadityapatil27@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aditya-patil7593/)
