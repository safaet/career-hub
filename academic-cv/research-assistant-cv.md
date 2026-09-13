# Safaet Jaman Arman

Chattogram, Bangladesh
esafaetjaman@gmail.com | +8801306726612
[GitHub](https://github.com/safaet) | [LinkedIn](https://linkedin.com/in/safaet-jaman) | [Portfolio](https://safaet.github.io/Personal_portfolio/)

---

## Research Summary

Final-year Computer Science and Engineering student with research experience in antimicrobial resistance (AMR) phenotype prediction, conducted in collaboration with icddr,b, resulting in a paper accepted at ECCT 2026 that introduces a novel Resistome Burden Index (RBI) feature within an SVM-XGBoost ensemble. Experienced in statistical model evaluation (McNemar's test, bootstrap confidence intervals, Wilcoxon signed-rank testing), multilingual NLP and retrieval system development, and building reproducible research software, including deployment of research code as a public web application.

---

## Education

**BSc in Computer Science & Engineering** (in progress)
International Islamic University Chittagong (IIUC), Chittagong, Bangladesh
2019 – Present | Final-year undergraduate student; expected graduation 2026

Undergraduate research: AMR prediction via an SVM-XGBoost ensemble, conducted in collaboration with icddr,b (see Research Experience)

Relevant coursework: Machine Learning, Deep Learning, Natural Language Processing, Data Structures & Algorithms, Statistics & Probability, Linear Algebra

---

## Research Experience

### Research Collaboration — icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)
Dates not documented

- Investigated antimicrobial resistance (AMR) phenotype prediction from clinical genomic data
- Engineered the Resistome Burden Index (RBI), an interpretable composite feature designed to address noisy genomic labels and class imbalance in the dataset
- Implemented and trained an SVM-XGBoost ensemble model incorporating the RBI feature for phenotype classification
- Conducted statistical evaluation of model comparisons using McNemar's test, bootstrap confidence intervals, and Wilcoxon signed-rank testing
- Co-authored the resulting manuscript, accepted at ECCT 2026

---

## Publications

### AMR Prediction via SVM-XGBoost Ensemble with Resistome Burden Index
**Venue:** ECCT 2026 (Engineering, Computing & Communication Technologies)
**Status:** Accepted — camera-ready submitted
**Collaboration:** icddr,b (International Centre for Diarrhoeal Disease Research, Bangladesh)
**Repository:** https://github.com/safaet/AMR-Prediction

*Complete author list not yet confirmed for this CV — see Before Submission checklist.*

---

## Selected Research and Technical Projects

### ResistomeX — AMR Prediction Web Application
**Status:** Completed and deployed
**Repository / Demo:** https://github.com/safaet/ResistomeX | resistomex.streamlit.app

- Deployed a separate R-Blend ensemble (Decision Tree, Logistic Regression, and XGBoost combined via soft voting, incorporating the RBI feature) as a publicly accessible prediction tool, distinct from the SVM-XGBoost ensemble used in the ECCT 2026 paper
- Refactored an exploratory research notebook into four self-contained, reproducible pipeline stages: EDA, preprocessing, training, and evaluation
- Reports an average F1 of 0.9421 across 12 antibiotic-pathogen datasets, per the underlying research pipeline (this figure applies to the R-Blend ensemble in this application, not the ECCT 2026 paper's ensemble)

### Multimodal Disaster Severity Classification
**Status:** In progress (Kaggle competition, datathon-iiuc-cse-fest-2026)

- Implementing a late-fusion multimodal architecture (EfficientNet-B3 for vision, XLM-RoBERTa for text) to classify disaster images and text by severity
- Evaluating with F1-macro, accuracy, and AUC-ROC under 5-fold cross-validation
- Addressing bilingual (Bengali/English) text and class imbalance in the dataset

---

## Relevant Professional Experience

### Technical Lead, AI/ML — Neuralis AI
Part-time | August 2026 – Present

- Designed a two-stage retrieval pipeline (bi-encoder retrieval with bge-m3, cross-encoder reranking with bge-reranker-v2-m3) with a data-calibrated refusal mechanism that withholds generation when supporting evidence is insufficient
- Built the evaluation methodology for the system: RAGAS-based faithfulness/relevancy scoring and retrieval/chunking A/B evaluation
- Collaborated with a four-person team (frontend, data collection, deployment) on corpus construction and technical documentation for a multilingual (Bengali/romanized-Bengali/English) dataset

### AI Engineer — Neuralis AI
Part-time | Prior to August 2026 (exact start date not documented)

- Implemented and evaluated a retrieval pipeline combining bge-m3 multilingual bi-encoder embeddings with paragraph/sentence-aware chunking and bge-reranker-v2-m3 cross-encoder reranking
- Built an incremental data-ingestion pipeline with per-record embedding-state tracking to support safe re-indexing of a growing multilingual corpus
- Built offline evaluation tooling for retrieval-threshold calibration and embedding regression testing, supporting reproducible pipeline changes

### Junior AI/ML Engineer — Code Owls
Full-time | July 2024 – May 2025

- Developed Generative AI workflows using LangChain and LangSmith, applying structured A/B evaluation to assess model output quality
- Built AI automation solutions in Python and FastAPI, supporting data preprocessing and model integration across the development lifecycle

---

## Technical and Research Skills

**Programming and Data Analysis:** Python, SQL, Pandas, NumPy

**Machine Learning and Deep Learning:** Scikit-learn, XGBoost, PyTorch, HuggingFace Transformers, model ensembling, feature engineering

**NLP, LLMs, and Retrieval:** BanglaBERT, XLM-RoBERTa, LangChain, FAISS, retrieval-augmented generation pipeline design, cross-encoder reranking

**Computer Vision and Multimodal Learning:** EfficientNet-B3, late-fusion multimodal architectures

**Experimental Design and Statistical Evaluation:** Cross-validation, McNemar's test, bootstrap confidence intervals, Wilcoxon signed-rank test, retrieval/generation A/B evaluation

**Research Software and Reproducibility:** Git/GitHub, Docker, FastAPI, Streamlit, PostgreSQL

---

## Selected Honors and Awards

- 4th Place — IIUC Intra-University Programming Contest, Autumn 2022
- Kaggle: Titanic – Machine Learning from Disaster — leaderboard placement of Rank 1003 (exact date not documented)
