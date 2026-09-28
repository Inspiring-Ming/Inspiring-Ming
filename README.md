<h1 align="center">Jasmin (Mingqin) Yu</h1>

<p align="center">
  <sub>Software Engineering · LLM &amp; Agents · Knowledge Graphs · Financial Services · Sydney</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mingqin-yu/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=1nRQ9twAAAAJ&hl=en"><img src="https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"></a>
  <a href="https://inspiring-ming.github.io/Ming-sGalaxyWorld/"><img src="https://img.shields.io/badge/Portfolio-1a1a1a?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="mailto:mingchin.yuyu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### 🤖 [Grounded RAG + Agent](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)
A tool-calling [agent](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG/blob/main/app/agent.py)
**and** a fixed RAG pipeline over the same store, so the two can be compared honestly.
→ the model sequences its own retrieval; bounded turns, every call traced, errors returned for recovery.
**Result:** repeat-call cost cut to **1/10** by caching · [18 tests](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG/blob/main/tests/test_agent.py) that run without an API key.
<br>`Python` `Anthropic API` `Flask` `SQLite` `Docker` `pytest`

### 🏦 [Materiality Misalignment Risk](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)
20 sustainability reports from **ANZ · CBA · NAB · Westpac** (2021–2025) scored against
[SASB FN-CB](https://sasb.ifrs.org/standards/download/).
→ two models compared, weight and prompt ablations, 3-run stability, 30 human-annotated pairs.
**Result:** mean MMRI **0.172** (Claude) vs **0.464** (GPT) · corpus reproducible by SHA-256 checksum.
<br>`LLM evaluation` `Banking disclosure` `Reproducibility`

### 🕸️ [OntoMetric — ESG Knowledge Graph](https://github.com/Inspiring-Ming/ESG-Metric-KG-System)
RDF knowledge graph modelling entities, relationships and calculation logic, so every
generated figure traces back to source.
**Result:** published at **IEEE ICWS 2026**; extraction accuracy from under 10% to **65–90%**
with end-to-end provenance · [thesis](https://unsworks.unsw.edu.au/entities/publication/68e19b33-bfbb-4398-96f5-59239f6830b9)
<br>`Knowledge Graph` `Ontology` `RAG` `Provenance` `Python`

### 📊 [ESG Landscape Explorer](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)
**6.6M** raw observations reduced to a clean company × metric matrix, then PCA, KMeans and a
disclosure-gap analysis, served as a Streamlit dashboard with a live SQL console.
**Result:** PC1 (17.5% of variance) tracks *disclosure maturity*, not performance — **84%** of
environmental observations are estimated rather than reported.
<br>`scikit-learn` `SQL` `pandas` `Streamlit`

### 🎬 [IMDb Sentiment](https://github.com/Inspiring-Ming/imdb-sentiment-dl)
Word2Vec + neural network over 50K reviews. Config-driven pipeline, tested, containerised.
**Result:** **0.84 F1.**
<br>`TensorFlow/Keras` `NLP` `Docker`

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
  <img src="https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
</p>

<p align="center">
  <sub>PhD Computer Science (UNSW) · Master of Finance ·
  <a href="https://scholar.google.com/citations?user=1nRQ9twAAAAJ&hl=en">IEEE ICWS 2026 · HICSS-59 · <i>Electronics</i></a> ·
  <b>Open to data science and AI engineering roles</b></sub>
</p>
