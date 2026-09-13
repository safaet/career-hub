# Safaet Jaman Arman

AI/ML Researcher | NLP Researcher | LLM/RAG Engineer

Chandgaon, Chattogram, Bangladesh
esafaetjaman@gmail.com | +8801306726612
[GitHub](https://github.com/safaet) | [LinkedIn](https://linkedin.com/in/safaet-jaman) | [Portfolio](https://safaet.github.io/Personal_portfolio/)

---

## Research Profile

Final-year Computer Science and Engineering researcher with a peer-reviewed publication (ECCT 2026) on antimicrobial resistance (AMR) phenotype prediction, developed in collaboration with icddr,b, introducing a novel Resistome Burden Index (RBI) feature within an SVM-XGBoost ensemble. Research and engineering work spans low-resource Bengali NLP, retrieval-augmented generation (RAG) system design and evaluation, and multimodal learning for disaster response. Background combines a production software-engineering foundation (Django, FastAPI, PostgreSQL) with applied ML/NLP research, evaluated using standard statistical significance testing (McNemar's test, Bootstrap confidence intervals, Wilcoxon signed-rank test).

---

## Research Interests

- Low-resource NLP — Bengali language models, multilingual transfer learning
- Medical AI and computational biology — antimicrobial resistance (AMR) prediction, clinical NLP, genomic machine learning
- Multimodal learning — vision-language fusion, disaster-response AI
- LLM reasoning and agentic systems — retrieval-augmented generation, tool-use, long-context LLMs
- ML safety and explainability — interpretable ML for healthcare (SHAP)

---

## Education

### BSc in Computer Science & Engineering
International Islamic University Chittagong (IIUC), Chittagong, Bangladesh
2019 – Present (Final Year; Expected Graduation 2026)

Relevant coursework: Machine Learning, Deep Learning, Natural Language Processing, Computer Vision, Data Mining, Statistics & Probability, Linear Algebra, Data Structures & Algorithms, Database Systems, Operating Systems, Computer Networks, Software Engineering

---

## Publications

### AMR Prediction via SVM-XGBoost Ensemble with Resistome Burden Index

**Venue:** ECCT 2026 (Engineering, Computing & Communication Technologies)
**Status:** Accepted — camera-ready submitted
**Collaboration:** icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)
**Repository:** [github.com/safaet/AMR-Prediction](https://github.com/safaet/AMR-Prediction)

**Key Contributions**
- Introduced the Resistome Burden Index (RBI), a novel interpretable composite feature for AMR phenotype prediction from genomic data
- Designed an SVM-XGBoost ensemble incorporating the RBI feature
- Evaluated model performance using accuracy, F1, AUC-ROC, McNemar's test, Bootstrap confidence intervals, and Wilcoxon signed-rank testing

<!-- TODO: Add complete author list, DOI/arXiv link, and publication date once available -->

---

## Research Experience

### Research Collaborator — icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)

- Investigated antimicrobial resistance (AMR) phenotype prediction from clinical genomic data using ensemble machine learning
- Developed the Resistome Burden Index (RBI), an interpretable composite feature designed to address noisy genomic labels and class imbalance
- Designed and trained an SVM-XGBoost ensemble on the icddr,b genomic dataset
- Conducted statistical significance testing (McNemar's test, Bootstrap confidence intervals, Wilcoxon signed-rank test) to validate model comparisons
- Co-authored the resulting paper, accepted at ECCT 2026

<!-- TODO: Add exact collaboration dates and supervisor/PI name if applicable -->

---

## Research Projects

### AMR Resistome Prediction (ECCT 2026 Paper)

**Research Area:** Computational biology / genomic machine learning
**Role:** ML Engineer & Co-Author
**Technologies:** Python, Scikit-learn, XGBoost, Pandas, NumPy, LaTeX
**Status:** Accepted (ECCT 2026)
**Repository:** [github.com/safaet/AMR-Prediction](https://github.com/safaet/AMR-Prediction)

- Investigated antimicrobial resistance phenotype prediction from icddr,b clinical genomic data
- Designed an SVM-XGBoost ensemble with the novel Resistome Burden Index (RBI) feature to address noisy labels and class imbalance
- Evaluated using accuracy, F1, AUC-ROC, and statistical significance testing (McNemar's, Bootstrap CI, Wilcoxon signed-rank)
<!-- TODO: Add verified accuracy/F1 metrics for the paper's reported results -->

### ResistomeX — AMR Prediction Web Application

**Research Area:** Applied computational biology / model deployment
**Role:** Solo developer — productized the R-Blend ensemble from the AMR research pipeline
**Technologies:** Python, Streamlit, Scikit-learn, XGBoost, Pandas, NumPy
**Status:** Deployed
**Repository / Demo:** [github.com/safaet/ResistomeX](https://github.com/safaet/ResistomeX) | resistomex.streamlit.app

- Translated the R-Blend ensemble (Decision Tree, Logistic Regression, and XGBoost via soft voting, with the RBI feature) from the ECCT 2026 research pipeline into a publicly accessible prediction tool
- Refactored the research notebook into four self-contained pipeline stages (EDA, preprocessing, training, evaluation)
- Reports an average F1 of 0.9421 across 12 antibiotic-pathogen datasets, per the underlying research

### Multimodal Disaster Severity Classification

**Research Area:** Multimodal learning / disaster-response AI
**Role:** Solo — full pipeline design and implementation
**Technologies:** PyTorch, EfficientNet-B3, XLM-RoBERTa-base, HuggingFace, AdamW, mixed-precision training
**Status:** In progress (Kaggle competition, datathon-iiuc-cse-fest-2026)

- Designed a late-fusion multimodal architecture (EfficientNet-B3 for vision, XLM-RoBERTa for text) for disaster-severity classification from bilingual (Bengali/English) image-text data
- Evaluated using F1-macro, accuracy, and AUC-ROC with 5-fold cross-validation
- Addressing class imbalance and multimodal alignment across languages
<!-- TODO: Add final competition score/placement once concluded -->

---

## Research in Progress

- **Multimodal Disaster Severity Classification** — late-fusion vision-language model (EfficientNet-B3 + XLM-RoBERTa) for bilingual disaster-response classification; Kaggle competition ongoing

---

## Planned Research

- BanglaLex — retrieval-augmented generation system for Bengali legal document question answering (planned publication)
- Benchmark study of Bengali NLP models on clinical/medical text (planned publication)
- Multimodal disaster severity classification extended with bilingual (Bengali-English) data (planned publication)
- MediFlow BD — medical AI MLOps platform (planned; not yet started)

---

## Technical Skills

### Programming
Python (Advanced), JavaScript, SQL, Bash/Shell, LaTeX, C/C++

### Machine Learning
Scikit-learn, XGBoost, LightGBM, CatBoost, feature engineering, model ensembling

### Deep Learning
PyTorch, HuggingFace Transformers, PEFT/LoRA, mixed-precision training (AMP), cosine learning-rate scheduling

### NLP
BanglaBERT, XLM-RoBERTa, mBERT, TF-IDF, BPE tokenization, sequence classification, named entity recognition (NER)

### LLM / RAG
LangChain, LangGraph, FAISS, retrieval-augmented generation (RAG) pipeline design, prompt engineering, tool-use agents

### Computer Vision
EfficientNet-B3, ConvNeXt, OpenCV, Albumentations, image augmentation

### Multimodal Learning
Late fusion, feature concatenation, multimodal transformers

### Research & Evaluation
McNemar's test, Bootstrap confidence intervals, Wilcoxon signed-rank test, cross-validation, retrieval/chunking A/B evaluation, RAGAS-based faithfulness and relevancy scoring

### Data Analysis
Pandas, NumPy, Matplotlib, Seaborn, Plotly, BeautifulSoup (web scraping)

### MLOps / Deployment
Docker, systemd, GitHub Actions, Weights & Biases (wandb), MLflow, HuggingFace Hub, vLLM

### Research Tools
LaTeX, Zotero, ArXiv, Google Scholar, Semantic Scholar

### Systems & Backend Engineering
Django, FastAPI, PostgreSQL, SQLAlchemy, ChromaDB, async API design

---

## Professional Experience

### Technical Lead, AI/ML — Neuralis AI
Bengali-language RAG chatbot (client project) | Part-time | 10 August 2026 – Present

- Directed the architectural design of a two-stage retrieval-augmented generation (RAG) system, integrating a bi-encoder retriever (bge-m3) with a cross-encoder reranker (bge-reranker-v2-m3) and a data-calibrated refusal mechanism constraining generation to supported, verifiable answers
- Designed an evaluation and observability methodology for the pipeline: RAGAS-based faithfulness/relevancy scoring, retrieval and chunking A/B evaluation, and per-stage tracing of token cost, latency, and output quality
- Coordinated a four-person interdisciplinary team (frontend engineering, data collection, deployment), directing corpus-construction workflows for a low-resource, multilingual (Bengali/romanized-Bengali/English) domain

### AI Engineer — Neuralis AI
Multilingual Conversational AI Product — RAG Backend | Part-time | Prior to August 2026

- Developed a multilingual query-understanding component using LLM-based query rewriting to normalize romanized and English input into the target script
- Implemented and evaluated a two-stage retrieval pipeline combining bge-m3 multilingual bi-encoder embeddings (1024-dimensional) with paragraph/sentence-aware chunking, and bge-reranker-v2-m3 cross-encoder re-scoring
- Designed a score-gated grounded-generation mechanism constraining answers to remain consistent with cited source passages, refusing generation when supporting evidence was insufficient
- Designed a deterministic regex-first intent classification system with LLM fallback, dispatching queries across grounded question answering, document summarization, persona-based dialogue, and recommendation tasks
- Built offline evaluation tooling for retrieval-threshold calibration, intent-routing accuracy, and embedding regression testing

### Junior AI/ML Engineer — Code Owls
Generative AI / LLM Automation Workflows | Full-time | July 2024 – May 2025

- Developed and evaluated Generative AI workflows using LangChain and LangSmith for adaptive, LLM-driven service pipelines
- Investigated emerging techniques in Generative AI and NLP to inform system-design decisions
- Applied structured A/B evaluation methodology within an Agile development process to assess model accuracy and response quality

---

## Academic & Research Achievements

- Co-authored a peer-reviewed paper accepted at ECCT 2026 (international conference)
- Collaborated with icddr,b on the first ML-based AMR prediction study conducted on this dataset
- Kaggle: Titanic – Machine Learning from Disaster — achieved Rank 1003 globally
- 4th Place — IIUC Intra-University Programming Contest, Autumn 2022

---

## Conferences & Presentations

- ECCT 2026 (Engineering, Computing & Communication Technologies) — paper accepted
<!-- TODO: Add presentation date/location once confirmed; do not claim presentation until it occurs -->

---

## Leadership & Service

### Technical Team Leadership — Neuralis AI

- Directed a four-person cross-functional team, coordinating technical architecture decisions, data-collection methodology, and evaluation strategy for a multilingual RAG system (see Professional Experience for technical detail)

---

## Certifications & Relevant Self-Study

- Completed a self-directed 12-topic AI/ML fundamentals curriculum (~580 hours) covering linear algebra, transformers, RAG, and MLOps
- Practical Deep Learning for Coders (fast.ai) — completed through Part 2
- LangChain for LLM Application Development (DeepLearning.AI) — completed
- LangGraph for multi-agent systems — completed

---

## Research Direction

My research direction centers on low-resource Bengali NLP and medical AI/computational biology, building on the ECCT 2026 collaboration with icddr,b on antimicrobial resistance prediction. Planned next steps include Bengali biomedical NLP (where no large annotated clinical corpus currently exists), multimodal learning for disaster response in South Asian low-resource settings, and retrieval-augmented and agentic LLM systems. The long-term goal is a PhD in AI/ML with a focus on these areas, followed by a research career addressing problems specific to South Asia.

---

## References

References available upon request.

---

## Information to Complete

- Complete author list and DOI/arXiv link for the ECCT 2026 paper
- Exact dates for the icddr,b research collaboration, and supervisor/PI name if applicable
- Verified accuracy/F1 metrics for the ECCT 2026 paper's own reported results (distinct from ResistomeX's reported 0.9421 average F1)
- Final competition score/placement for the Multimodal Disaster Severity Classification project (Kaggle competition in progress) and the IIUC CSE Fest 2026 Datathon
- Presentation date/location for ECCT 2026, once confirmed
- Verified reference contacts (name, title, institution, email) for future applications
