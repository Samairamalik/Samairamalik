<div align="center">

<img src="https://capsule-render.vercel.app/api?type=transparent&height=150&text=Samaira%20Malik&fontColor=7C5CFF&fontSize=56&fontAlignY=40&desc=ML%20%C2%B7%20Data%20%C2%B7%20Product%20%E2%80%94%20Bengaluru&descAlignY=66&descSize=15" alt="Samaira Malik" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1400&color=7C5CFF&center=true&vCenter=true&width=700&lines=ML%2C+data%2C+and+the+question+of+what's+worth+building.;signal+%E2%86%92+system+%E2%86%92+something+someone+actually+uses.;most+of+the+work+happens+upstream+of+the+model." alt="tagline" />

<br/>

<a href="https://www.linkedin.com/in/samaira-malik-a06266264/"><img src="https://img.shields.io/badge/LinkedIn-7C5CFF?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn" /></a>
<a href="mailto:samaira6005@gmail.com"><img src="https://img.shields.io/badge/Email-7C5CFF?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>
<a href="YOUR-RESUME-LINK"><img src="https://img.shields.io/badge/Résumé-F5A524?style=flat-square&logo=readdotcv&logoColor=white&labelColor=0D1117" alt="Resume" /></a>
<img src="https://img.shields.io/badge/Open%20to-AI%20%2F%20Data%20%2F%20APM%20Internships%20'27-1F2937?style=flat-square&labelColor=0D1117" alt="Status" />

</div>

---

### `~/whoami`

I work across **ML, data, and product** — building the pipeline, and caring about what it outputs and who it's for. Most of my work starts as an unlovely spreadsheet, or someone saying "we just need a number," and the interesting part is usually figuring out which number they actually meant.

```yaml
samaira:
  builds:    ML and data systems, end to end
  thinks_about: what they're for, not only how they work
  studying:  B.Tech, Computer Science & AI — Manipal Institute of Technology, Bengaluru
  primary:   Python   # C++ when it has to be fast

works_across:
  data:      ingestion, validation, feature pipelines, forecasting
  ml:        LLM chains with verification, time series, evaluation
  product:   scoping, tradeoffs, stakeholder translation, shipping

the_overlap: >
  The interesting questions live between the three — what's worth
  building, what the data can genuinely support, and what someone
  will still trust in month six.
```

---

### `~/tradeoffs`

Some of the choices behind the work above — mostly the ones where the engineering answer and the useful answer weren't the same.

> **Weaker data source, but one that actually runs.**
> The most useful source for trend detection didn't have a clean API path. I built the first version on the sources I could reliably run in production, wrote up what we'd be missing, and took that to my manager rather than deciding it quietly. The signal is thinner than it could be — but it's documented, and it ships.

> **Every forecast carries a reason.**
> My manager wanted a readable explanation attached to each prediction, not just a number, because the output has to survive being questioned in a meeting. That constrained the modelling more than I expected, and I'm still working out what it costs in accuracy.

> **One engine, one config per category.**
> I set it up so adding a category means writing a config file rather than a new script. The first one took longer than it would have otherwise; everything after has been much faster. Whether that was the right call depends on how many categories get added — so far, it's held up.

---

### `~/work`

