Hi, I'm Katarzyna 👋

AI/ML Engineering · LLM Systems · NLP · AI Evaluation

I build AI and data systems designed to be tested, measured, and improved — not just demonstrated.

My work spans LLM applications, semantic algorithms, machine learning experiments, computational neuroscience, and data engineering.

I'm especially interested in the question that comes after building a working prototype:

How do we know that it actually works?

For me, that means establishing meaningful baselines, designing controlled experiments, evaluating on unseen data, investigating failure modes, and making results reproducible.

I'm completing my Master's degree in Computer Science at Warsaw University of Technology, specializing in Artificial Intelligence.

🔬 Featured Projects

📚 "Notes RAG Assistant" (https://github.com/kat1478/notes-rag-assistant)

LLM Engineering · RAG · Evaluation · AWS

An end-to-end Retrieval-Augmented Generation application for querying personal notes with grounded answers, explicit source citations, and refusal behaviour when evidence is insufficient.

- Built a FastAPI backend with semantic retrieval, TF-IDF fallback, context expansion, persistent vector storage, and interchangeable LLM providers.
- Designed separate evaluation pipelines for retrieval quality, answer quality, and previously unseen documents.
- Benchmarked 6 LLMs on 94 questions, comparing answer grounding, cost, and latency.
- Integrated an LLM-as-judge calibrated against human assessments.
- Implemented automated quality gates, Docker support, and an AWS Lambda deployment.

Stack: "Python" · "FastAPI" · "ChromaDB" · "sentence-transformers" · "OpenRouter" · "Ollama" · "Docker" · "AWS Lambda"

"Repository" (https://github.com/kat1478/notes-rag-assistant) · "Live Demo" (https://iwpihtdkkdhsjuo5vinbtg6pty0dsvhz.lambda-url.eu-north-1.on.aws/)

---

🧠 "NeuroFlyNav" (https://github.com/kat1478/NeuroFlyNav)

Computational Neuroscience · Experimental ML · Graph-Based Neural Systems

A research project investigating whether biological neural connectivity can improve artificial navigation agents.

The system uses the real Drosophila central-complex connectome as a recurrent neural reservoir and compares it against controlled alternative network structures.

- Constructed a recurrent network from 2,966 neurons and 467,579 connections.
- Compared biological connectivity with degree-preserving shuffled graphs, random recurrent networks, and memoryless agents.
- Conducted multi-seed experiments, confidence-interval analysis, and follow-up evaluations on fresh seeds.
- Investigated how cell-type connectivity, recurrent dynamics, and trainable weights influence navigation performance.
- Documented negative results, experimental limitations, and alternative explanations.

Research focus: understanding whether observed improvements come from biological connectivity itself, network structure, or the dynamics used to process information.

Stack: "Python" · "NumPy" · "Graph Algorithms" · "Recurrent Neural Networks" · "Statistical Evaluation"

"Repository" (https://github.com/kat1478/NeuroFlyNav)

---

📊 "Advertising Analytics Pipeline" (https://github.com/kat1478/advertising-analytics-pipeline)

Data Engineering · SQL · Data Quality · CI/CD

A reproducible end-to-end analytics pipeline for transforming advertising campaign data into validated analytical datasets and business reports.

- Implemented deterministic synthetic data generation, ingestion, validation, SQL staging, and analytical marts.
- Designed campaign-performance metrics including CTR, CPC, conversion rate, and ROAS.
- Developed automated tests for data consistency, attribution assumptions, and financial metric correctness.
- Built reproducible reporting workflows and continuous integration with GitHub Actions.

Stack: "Python" · "SQL" · "DuckDB" · "pandas" · "pytest" · "GitHub Actions"

"Repository" (https://github.com/kat1478/advertising-analytics-pipeline)

---

🧬 "Evolution Strategies for MuJoCo & HumanoidBench" (https://github.com/kat1478/es-mujoco-humanoidbench)

Reinforcement Learning · Evolutionary Optimization · Experimental ML

An experimental implementation of Evolution Strategies based on Salimans et al. (2017), evaluated on MuJoCo HalfCheetah and HumanoidBench environments.

- Implemented Evolution Strategies with antithetic sampling, fitness shaping, and observation normalization.
- Conducted experiments across locomotion and manipulation environments.
- Investigated convergence stability, optimization behaviour, and computational-budget limitations.
- Documented performance differences and limitations of partial experimental replication.

Stack: "Python" · "MuJoCo" · "Evolution Strategies" · "Reinforcement Learning"

"Repository" (https://github.com/kat1478/es-mujoco-humanoidbench)

🧪 Additional Projects

🔎 "SPADE Sequential Pattern Mining" (https://github.com/kat1478/SPADE_project)

Implemented and experimentally compared depth-first, breadth-first, and constrained SPADE variants for sequential pattern mining.

Focused on algorithm correctness, consistency checks, execution statistics, and reproducible experiments.

"Python" · "Algorithms" · "Sequential Pattern Mining" · "pytest"

🧠 "BERT Semantic Similarity" (https://github.com/kat1478/nlp-semantic-similarity-bert)

Fine-tuned BERT for semantic similarity classification using Quora Question Pairs.

Implemented data preprocessing, model training, and evaluation using classification metrics, confusion matrices, and ROC analysis.

"PyTorch" · "BERT" · "Transformers" · "scikit-learn"

📈 "AI Car Price Data Analyst" (https://github.com/kat1478/ai-data-analyst)

An automated data analysis and machine learning workflow combining exploratory data analysis, regression modeling, evaluation, and interactive reporting.

Includes a Python CLI, Streamlit dashboard, automated tests, and reproducible data-processing pipelines.

"Python" · "pandas" · "scikit-learn" · "Streamlit" · "pytest"

🔐 Private Research & Development

Alongside my public portfolio, I work on experimental AI systems and research-oriented engineering projects.

Palimpsest — Semantic Document Alignment

NLP · Algorithm Engineering · Evaluation

An auditable semantic document comparison system combining transformer embeddings, exact-text anchors, and order-preserving sequence alignment.

- Developed paragraph-level and sentence-level alignment workflows.
- Designed baseline comparisons, parameter calibration, and held-out evaluation protocols.
- Implemented structured reports preserving source references, model revisions, algorithm parameters, and reproducibility metadata.
- Explored the distinction between semantic correspondence and actual meaning equivalence.

"Python" · "sentence-transformers" · "Needleman–Wunsch" · "pytest" · "mypy"

PACKEN — Multi-Agent AI Evaluation

Agentic AI · Adversarial Testing · AI Safety Evaluation

An experimental framework for defensively evaluating controlled LLM-based multi-agent systems.

- Designed a multi-agent evaluation architecture with specialized probing, strategy, and oversight responsibilities.
- Developed structured interaction contracts and traceable execution records.
- Implemented evaluation workflows for analyzing adversarial test outcomes and system behaviour.
- Explored repeatable testing, scoring, and failure analysis for agentic systems.

"Python" · "LLM APIs" · "Multi-Agent Systems" · "Evaluation Frameworks" · "pytest"

Both projects are maintained in private repositories.

🛠️ Technical Stack

AI & Machine Learning

"Python" · "PyTorch" · "Transformers" · "scikit-learn" · "sentence-transformers" · "RAG" · "Embeddings" · "Vector Search" · "LLM Evaluation"

Backend & Data

"FastAPI" · "REST APIs" · "SQL" · "PostgreSQL" · "DuckDB" · "ChromaDB" · "pandas"

Engineering & Infrastructure

"pytest" · "Ruff" · "mypy" · "Git" · "GitHub Actions" · "Docker" · "AWS Lambda" · "Linux / WSL" · "Conda / Mamba"

LLM Tools & Workflows

"Claude Code" · "Codex" · "Ollama" · "OpenRouter" · "AI-Assisted Development"

🧭 How I Work

I approach engineering and research as an iterative process:

Build → Establish baselines → Evaluate → Investigate failures → Improve → Re-evaluate

Some principles I follow:

- Evidence over assumptions — compare approaches against measurable baselines rather than relying on intuition.
- Reproducibility — document configurations, model versions, evaluation protocols, and experimental conditions.
- Meaningful evaluation — separate development and calibration from held-out validation.
- Engineering quality — use automated testing, static analysis, CI, and independent code review.
- Transparent limitations — document negative results, failure modes, and conditions under which conclusions may not generalize.

I also use AI-assisted engineering workflows with separate responsibilities for planning, implementation, and independent verification.

The goal is not simply to generate code faster, but to make development more structured, testable, and traceable.

🎯 Areas of Interest

I'm interested in engineering and research opportunities involving:

Applied AI Engineering · LLM & RAG Systems · AI Evaluation · Agentic AI · ML Engineering · NLP · AI Backend · Data & AI Systems

I particularly enjoy problems that combine software engineering, experimentation, and practical machine learning.

📍 Warsaw, Poland · Open to remote and hybrid opportunities

📧 Email: "katarzynakadyszewska@gmail.com" (mailto:katarzynakadyszewska@gmail.com)

🔗 LinkedIn: "katarzyna-kadyszewska" (https://www.linkedin.com/in/katarzyna-kadyszewska)