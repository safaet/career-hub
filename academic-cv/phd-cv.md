# Safaet Jaman Arman

Chattogram, Bangladesh
esafaetjaman@gmail.com | +8801306726612
[GitHub](https://github.com/safaet) | [LinkedIn](https://linkedin.com/in/safaet-jaman) | [Portfolio](https://safaet.github.io/Personal_portfolio/)

---

## Research Interests

- Low-resource NLP, with a focus on Bengali language modeling and multilingual transfer learning
- Medical AI and computational biology, including antimicrobial resistance (AMR) prediction and genomic machine learning
- Retrieval-augmented generation and LLM reasoning, including grounding, evaluation, and refusal mechanisms
- Multimodal learning for disaster-response applications in low-resource settings

---

## Education

**BSc in Computer Science & Engineering** (in progress)
International Islamic University Chittagong (IIUC), Chittagong, Bangladesh
2019 – Present | Final-year undergraduate student; expected graduation 2026

Undergraduate research: AMR prediction via an SVM-XGBoost ensemble, conducted in collaboration with icddr,b (see Research Experience)

Relevant coursework: Machine Learning, Deep Learning, Natural Language Processing, Data Structures & Algorithms, Statistics & Probability, Linear Algebra

---

## Publications

### AMR Prediction via SVM-XGBoost Ensemble with Resistome Burden Index
**Venue:** ECCT 2026 (Engineering, Computing & Communication Technologies)
**Status:** Accepted — camera-ready submitted
**Collaboration:** icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)
**Repository:** https://github.com/safaet/AMR-Prediction

*Complete author list not yet confirmed for this CV — see Before Submission checklist.*

---

## Research Experience

### Research Collaboration — icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)
Dates not documented

- Investigated antimicrobial resistance (AMR) phenotype prediction from clinical genomic data
- Designed the Resistome Burden Index (RBI), an interpretable composite feature intended to address noisy genomic labels and class imbalance in the dataset
- Developed an SVM-XGBoost ensemble incorporating the RBI feature for phenotype classification
- Conducted statistical evaluation of model comparisons using McNemar's test, bootstrap confidence intervals, and Wilcoxon signed-rank testing
- Co-authored the resulting manuscript, accepted at ECCT 2026

---

## Selected Research Projects

### ResistomeX — AMR Prediction Web Application
**Status:** Completed and deployed
**Repository / Demo:** https://github.com/safaet/ResistomeX | resistomex.streamlit.app

- Deployed a separate R-Blend ensemble (Decision Tree, Logistic Regression, and XGBoost combined via soft voting, incorporating the RBI feature) as a publicly accessible prediction tool, distinct from the SVM-XGBoost ensemble used in the ECCT 2026 paper
- Refactored an exploratory research notebook into four self-contained pipeline stages: EDA, preprocessing, training, and evaluation
- Reports an average F1 of 0.9421 across 12 antibiotic-pathogen datasets, per the underlying research pipeline (this figure applies to the R-Blend ensemble in this application, not the ECCT 2026 paper's ensemble)

### Multimodal Disaster Severity Classification
**Status:** In progress (Kaggle competition, datathon-iiuc-cse-fest-2026)

- Designing a late-fusion multimodal architecture (EfficientNet-B3 for vision, XLM-RoBERTa for text) to classify disaster images and text by severity
- Evaluating with F1-macro, accuracy, and AUC-ROC under 5-fold cross-validation
- Addressing bilingual (Bengali/English) text and class imbalance in the dataset

---

## Relevant Professional Experience

### Technical Lead, AI/ML — Neuralis AI
Part-time | August 2026 – Present

- Directed the architectural design of a two-stage retrieval pipeline (bi-encoder retrieval with bge-m3, cross-encoder reranking with bge-reranker-v2-m3) with a data-calibrated refusal mechanism that withholds generation when supporting evidence is insufficient, rather than eliminating hallucination outright
- Designed the evaluation methodology for the system: RAGAS-based faithfulness/relevancy scoring and retrieval/chunking A/B evaluation
- Coordinated a four-person team across frontend, data collection, and deployment for a multilingual (Bengali/romanized-Bengali/English) corpus

### AI Engineer — Neuralis AI
Part-time | Prior to August 2026 (exact start date not documented)

- Designed and evaluated a retrieval pipeline combining bge-m3 multilingual bi-encoder embeddings with paragraph/sentence-aware chunking and bge-reranker-v2-m3 cross-encoder reranking
- Built an incremental data-ingestion pipeline with per-record embedding-state tracking, supporting safe re-indexing for a growing multilingual corpus
- Built offline evaluation tooling for retrieval-threshold calibration and embedding regression testing

### Junior AI/ML Engineer — Code Owls
Full-time | July 2024 – May 2025

- Developed and evaluated Generative AI workflows using LangChain and LangSmith, including structured A/B evaluation of model outputs

---

## Technical and Research Skills

**Programming:** Python, SQL, Bash, C/C++

**Machine Learning and Deep Learning:** Scikit-learn, XGBoost, PyTorch, HuggingFace Transformers, PEFT/LoRA, model ensembling, feature engineering

**NLP and Multimodal Learning:** BanglaBERT, XLM-RoBERTa, mBERT, sequence classification, late-fusion multimodal architectures

**LLMs and Retrieval:** LangChain, FAISS, retrieval-augmented generation pipeline design, cross-encoder reranking, prompt engineering

**Experimental Design and Statistical Evaluation:** Cross-validation, McNemar's test, bootstrap confidence intervals, Wilcoxon signed-rank test, retrieval/generation A/B evaluation

**Research Software and Deployment:** Git/GitHub, Docker, FastAPI, Streamlit, PostgreSQL

---

## Honors and Awards

- 4th Place — IIUC Intra-University Programming Contest, Autumn 2022
- Kaggle: Titanic – Machine Learning from Disaster — leaderboard placement of Rank 1003 (exact date not documented)
