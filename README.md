<h1 align="center">Jasmin (Mingqin) Yu</h1>

<p align="center">
  <sub>I work on LLM systems, AI agents and knowledge graphs for financial services and ESG. Based in Sydney.</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mingqin-yu/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=1nRQ9twAAAAJ&hl=en"><img src="https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"></a>
  <a href="https://inspiring-ming.github.io/Ming-sGalaxyWorld/"><img src="https://img.shields.io/badge/Portfolio-1a1a1a?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="mailto:mingchin.yuyu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🧭 ESG Portfolio Agent — Pre-Trade Compliance

An agent that answers fund carbon-intensity questions and checks trades against an ESG mandate,
built on top of my existing ESG metric system (IEEE ICWS 2026) instead of replacing it. The model only picks the next step;
every number comes from a service, and a breaching trade waits for a second person to approve. I
wrote probes that try to break those rules (forged tokens, wrong-role approvals) and none got through.

**[🌐 Project page](https://inspiring-ming.github.io/AI-Agent-for-ESG/)** · [Code](https://github.com/Inspiring-Ming/AI-Agent-for-ESG)
<br>`Claude` `MCP` `FastAPI` `Docker Compose`

</td>
<td width="50%" valign="top">

### 🤖 RAG vs. Agent over ESG Data

I kept reading that agents beat fixed pipelines, so I built both over the same data to check. For
most questions the pipeline won: cheaper, easier to test, same answer. The agent only paid off when
a question needed chaining. Every call is traced, because an agent you can't audit isn't much use
in a bank.

**[🌐 Project page](https://inspiring-ming.github.io/Reporting-Agent-for-ESG/)** · [Code](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)
<br>`Python` `Anthropic API` `Docker` `18 tests`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🕸️ OntoMetric — LLM to ESG Knowledge Graph

Asking an LLM to pull numbers out of sustainability reports gave answers that looked right and
often weren't. So I built a knowledge graph defining each metric — meaning, calculation, source —
and had the model fill that instead. Accuracy went from under 10% to 65–90%, every figure traceable.

**[🌐 Project page](https://inspiring-ming.github.io/OntoMetric/)** · [Code](https://github.com/Inspiring-Ming/OntoMetric) · [Paper](https://arxiv.org/abs/2512.01289) · *IEEE ICKG 2026*
<br>`Knowledge Graph` `Ontology` `RAG` `Provenance`

</td>
<td width="50%" valign="top">

### 🏦 Bank Disclosure vs. SASB — Materiality Risk

Do the big four Australian banks report what the SASB standard says matters? I scored 20 reports
from **ANZ, CBA, NAB and Westpac**. There's a gap — but two models disagreed on its size (0.172 vs
0.464), so this ended up with stability runs and 30 human-checked pairs instead of one number.

**[🌐 Live results](https://inspiring-ming.github.io/Quantifying-Materiality-Misalignment-Risk-/)** · [Code](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)
<br>`LLM evaluation` `Banking disclosure` `Reproducibility`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 ESG Landscape Explorer

6.6M raw observations cleaned into a company × metric matrix, then PCA and clustering to see what
separates one company from another. Turned out to be disclosure, not performance: 84% of
environmental figures are estimates.

**[🚀 Live dashboard](https://huggingface.co/spaces/Inspiring-Ming/esg-landscape-explorer)** · [Code](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)
<br>`Python` `scikit-learn` `SQL` `Streamlit`

</td>
<td width="50%" valign="top">

### 🎬 IMDb Sentiment — Architecture Bake-off

The standard Keras tutorial flattens an embedding layer, throwing away word order. I ran three
models on identical splits to see if that mattered. Average-pooling won (0.838 accuracy, 0.840 F1),
beating both the tutorial and an LSTM.

**[🌐 Project page](https://inspiring-ming.github.io/imdb-sentiment-dl/)** · [Code](https://github.com/Inspiring-Ming/imdb-sentiment-dl)
<br>`TensorFlow/Keras` `NLP` `Docker`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🛠 Toolkit

`Python` `SQL` `pandas` `scikit-learn` `TensorFlow`

`Anthropic` `OpenAI` `RAG` `Agents` `MCP` `Knowledge Graphs`

`FastAPI` `Flask` `Docker` `CI/CD` `pytest` `AWS`

Four years on an industry PhD with Cognitivo, including a Westpac project on ESG risk scoring.
Two years in corporate banking before that.

**Published:** [IEEE ICKG 2026](https://arxiv.org/abs/2512.01289) · [IEEE ICWS 2026](https://doi.org/10.1109/ICWS72778.2026.00052) · HICSS-59 · [*Electronics* 2024](https://doi.org/10.3390/electronics13091719)

</td>
</tr>
</table>
