<h1 align="center">Jasmin (Mingqin) Yu</h1>

<p align="center">
  <b>I build AI systems for places where a confident wrong answer is worse than no answer.</b>
</p>

<p align="center">
  <code>LLM &amp; Agent Systems</code> · <code>Evaluation</code> · <code>Data Science</code> · <code>Financial Services</code>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mingqin-yu/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=1nRQ9twAAAAJ&hl=en"><img src="https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"></a>
  <a href="https://inspiring-ming.github.io/Ming-sGalaxyWorld/"><img src="https://img.shields.io/badge/Portfolio-1a1a1a?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="mailto:mingchin.yuyu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/📍_Sydney-informational?style=flat-square">
  <img src="https://img.shields.io/badge/Open_to-Data_Science_%2F_AI_Engineering-2ea44f?style=flat-square">
</p>

---

## Where I've worked

```
2022 – 2026   Industry PhD Researcher · Data Scientist          UNSW × Cognitivo × FAIC
              Led Project P002 with Westpac: ESG risk scoring and ranking for
              investment decisions. Requirements → prototype → deployment.
              Led a team of 4 across concurrent workstreams.

2023 – now    Teaching & Research Associate  (part time)        UNSW · USYD
              ML, NLP, recommender systems, algorithms. Capstone supervision.

2020 – 2022   Relationship Manager · Corporate & Retail Banking Guangfa Bank
              Lending applications, credit risk, customer segmentation, KYC.
```

**PhD** Computer Science, UNSW (2026) · **MFin** UIBE × Adelaide (GPA 3.7) · **CFA Institute** ESG Investing; Climate Risk

---

## Three problems I solved

<table>
<tr><td width="33%" valign="top">

### 🎯 Accuracy was under 10%

Unconstrained LLM extraction on regulatory filings returned values that *looked*
right but weren't — harder to catch than obvious failure.

**What I did:** split the failure modes. Schema checks for malformed output,
semantic checks for values that parse but make no sense in context. Ran both.

**Result:** `65–90%`, reported *by document type* — the average was hiding
where it still broke.

</td><td width="33%" valign="top">

### 💸 Too expensive to run

The pipeline cost more per run than the partner could justify at the frequency
they needed it.

**What I did:** noticed the largest input block was identical every call.
Restructured the prompt so stable content sat ahead of the cache boundary.

**Result:** `48× cheaper` per repeat call — changed what was commercially
viable, not just technically possible.

</td><td width="33%" valign="top">

### 🤔 Agent, or just RAG?

Everyone wants an agent. Agents cost more, fail in more ways, and are harder
to test.

**What I did:** built *both* over the same data store so the comparison was
honest, not theoretical.

**Result:** fixed pipeline stays the default; the agent earns its place only
where question shape varies.

</td></tr>
</table>

---

## Code you can read

<table>
<tr><td width="50%" valign="top">

**🤖 [Grounded RAG + Agent](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)**

Reasoning loop · 5 tool interfaces · bounded turns · every call traced ·
errors returned to the model for recovery

`Python` `Anthropic API` `SQLite` `Docker` `18 tests`

</td><td width="50%" valign="top">

**🏦 [Materiality Misalignment Risk](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)**

**ANZ · CBA · NAB · Westpac** — 20 reports scored against SASB FN-CB.
2 models, ablations, 30 human-annotated validation pairs

`LLM evaluation` `Reproducibility` `SHA-256 corpus`

</td></tr>
<tr><td width="50%" valign="top">

**📊 [ESG Landscape Explorer](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)**

6.6M observations → company × metric matrix → PCA, KMeans, disclosure-gap
analysis. Streamlit app with live SQL console

`scikit-learn` `SQL` `Streamlit`

</td><td width="50%" valign="top">

**🎬 [IMDb Sentiment](https://github.com/Inspiring-Ming/imdb-sentiment-dl)**

Word2Vec + neural net, **0.84 F1** on 50K reviews. Config-driven, tested,
containerised

`TensorFlow/Keras` `NLP` `Docker`

</td></tr>
</table>

---

## Toolkit

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch%20%2F%20Keras-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white">
</p>

```text
LLM systems   RAG · tool-calling agents · prompt & context engineering · guardrails · MCP
Evaluation    validation frameworks · ablations · human benchmarking · failure analysis
Data & ML     pandas · PCA/clustering · NLP · pipelines at 400K+ records
Domain        financial services · credit & risk · sustainability disclosure
```

---

## Published

| | |
|---|---|
| **IEEE ICWS 2026** | An Ontology-driven Service-oriented System for ESG Metric Computation and Reporting |
| **HICSS-59** | Reducing Analytical Opacity in Decision Support: An AI-enabled Framework for Traceable and Explainable Reporting |
| ***Electronics*** 13(9) | An Ontology-driven Architecture for ESG Decision Support and Reporting |

<p align="center">
  <sub>Grants: AEA Ignite (Australia's Economic Accelerator) · SDG Faculty Research Showcase, UNSW Business School</sub>
</p>

<p align="center">
  <b>Looking for data science and AI engineering roles in Sydney.</b><br>
  <sub>The fastest way to reach me is <a href="https://www.linkedin.com/in/mingqin-yu/">LinkedIn</a>.</sub>
</p>
