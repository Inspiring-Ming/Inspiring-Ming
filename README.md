## Jasmin (Mingqin) Yu

**AI systems that have to be checkable.** PhD in Computer Science (UNSW, 2026),
completed as an industry PhD with [Cognitivo](https://cognitivo.com.au/). Master of
Finance, and two years in corporate banking before that.

I build LLM and machine-learning systems for settings where a confident wrong answer
is worse than no answer: the work is usually less about the model and more about
retrieval, validation, provenance and evaluation around it.

📍 Sydney · [LinkedIn](https://www.linkedin.com/in/mingqin-yu/) ·
[Google Scholar](https://scholar.google.com/citations?user=1nRQ9twAAAAJ&hl=en) ·
[Portfolio](https://inspiring-ming.github.io/Ming-sGalaxyWorld/)

---

### Start here

**[Reporting-Agent-for-ESG](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)** — grounded RAG **and** a tool-calling agent over the same data store, so the two can be compared.
The agent implements the reasoning loop, five tool interfaces and orchestration; the model
sequences its own retrieval. Bounded turn cap, every call traced, tool errors returned to the
model for recovery, enforced markers separating retrieved data from model output. 18 tests,
runnable without an API key.
> *The agent is not the default — it costs more and is harder to test, so it has to earn its place against the fixed pipeline.*
`Python` `Anthropic API` `SQLite` `Docker` `pytest`

**[Quantifying Materiality Misalignment Risk](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)** — LLM-assisted scoring of 20 sustainability reports from **ANZ, CBA, NAB and Westpac**
(2021–2025) against the SASB FN-CB standard. Two models compared, weight and prompt ablations,
3-run stability testing, and 30 human-annotated pairs for validation. Source PDFs are not
redistributed; SHA-256 checksums make the corpus reproducible anyway.
> *Evaluation designed to show where the measure is unreliable, not only where it works.*
`Python` `LLM evaluation` `Reproducibility`

**[ESG Landscape Explorer](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)** — 6.6M raw observations reduced to a clean company × metric matrix, then PCA, KMeans
clustering, industry profiling and a disclosure-gap analysis, served as a Streamlit dashboard
with an in-app SQL console.
> *PC1 (17.5% of variance) turned out to track disclosure maturity rather than performance — 84% of environmental observations are estimated, not reported.*
`Python` `scikit-learn` `SQL` `Streamlit`

**[IMDb Sentiment (deep learning)](https://github.com/Inspiring-Ming/imdb-sentiment-dl)** — Word2Vec + neural network, 0.84 F1 on 50K reviews. Config-driven pipeline, tests,
containerised.
`Python` `TensorFlow/Keras` `Docker`

---

### What I work on

| | |
|---|---|
| **LLM systems** | RAG, tool-calling agents, prompt and context engineering, guardrails, MCP |
| **Evaluation** | Validation frameworks, ablations, human benchmarking, failure analysis |
| **Data & ML** | Python, SQL, pandas, scikit-learn, PCA/clustering, NLP, pipelines at 400K+ records |
| **Engineering** | FastAPI, Flask, Docker, CI/CD, pytest, AWS |
| **Domain** | Financial services, credit and risk, sustainability disclosure and reporting |

### Published

- **An Ontology-driven Service-oriented System for ESG Metric Computation and Reporting** — IEEE ICWS 2026
- **Reducing Analytical Opacity in Decision Support: An AI-enabled Framework for Traceable and Explainable Reporting** — HICSS-59
- **An Ontology-driven Architecture for ESG Decision Support and Reporting** — *Electronics* 13(9), 2024

---

*Currently looking for data science and AI engineering roles in Sydney.*