| Project | What it does | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[VizLens](https://github.com/Samairamalik/VIZ-LENS)** | Google Lens for *abstract* concepts. I own the AI layer — a three-stage chain generating self-contained HTML5 visualisations, structured quizzes, and a code judge that returns the failing line plus a visual reference. Scoped the three surfaces as the product, not just the model. | `Gemini` `TypeScript` `Structured output` | National hackathon finalist |
| **Retail Reporting Automation** | Config-driven pipeline replacing a manual monthly FMCG reporting cycle: ingestion → computation → validation → narrative → deck. LLM writes the prose; deterministic code owns every number. | `Python` `YAML` `LLM narrative` `pytest` | Internal · shipped |
| **Ingredient Trend Forecasting** | Detects emerging food trends from social signal and forecasts next month's movers — with a defensible reason attached to every prediction. Owned solo, from data sourcing to spec. | `Python` `Reddit/YouTube APIs` `Time series` | Internal · in build |
| **[NeuroSense](https://github.com/Samairamalik/NeuroSense)** | Multimodal screening for **early Parkinson's detection**. Independent models on voice, handwriting/spiral drawings, and MRI — each returning its own prediction and confidence, so modalities can be *compared* rather than blended into one opaque score. Scoped deliberately as clinical decision support, not a diagnostic replacement. | `CNN` `XGBoost` `SVM` `HOG` | Team of 6 · complete |
| **Shadow Auditor** | Research pilot measuring how dialect and register shift model behaviour. Targeting a workshop submission. | `Evaluation` `NLP` | In progress |

---

### `~/toolkit`

<table>
<tr>
<td><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Python-7C5CFF?style=flat-square&logo=python&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/C++-7C5CFF?style=flat-square&logo=cplusplus&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/SQL-7C5CFF?style=flat-square&logo=postgresql&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/TypeScript-7C5CFF?style=flat-square&logo=typescript&logoColor=white&labelColor=0D1117" />
</td>
</tr>
<tr>
<td><b>ML &amp; Data</b></td>
<td>
<img src="https://img.shields.io/badge/pandas-38BDF8?style=flat-square&logo=pandas&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/NumPy-38BDF8?style=flat-square&logo=numpy&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/scikit--learn-38BDF8?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/LightGBM-38BDF8?style=flat-square&logo=leaflet&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/PyTorch-38BDF8?style=flat-square&logo=pytorch&logoColor=white&labelColor=0D1117" />
</td>
</tr>
<tr>
<td><b>Applied AI</b></td>
<td>
<img src="https://img.shields.io/badge/Gemini-F5A524?style=flat-square&logo=googlegemini&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OpenAI-F5A524?style=flat-square&logo=openai&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/LangChain-F5A524?style=flat-square&logo=langchain&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Hugging%20Face-F5A524?style=flat-square&logo=huggingface&logoColor=white&labelColor=0D1117" />
</td>
</tr>
<tr>
<td><b>Platform</b></td>
<td>
<img src="https://img.shields.io/badge/FastAPI-34D399?style=flat-square&logo=fastapi&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Docker-34D399?style=flat-square&logo=docker&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/PostgreSQL-34D399?style=flat-square&logo=postgresql&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/GitHub%20Actions-34D399?style=flat-square&logo=githubactions&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/GCP-34D399?style=flat-square&logo=googlecloud&logoColor=white&labelColor=0D1117" />
</td>
</tr>
</table>

---

### `~/stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Samairamalik&show_icons=true&hide_border=true&bg_color=0D1117&title_color=7C5CFF&text_color=C9D1D9&icon_color=F5A524&include_all_commits=true&rank_icon=github" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Samairamalik&layout=compact&hide_border=true&bg_color=0D1117&title_color=7C5CFF&text_color=C9D1D9&langs_count=6" alt="top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Samairamalik&bg_color=0D1117&color=C9D1D9&line=7C5CFF&point=F5A524&area=true&area_color=7C5CFF&hide_border=true" alt="activity graph" width="98%" />

</div>

---

<details>
<summary><b><code>~/off-the-keyboard</code></b> — the part that isn't in a terminal</summary>

<br/>

**Sports Secretary** and **basketball captain** on campus — mostly an exercise in shipping under a deadline with people who have their own opinions. Running a season and running a project have more overlap than either side admits: you're allocating limited resources, managing morale, and deciding what to cut in week nine.

**VP of NEURA**, the campus AI club, where I spend a lot of time convincing people that the boring part — the data — is the interesting part.

Currently curious about basketball analytics as a computer vision problem. Ask me and I will not stop talking.

</details>

<br/>

<div align="center">

<sub><i>Open to Summer 2027 internships across applied ML, data platform, and product.</i></sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=transparent&height=60&section=footer" alt="" />

</div>
