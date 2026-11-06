
# Hi, I'm Katarzyna 👋

**AI/ML Engineering · LLM Systems · NLP · Evaluation**

I build AI and data systems with a focus on **reliability, reproducibility, and measurable results**.

My work combines software engineering with machine learning experiments, LLM applications, semantic algorithms, and data pipelines. I'm particularly interested in what happens after a prototype starts working:

**How do we know that it actually works?**

That means building meaningful baselines, testing unseen cases, investigating failure modes, and improving systems based on evidence.

I'm completing my Master's degree in **Computer Science at Warsaw University of Technology**, specializing in Artificial Intelligence.

## Featured Projects

### [Notes RAG Assistant](https://github.com/kat1478/notes-rag-assistant)

**LLM Engineering · RAG · Evaluation · AWS**

An end-to-end RAG application for querying personal notes with grounded answers, source citations, and refusal behaviour when evidence is insufficient.

- Built a FastAPI backend with semantic search, TF-IDF fallback, context expansion, and multiple LLM providers.
- Developed separate evaluation workflows for retrieval, answer quality, and unseen documents.
- Benchmarked **6 LLMs on 94 questions**, comparing grounding, cost, and latency.
- Integrated an LLM-as-judge calibrated against human assessments.
- Added automated quality gates, Docker support, and AWS Lambda deployment.

**Stack:** `Python` · `FastAPI` · `ChromaDB` · `sentence-transformers` · `OpenRouter` · `Docker` · `AWS`

[Repository](https://github.com/kat1478/notes-rag-assistant) | [Live Demo](https://iwpihtdkkdhsjuo5vinbtg6pty0dsvhz.lambda-url.eu-north-1.on.aws/)

---

### [NeuroFlyNav](https://github.com/kat1478/NeuroFlyNav)

**Computational Neuroscience · Experimental ML · Graph-Based Neural Systems**

A research project investigating whether biological neural connectivity can improve artificial navigation agents.

The system uses the real *Drosophila* central-complex connectome as a recurrent neural reservoir and compares it against controlled alternative networks.

- Constructed a recurrent system using **2,966 neurons and 467,579 connections**.
- Compared biological wiring with shuffled, random, and memoryless baselines.
- Conducted multi-seed experiments, confidence-interval analysis, and follow-up evaluations.
- Investigated the roles of cell-type connectivity, recurrent dynamics, and trainable weights.
- Documented negative results and experimental limitations alongside observed improvements.

**Stack:** `Python` · `NumPy` · `Graph Algorithms` · `Recurrent Networks` · `Statistical Evaluation`

[Repository](https://github.com/kat1478/NeuroFlyNav)

---

### [Advertising Analytics Pipeline](https://github.com/kat1478/advertising-analytics-pipeline)

**Data Engineering · SQL · Data Quality**

A reproducible analytics pipeline transforming advertising events into validated analytical datasets and business reports.

- Implemented deterministic synthetic data generation, ingestion, validation, SQL staging, and analytical marts.
- Calculated advertising metrics including CTR, CPC, conversion rate, and ROAS.
- Developed automated data-quality and metric-consistency tests.
- Added end-to-end testing and GitHub Actions CI.

**Stack:** `Python` · `SQL` · `DuckDB` · `pandas` · `pytest` · `GitHub Actions`

[Repository](https://github.com/kat1478/advertising-analytics-pipeline)

---

### [Evolution Strategies for MuJoCo & HumanoidBench](https://github.com/kat1478/es-mujoco-humanoidbench)

**Reinforcement Learning · Evolutionary Optimization**

An experimental implementation of Evolution Strategies based on Salimans et al. (2017), evaluated on MuJoCo HalfCheetah and HumanoidBench tasks.

- Implemented antithetic sampling, fitness shaping, and observation normalization.
- Conducted optimization experiments across locomotion and manipulation environments.
- Analyzed convergence, performance variability, and computational-budget limitations.

**Stack:** `Python` · `MuJoCo` · `Evolution Strategies` · `Reinforcement Learning`

[Repository](https://github.com/kat1478/es-mujoco-humanoidbench)

## Other Projects

- **[SPADE Sequential Pattern Mining](https://github.com/kat1478/SPADE_project)** — Implementation and comparison of DFS, BFS, and constrained sequential pattern mining algorithms, with correctness tests and reproducible runtime statistics.
- **[BERT Semantic Similarity](https://github.com/kat1478/nlp-semantic-similarity-bert)** — Fine-tuning BERT for question-pair similarity classification, with evaluation using classification metrics and ROC analysis.
- **[AI Car Price Data Analyst](https://github.com/kat1478/ai-data-analyst)** — Automated EDA, regression modeling, evaluation, and reporting through a Python CLI and Streamlit dashboard.

## Private Research & Development

### Palimpsest — Semantic Document Alignment

An auditable document comparison system combining transformer embeddings, exact-text anchors, and order-preserving sequence alignment.

- Developed paragraph-level and sentence-level alignment workflows.
- Designed baseline comparisons, calibration protocols, and held-out evaluation.
- Implemented reproducible reports preserving model versions, algorithm parameters, and source references.

**Focus:** `NLP` · `Semantic Alignment` · `Needleman–Wunsch` · `Evaluation`

### PACKEN — Multi-Agent AI Evaluation

An experimental framework for defensively evaluating controlled LLM-based multi-agent systems.

- Designed a multi-agent architecture with probing, strategy, and oversight responsibilities.
- Developed structured message contracts and traceable execution records.
- Implemented evaluation workflows for adversarial testing and failure analysis.

**Focus:** `Agentic AI` · `Adversarial Testing` · `LLM Evaluation` · `Multi-Agent Systems`

*Both projects are maintained in private repositories.*

## Technical Stack

| Area | Technologies |
| --- | --- |
| **AI / ML** | Python, PyTorch, Transformers, scikit-learn, sentence-transformers, RAG, LLM evaluation |
| **Backend & Data** | FastAPI, REST APIs, SQL, PostgreSQL, DuckDB, ChromaDB, pandas |
| **Engineering** | pytest, Ruff, mypy, Git, GitHub Actions, Docker, AWS Lambda, Linux / WSL |
| **AI Development Tools** | Claude Code, Codex, Ollama, OpenRouter |

## How I Work

I prefer short, verifiable development cycles:

**Build → Establish baselines → Evaluate → Investigate failures → Improve → Re-evaluate**

My approach emphasizes:

- **Evidence over assumptions** — comparing methods against measurable baselines.
- **Reproducibility** — recording configurations, model versions, and experimental conditions.
- **Meaningful evaluation** — separating development and calibration from held-out validation.
- **Engineering quality** — automated tests, CI, static analysis, and independent review.
- **Transparent limitations** — documenting negative results and known failure modes.

I also use AI-assisted engineering workflows with separate responsibilities for planning, implementation, and independent verification.

## What I'm Looking For

I'm interested in opportunities involving **Applied AI Engineering, LLM & RAG Systems, AI Evaluation, Agentic AI, ML Engineering, NLP, and AI Backend Development**.

I particularly enjoy problems combining software engineering with experimentation and practical machine learning.

**Based in Warsaw, Poland** · Open to remote and hybrid opportunities.

**Contact:** [Email](mailto:katarzynakadyszewska@gmail.com) · [LinkedIn](https://www.linkedin.com/in/katarzyna-kadyszewska)
