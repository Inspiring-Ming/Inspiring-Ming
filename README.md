<h1 align="center">Jasmin (Mingqin) Yu</h1>

<p align="center">
  <b>AI &amp; Data Scientist</b> — LLM systems, agents and knowledge graphs for financial services<br>
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
**Q.** With 6.6M messy data points, what actually separates one company from another?
**Built.** Cleaning pipeline → company × metric matrix → PCA + KMeans, served as a dashboard you can query in SQL.
**Found.** The strongest signal isn't performance, it's *how much a company discloses*. 84% of environmental figures are estimates.

**[🚀 Live dashboard](https://huggingface.co/spaces/Inspiring-Ming/esg-landscape-explorer)** · [Code](https://github.com/Inspiring-Ming/DataAnalysis_SQL-ML)
<br>`Python` `scikit-learn` `SQL` `Streamlit`

</td>
<td width="50%" valign="top">

### 🤖 Grounded RAG + Agent
**Q.** Everyone wants an agent — is one actually better than a simple pipeline?
**Built.** Both, over the same data, so the comparison is real. Agent picks its own steps; every call traced and turn-capped.
**Found.** The simple pipeline wins most of the time. The agent earns its place only when you can't predict the question.

**[🌐 Project page](https://inspiring-ming.github.io/Reporting-Agent-for-ESG/)** · [Code](https://github.com/Inspiring-Ming/Reporting-Agent-for-ESG)
<br>`Python` `Anthropic API` `Docker` `18 tests`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🕸️ OntoMetric — Knowledge Graph
**Q.** How do you make an LLM's output defensible enough to put in a report?
**Built.** A knowledge graph defining every metric — meaning, calculation, source — so the model fills a structure instead of inventing one.
**Found.** Accuracy from under 10% to **65–90%**, every figure traceable to source.

**[🌐 Project page](https://inspiring-ming.github.io/OntoMetric/)** · [Code](https://github.com/Inspiring-Ming/ESG-Metric-KG-System) · *IEEE ICWS 2026*
<br>`Knowledge Graph` `Ontology` `RAG` `Provenance`

</td>
<td width="50%" valign="top">

### 🏦 Materiality Misalignment Risk
**Q.** Do the big four Australian banks report what actually matters?
**Built.** LLM-assisted scoring over 20 reports from **ANZ, CBA, NAB, Westpac**, checked against the SASB banking standard.
**Found.** A measurable gap — and two models disagreed sharply (0.172 vs 0.464), so I added stability runs and human checks.

**[🌐 Live results](https://inspiring-ming.github.io/Quantifying-Materiality-Misalignment-Risk-/)** · [Code](https://github.com/Inspiring-Ming/Quantifying-Materiality-Misalignment-Risk-)
<br>`LLM evaluation` `Banking disclosure` `Reproducibility`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎬 IMDb Sentiment
**Q.** Does a better architecture beat the standard tutorial, or do people just assume it does?
**Built.** Three models, identical splits, one variable changed: Flatten vs average-pooling vs LSTM.
**Found.** Pooling beat both — **0.838 accuracy, 0.840 F1**. The cheap structural fix won, not the expensive sequence model.

**[🌐 Project page](https://inspiring-ming.github.io/imdb-sentiment-dl/)** · [Code](https://github.com/Inspiring-Ming/imdb-sentiment-dl)
<br>`TensorFlow/Keras` `NLP` `Docker`

</td>
<td width="50%" valign="top">

### 🛠 Toolkit

`Python` `SQL` `pandas` `scikit-learn` `TensorFlow`

`Anthropic` `OpenAI` `RAG` `Agents` `MCP` `Knowledge Graphs`

`FastAPI` `Flask` `Docker` `CI/CD` `pytest` `AWS`

**Domain:** financial services · credit &amp; risk · sustainability disclosure

**Published:** IEEE ICWS 2026 · HICSS-59 · *Electronics*

</td>
</tr>
</table>

<p align="center">
  <b>Open to data science and AI engineering roles in Sydney.</b>
</p>
