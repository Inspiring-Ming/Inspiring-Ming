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

### 📊 ESG Landscape Explorer
**The question:** with 6.6M messy ESG data points, what actually separates one company from another?
**What I built:** a pipeline that cleans the data into a company × metric matrix, then PCA and
clustering to find the structure, served as a dashboard anyone can query in SQL.
**What I found:** the strongest signal isn't performance, it's *how much a company discloses* —
84% of environmental figures are estimates, not reported numbers.

[🚀 Try the dashboard](https://huggingface.co/spaces/Inspiring-Ming/esg-landscape-explorer) · [Code](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)
<br>`Python` `scikit-learn` `SQL` `Streamlit`

---

### 🤖 Grounded RAG + Agent
**The question:** everyone wants an AI agent — but is one actually better than a simple pipeline?
**What I built:** both, over the same data, so the comparison is real. The agent picks its own
retrieval steps; the pipeline follows a fixed path. Every agent call is traced and turn-capped.
**What I found:** the simple pipeline wins most of the time. The agent only earns its place when
you can't predict what the question will need.

[Read the agent loop](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG/blob/main/app/agent.py) · [18 tests](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG/blob/main/tests/test_agent.py) · [Code](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)
<br>`Python` `Anthropic API` `Flask` `Docker` `pytest`

---

### 🕸️ OntoMetric — ESG Knowledge Graph
**The question:** how do you make an LLM's output defensible enough to put in a report?
**What I built:** a knowledge graph that defines every metric — what it means, how it's calculated,
where it came from — so the model fills in a structure instead of inventing one.
**What I found:** accuracy went from under 10% to 65–90%, and every figure traces back to its source.

[🌐 Project page](https://inspiring-ming.github.io/OntoMetric/) · [Code](https://github.com/Inspiring-Ming/ESG-Metric-KG-System) · Published at **IEEE ICWS 2026**
<br>`Knowledge Graph` `Ontology` `RAG` `Provenance`

---

### 🏦 Materiality Misalignment Risk
**The question:** do the big four Australian banks report what actually matters?
**What I built:** an LLM-assisted scoring method, run over 20 sustainability reports from
**ANZ, CBA, NAB and Westpac** and checked against the SASB banking standard.
**What I found:** a measurable gap — and two models disagreed sharply (0.172 vs 0.464), which is
why I ran stability tests and human checks rather than trusting one score.

[🌐 Live results](https://inspiring-ming.github.io/Quantifying-Materiality-Misalignment-Risk-/) · [Code](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)
<br>`LLM evaluation` `Banking disclosure` `Reproducibility`

---

### 🎬 IMDb Sentiment
**The question:** can a small, well-engineered model beat a big, badly-run one?
**What I built:** Word2Vec plus a neural network over 50K reviews, with a config-driven pipeline,
tests and a container — so it runs the same way every time.
**What I found:** 0.84 F1, and a setup I can retrain in one command.

[Code](https://github.com/Inspiring-Ming/imdb-sentiment-dl)
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
