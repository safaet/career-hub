# Safaet Jaman Arman

AI/ML Engineer | NLP Researcher | LLM/RAG Engineer

Chandgaon, Chattogram, Bangladesh
esafaetjaman@gmail.com | +8801306726612
[GitHub](https://github.com/safaet) | [LinkedIn](https://linkedin.com/in/safaet-jaman) | [Portfolio](https://safaet.github.io/Personal_portfolio/)

---

## Professional Summary

AI/ML Engineer and NLP researcher with production experience shipping Retrieval-Augmented Generation (RAG) systems and Generative AI workflows for multilingual (Bengali/romanized-Bengali/English) conversational products. Led the end-to-end design of a two-stage retrieval pipeline (bi-encoder + cross-encoder reranking) with a data-calibrated refusal gate, evaluation harness, and observability layer, while directing a 4-person cross-functional delivery team. Co-author of a peer-reviewed paper on antimicrobial resistance (AMR) prediction accepted at ECCT 2026, developed in collaboration with icddr,b, introducing a novel Resistome Burden Index (RBI) feature. Combines a full-stack engineering foundation (Django, FastAPI, PostgreSQL) with applied ML/NLP research, with a focus on low-resource Bengali NLP and medical AI.

---

## Core Technical Skills

### AI / Machine Learning
Scikit-learn, XGBoost, LightGBM, CatBoost, Feature Engineering, Model Ensembling

### Deep Learning
PyTorch, HuggingFace Transformers, PEFT/LoRA, Mixed Precision (AMP), Cosine Learning Rate Scheduling

### NLP
BanglaBERT, XLM-RoBERTa, mBERT, TF-IDF, BPE Tokenization, Sequence Classification, Named Entity Recognition (NER)

### LLM / RAG / Agentic AI
LangChain, LangGraph, FAISS, Retrieval-Augmented Generation (RAG) Pipeline Design, Prompt Engineering, Tool-Use Agents, Intent Routing, LLM Evaluation (RAGAS), LLM Tracing/Observability

### Computer Vision
EfficientNet-B3, ConvNeXt, OpenCV, Albumentations, Image Augmentation

### Multimodal Learning
Late Fusion, Feature Concatenation, Multimodal Transformers

### Backend Engineering
Django, FastAPI, Uvicorn, Pydantic v2, REST APIs, JWT Authentication, Async Request Handling

### Databases
PostgreSQL, SQLAlchemy, MySQL, MongoDB, SQLite, ChromaDB, FAISS

### MLOps / DevOps
Docker, systemd, GitHub Actions, Weights & Biases (wandb), MLflow, HuggingFace Hub, vLLM, AWS

### Data Analysis
Pandas, NumPy, Matplotlib, Seaborn, Plotly, BeautifulSoup (Web Scraping)

### Research & Evaluation
McNemar's Test, Bootstrap Confidence Intervals, Wilcoxon Signed-Rank Test, LaTeX, Statistical Significance Testing

### Tools
Git, GitHub, VSCode, Jupyter, Kaggle, Linux/Ubuntu, Postman, Google Colab, Streamlit

---

## Professional Experience

### Technical Lead, AI/ML — Neuralis AI
Bengali-language RAG chatbot (client project) | Part-time | 10 August 2026 – Present

- Led a 4-person cross-functional team (frontend engineer, two data-collection specialists, one deployment engineer) from architecture through delivery, while personally owning the ML/backend implementation
- Architected the RAG pipeline's core design decisions: PostgreSQL schema, ingestion pipeline, two-stage retrieval (bge-m3 bi-encoder + bge-reranker-v2-m3 cross-encoder reranking), and a data-calibrated refusal gate to suppress hallucinated answers on out-of-scope queries
- Built the evaluation and observability strategy: RAGAS-based faithfulness/relevancy scoring, retrieval and chunking A/B test harnesses, and self-hosted LLM tracing capturing per-stage token cost, latency, and quality
- Directed data-collection workflows across the team for corpus construction from books and web sources
- Owned the GitHub repository and release process, enabling the deployment engineer to ship independently from `main` with no direct handoff friction

### AI Engineer — Neuralis AI
Multilingual Conversational AI Product — RAG Backend | Part-time (~25 hrs/week) | Prior to August 2026

- Engineered a full retrieval pipeline — LLM-based query rewriting (normalizing romanized and English input into the target script, with caching and graceful fallback), bge-m3 multilingual bi-encoder embeddings (1024-dim) with custom paragraph/sentence-aware chunking, and bge-reranker-v2-m3 cross-encoder reranking — supporting native script, romanized, and English queries
- Implemented score-gated grounded generation with strict context-only prompting and inline citations, ensuring generated answers cannot contradict their cited sources and refusing to answer unsupported queries rather than hallucinating
- Designed a deterministic regex-first intent classifier with LLM fallback, routing a single chat endpoint to grounded QA, map-reduce document summarization, stateful persona chat, and grounded recommendation services
- Built the data layer: a normalized relational schema in PostgreSQL with an incremental ingest pipeline, per-record embedding-state tracking, and stale-chunk cleanup for safe re-indexing
- Served the system via async FastAPI, offloading blocking model/LLM calls to a threadpool, with typed request/response schemas, structured error handling, and per-request latency/retrieval-score telemetry
- Built offline evaluation tooling (retrieval-threshold tuning, intent-routing evaluation harness, embedding regression tests) and containerized deployment with Docker, run via systemd

### Junior AI/ML Engineer — Code Owls
Generative AI / LLM Automation Workflows | Full-time | July 2024 – May 2025

- Developed and deployed Generative AI workflows using LangChain and LangSmith, enabling NLP-driven adaptive services with dynamic LLM response pipelines
- Researched and integrated emerging AI technologies and tools, tracking trends in Generative AI and NLP to improve system intelligence and response quality
- Built and maintained AI automation solutions using Python, FastAPI, Git, and Linux, supporting data preprocessing, model integration, and API deployment across the full development lifecycle
- Collaborated with cross-functional teams in an Agile environment, applying structured A/B evaluation and feedback loops to improve AI model accuracy and user experience

---

## Research Experience

### Research Collaborator — icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)

- Developed an ML pipeline for antimicrobial resistance (AMR) phenotype prediction using an SVM-XGBoost ensemble on an icddr,b clinical genomic dataset
- Introduced a novel Resistome Burden Index (RBI) as an interpretable composite feature for genomic ML
- Conducted full statistical significance testing (McNemar's test, Bootstrap confidence intervals, Wilcoxon signed-rank test) for ML model comparison
- Co-authored the resulting paper, accepted at ECCT 2026 (Engineering, Computing & Communication Technologies)

---

## Selected AI / ML Projects

### ResistomeX — AMR Prediction Web App
**Technologies:** Python, Streamlit, Scikit-learn, XGBoost, Pandas, NumPy

- Productized the R-Blend AMR resistance-phenotype ensemble (Decision Tree + Logistic Regression + XGBoost, soft voting, with the RBI feature) from the underlying ECCT 2026 research pipeline into a live, publicly accessible prediction tool
- Refactored a research notebook into four clean, self-contained pipeline notebooks (EDA, preprocessing, training, evaluation) suitable for a production-facing app
- Achieved an average F1 of 0.9421 across 12 antibiotic-pathogen datasets, per the underlying research
- Live deployment: Streamlit Community Cloud (resistomex.streamlit.app) | [GitHub](https://github.com/safaet/ResistomeX)

### AMR Resistome Prediction (ECCT 2026 Paper)
**Technologies:** Python, Scikit-learn, XGBoost, Pandas, NumPy, LaTeX

- Designed an SVM-XGBoost ensemble with a novel Resistome Burden Index (RBI) feature to predict antimicrobial resistance phenotypes from icddr,b clinical genomic data
- Evaluated using accuracy, F1, AUC-ROC, McNemar's test, Bootstrap CI, and Wilcoxon signed-rank testing
- Addressed noisy genomic labels and class imbalance while designing RBI as an interpretable composite feature
- Accepted at ECCT 2026 | [GitHub](https://github.com/safaet/AMR-Prediction)
<!-- TODO: Add verified accuracy/F1 metrics once confirmed for the paper itself (distinct from the ResistomeX app's reported F1) -->

### Multimodal Disaster Severity Classifier
**Technologies:** PyTorch, EfficientNet-B3, XLM-RoBERTa-base, HuggingFace, AdamW, AMP

- Designed and implemented a late-fusion multimodal pipeline (EfficientNet-B3 for vision + XLM-RoBERTa for text) to classify disaster images and text by severity for emergency response prioritization
- Built for the datathon-iiuc-cse-fest-2026 Kaggle competition, handling bilingual (Bengali + English) text, class imbalance, and multimodal alignment
- Evaluated via F1-macro, accuracy, and AUC with 5-fold cross-validation
- Status: Kaggle competition — in progress
<!-- TODO: Add final competition placement/score once the competition concludes -->

### Automatic Question Generator
**Technologies:** FastAPI, Python, Google Colab, Git

- Built an NLP-driven system to generate contextual questions and MCQs from educational content using FastAPI, demonstrating applied Generative AI for educational automation
- Status: Built and demoed (Google Colab)
<!-- TODO: Add GitHub link, dataset source, and evaluation metrics -->

### House Price Prediction
**Technologies:** Python, Scikit-learn, Streamlit, Git

- Developed and deployed a regression-based ML model for house price prediction from property features, live on a production server via Streamlit
<!-- TODO: Add GitHub link, dataset source, and evaluation metrics -->

---

## Additional Engineering Projects

### DevSearch — Developer Portfolio & Skill-Matching Platform
**Technologies:** Django, HTML, CSS, JavaScript, AWS, Git

- Built a full-stack platform helping developers build portfolios and get matched to opportunities based on skills, deployed on AWS
<!-- TODO: Add GitHub link -->

### CricketScrapper
**Technologies:** Python, BeautifulSoup, Git

- Scraped and structured live cricket data from Cricbuzz for analysis and display, demonstrating data pipeline design and web automation
<!-- TODO: Add GitHub link and deployment status -->

---

## Publications

### AMR Prediction via SVM-XGBoost Ensemble with Resistome Burden Index
ECCT 2026 (Engineering, Computing & Communication Technologies) — Accepted, camera-ready submitted

- Collaboration: icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)
- Main contribution: Novel Resistome Burden Index (RBI) feature combined with an SVM-XGBoost ensemble for AMR phenotype prediction
- Repository: [github.com/safaet/AMR-Prediction](https://github.com/safaet/AMR-Prediction)
<!-- TODO: Add co-author names and DOI/arXiv link once available -->

---

## Education

**BSc in Computer Science & Engineering (CSE)**
International Islamic University Chittagong (IIUC) | 2019 – Present (Final Year, Expected Graduation 2026)

Relevant coursework: Data Structures & Algorithms, Machine Learning, Deep Learning, Natural Language Processing, Computer Vision, Data Mining, Database Systems, Operating Systems, Computer Networks, Software Engineering, Statistics & Probability, Linear Algebra

---

## Achievements

- Co-authored a peer-reviewed paper accepted at ECCT 2026 (international conference)
- Collaborated with icddr,b on the first ML-based AMR prediction study using this dataset
- Kaggle: Titanic – Machine Learning from Disaster — achieved Rank 1003 globally
- 4th Place — IIUC Intra-University Programming Contest, Autumn 2022
- Active competitive programmer on Stopstalk and LeetCode

---

## Relevant Coursework & Self-Study

- Completed a self-directed 12-topic AI/ML fundamentals curriculum (~580 hours) covering linear algebra, transformers, RAG, and MLOps
- Practical Deep Learning for Coders (fast.ai) — completed through Part 2
- LangChain for LLM Application Development (DeepLearning.AI) — completed
- LangGraph for multi-agent systems — completed

---

## Research Interests

Low-resource NLP for Bengali; Medical AI and computational biology; Multimodal learning (vision-language fusion, disaster response AI); LLM reasoning and agentic systems (RAG, tool-use, long-context LLMs); ML safety and explainability (SHAP, interpretable ML for healthcare).

---

## Information to Complete

- Verified accuracy/F1 metrics for the ECCT 2026 AMR paper itself (currently unconfirmed — do not confuse with ResistomeX's reported 0.9421 average F1)
- Co-author names and DOI/arXiv link for the ECCT 2026 paper
- GitHub links for: Automatic Question Generator, House Price Prediction, DevSearch, CricketScrapper
- Dataset sources and evaluation metrics for Automatic Question Generator and House Price Prediction
- Final competition score/placement for the Multimodal Disaster Severity Classifier (Kaggle competition currently in progress) and for the IIUC CSE Fest 2026 Datathon
- Full project entries for planned/in-progress work once complete: BanglaBERT fine-tuning (P1), BanglaLex RAG system (P2), MediFlow BD MLOps platform (P3) — not included in this resume as they are not yet built
- Exact start/end dates and any concrete measurable outcomes for the Code Owls role, if available beyond what's documented
