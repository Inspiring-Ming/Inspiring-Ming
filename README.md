<h1 align="center">Jasmin (Mingqin) Yu</h1>

<p align="center">
  <b>AI &amp; Data Scientist</b> — LLM systems, agents and knowledge graphs, mostly for financial services<br>
  <sub>PhD Computer Science (UNSW) · Master of Finance · Sydney</sub>
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

### 📊 ESG Landscape Explorer

6.6M raw observations cleaned into a company × metric matrix, then PCA and clustering to see what
separates one company from another. Turned out to be disclosure, not performance — 84% of
environmental figures are estimates rather than reported numbers.

**[🚀 Live dashboard](https://huggingface.co/spaces/Inspiring-Ming/esg-landscape-explorer)** · [Code](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)
<br>`Python` `scikit-learn` `SQL` `Streamlit`

</td>
<td width="50%" valign="top">

### 🤖 Grounded RAG + Agent

I kept reading that agents beat fixed pipelines, so I built both over the same data to check. For
most questions the pipeline was better: cheaper, easier to test, same answer. The agent only paid
off when the question needed chaining. Every call is traced and the loop turn-capped, because an
agent you can't audit isn't much use in a bank.

**[🌐 Project page](https://inspiring-ming.github.io/Reporting-Agent-for-ESG/)** · [Code](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)
<br>`Python` `Anthropic API` `Docker` `18 tests`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🕸️ OntoMetric — Knowledge Graph

Asking an LLM to pull numbers out of sustainability reports gave answers that looked right and
often weren't. So I built a knowledge graph defining each metric — meaning, calculation, source —
and had the model fill that structure instead. Accuracy went from under 10% to 65–90%, with every
figure traceable back to source.

**[🌐 Project page](https://inspiring-ming.github.io/OntoMetric/)** · [Code](https://github.com/Inspiring-Ming/ESG-Metric-KG-System) · *IEEE ICWS 2026*
<br>`Knowledge Graph` `Ontology` `RAG` `Provenance`

</td>
<td width="50%" valign="top">

### 🏦 Materiality Misalignment Risk

Do the big four Australian banks report what the SASB standard says matters? I scored 20 reports
from **ANZ, CBA, NAB and Westpac**. There's a measurable gap — but two models disagreed a lot on
its size (0.172 vs 0.464), which is why this ended up with stability runs and 30 human-checked
pairs instead of one headline number.

**[🌐 Live results](https://inspiring-ming.github.io/Quantifying-Materiality-Misalignment-Risk-/)** · [Code](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)
<br>`LLM evaluation` `Banking disclosure` `Reproducibility`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎬 IMDb Sentiment

The standard Keras tutorial flattens an embedding layer, throwing away word order. I ran three
models on identical splits to see if fixing that mattered. Average-pooling won at 0.838 accuracy
and 0.840 F1, beating both the tutorial and an LSTM — the cheap structural fix, not the expensive
sequence model.

**[🌐 Project page](https://inspiring-ming.github.io/imdb-sentiment-dl/)** · [Code](https://github.com/Inspiring-Ming/imdb-sentiment-dl)
<br>`TensorFlow/Keras` `NLP` `Docker`

</td>
<td width="50%" valign="top">

### 🛠 Toolkit

`Python` `SQL` `pandas` `scikit-learn` `TensorFlow`

`Anthropic` `OpenAI` `RAG` `Agents` `MCP` `Knowledge Graphs`

`FastAPI` `Flask` `Docker` `CI/CD` `pytest` `AWS`

Four years on an industry PhD with Cognitivo, including a Westpac project on ESG risk scoring.
Two years in corporate banking before that.

**Published:** IEEE ICWS 2026 · HICSS-59 · *Electronics*

</td>
</tr>
</table>

<p align="center">
  <b>Looking for data science and AI engineering roles in Sydney.</b>
</p>
