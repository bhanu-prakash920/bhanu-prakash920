<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Bhanu%20Prakash%20Kusha&fontSize=50&fontColor=ffffff&fontAlignY=36&desc=Backend%20and%20AI%20Engineer%20%E2%80%A2%20Open%20Source%20%E2%80%A2%20IEEE%20Author&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Bhanu Prakash Kusha"/>
</p>

<p align="center">
  <a href="https://github.com/bhanu-prakash920">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1100&color=4FC3F7&center=true&vCenter=true&width=640&lines=I+build+backends+that+don't+lose+data.;Agentic+RAG+with+LangGraph+%2B+hybrid+retrieval.;100K+events%2Fs+streaming+pipelines.;Contributor+%40+FOSSASIA+%26+OWASP.;IEEE-published+in+spatio-temporal+GNNs." alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bhanu-prakash-kusha-05b677336/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:kushabhanuprakash07@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://bhanu-prakash920.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://leetcode.com/bunnykusha"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <img src="https://komarev.com/ghpvc/?username=bhanu-prakash920&style=for-the-badge&color=2c5364&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<!-- ═══════════════════════════ AT A GLANCE ═══════════════════════════ -->
<table align="center">
  <tr>
    <td align="center" width="170"><h2>9</h2><sub>merged PRs at<br/><b>FOSSASIA &amp; OWASP</b></sub></td>
    <td align="center" width="170"><h2>2</h2><sub>IEEE conference<br/><b>paper acceptances</b></sub></td>
    <td align="center" width="170"><h2>100K/s</h2><sub>events through<br/><b>Rosetta, zero lost</b></sub></td>
    <td align="center" width="170"><h2>9.2</h2><sub>CGPA, B.Tech CSE<br/><b>SRM IST '27</b></sub></td>
  </tr>
</table>

## About me

```python
class BhanuPrakash:
    role       = "Backend & AI Engineer"
    education  = "B.Tech CSE @ SRM Institute of Science and Technology (2023–2027) · CGPA 9.2"
    building   = ["Django / DRF / FastAPI backends", "Agentic RAG systems", "Streaming data platforms"]
    open_source = {"FOSSASIA/eventyay": "contributor since 2026", "OWASP/Nest": "contributor"}
    research   = "STGNN transit demand forecasting · IEEE ICETCI 2026 & IEEE AITest 2026 (Fukuoka)"
    certified  = "MongoDB Certified Associate Developer"
    ranked     = "AIR 97, SRMJEEE 2023 (merit scholarship)"

    def looking_for(self):
        return "Backend / AI Engineering internships and new-grad roles. Let's talk!"
```

<!-- ═══════════════════════════ PROJECTS ═══════════════════════════ -->
## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [Rosetta](https://github.com/bhanu-prakash920/rosetta)
**Multi-OEM vehicle data platform.** Every car maker sends data in its own format; Rosetta turns all of it into one canonical event. When a new maker appears, an agent works out the mapping for it.

- **100,572 events/s** sustained, p99 ingest-to-dashboard **379 ms**
- **0 of 10.1M events lost**, including when processes are SIGKILLed under load
- Agent field-mapper: **99.1%** correct vs **35.8%** for name matching
- **2,768 tests**, 93.5% coverage, Pact contracts, BDD, 11 green CI jobs
- 20-service stack: Kafka, TimescaleDB, pgvector, Redis, MQTT, Grafana, plus Helm and Terraform

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

</td>
<td width="50%" valign="top">

### [DocSage](https://github.com/bhanu-prakash920/DocSage)
**Multimodal agentic document intelligence.** Ask questions across PDFs, DOCX, slide decks and images. Every answer cites the exact page, table or figure it came from.

- LangGraph agent loop: **rewrite → retrieve → grade → answer**
- Hybrid **BM25 + dense** retrieval, **RRF fusion**, cross-encoder re-ranking
- Tables and charts are cropped and captioned by a vision model, so they're searchable too
- Unified schema with modality, page and **bbox** for per-source citations
- Evaluated with **RAGAS**; provider-agnostic, works with Chroma or Qdrant

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Docling](https://img.shields.io/badge/Docling-0F62FE?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-FF6F00?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Transit Demand Forecasting](https://github.com/bhanu-prakash920/transit_forecast) · *IEEE*
**Spatio-temporal GNN plus XGBoost ensemble** that forecasts bus ridership per stop, per hour, then re-plans bus frequency to match.

- **18.80% WMAPE · 5.89 MAE**, up to **36% better** than ARIMA, LSTM and GNN baselines
- Graph attention over a weighted stop-adjacency graph to model how demand spreads between stops
- Load-aware planner: **97% fewer overcrowded hours**, **35% less waiting**
- ETL over **840K+** smart-card taps into **384K+** hourly features

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

</td>
<td width="50%" valign="top">

### [Star Schema for Chatbots](https://github.com/bhanu-prakash920/StarSchemaForChatbots)
**How should data be modelled behind an analytics chatbot?** A benchmark of Star vs Snowflake vs Vector-RAG on 50,000 retail rows, scored against independently computed ground truth.

- Star & Snowflake: **20 / 20** exact answers. Vector RAG: **0 / 20**
- Companion warehouse that measures how well the chatbot itself performs

#### More I've built
- [**Chroma-Struct**](https://github.com/bhanu-prakash920/Chroma-Struct): hierarchy-preserving ingestion into ChromaDB for better RAG
- [**Hallucination Detector**](https://github.com/bhanu-prakash920/hallucination_detector): scores LLM answers using entity, intent and triple-level checks

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white)

</td>
</tr>
</table>

<!-- ═══════════════════════════ OPEN SOURCE ═══════════════════════════ -->
## Open source

<img src="https://github.com/fossasia.png?size=60" width="22" align="top"/> **[FOSSASIA / Eventyay](https://github.com/fossasia/eventyay)**: an open-source event management, ticketing and talks platform (Django)

| PR | What I shipped |
|---|---|
| [#4846](https://github.com/fossasia/eventyay/pull/4846) | Platform-wide footer links & static **Pages** system (TipTap editor, live preview, i18n) |
| [#4924](https://github.com/fossasia/eventyay/pull/4924) · [#4929](https://github.com/fossasia/eventyay/pull/4929) | Fixed an **HTTP 500** when deleting a 2FA device; redesigned the 2FA UX with a toggle and confirmation dialog |
| [#4729](https://github.com/fossasia/eventyay/pull/4729) | Moved the audit log into a dedicated **Change History** tab, with 200+ lines of tests |
| [#6209](https://github.com/fossasia/eventyay/pull/6209) | Fixed voucher logic so only real add-ons become free under `all_addons_included` |
| [#5169](https://github.com/fossasia/eventyay/pull/5169) · [#5197](https://github.com/fossasia/eventyay/pull/5197) | Simpler organizer sidebar navigation; reviewer & team emails shown in the sent-emails list |

<img src="https://github.com/OWASP.png?size=60" width="22" align="top"/> **[OWASP / Nest](https://github.com/OWASP/Nest)**: [#5208](https://github.com/OWASP/Nest/pull/5208) added `/.well-known/security.txt` per **RFC 9116**<br/>
<img src="https://github.com/fossasia.png?size=60" width="22" align="top"/> **[FOSSASIA / scrum_helper](https://github.com/fossasia/scrum_helper)**: [#798](https://github.com/fossasia/scrum_helper/pull/798) i18n for the Chrome extension's Generate button

<!-- ═══════════════════════════ PUBLICATIONS ═══════════════════════════ -->
## Publications

> **STGNN-Based Transit Demand Forecasting and Optimization**: co-author<br/>
> Accepted for **oral presentation** and **IEEE Xplore** publication at **ICETCI 2026**<br/>
> Accepted at **IEEE AITest 2026**, Fukuoka, Japan

<!-- ═══════════════════════════ TECH STACK ═══════════════════════════ -->
## Tech stack

<p align="center"><b>Languages & Backend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=py,cpp,ts,django,fastapi&perline=10" alt="Languages and backend"/>
</p>
<p align="center"><b>AI / ML</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn&perline=10" alt="ML"/>
  <br/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/XGBoost-006ACC?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge"/>
</p>
<p align="center"><b>Data & Infrastructure</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,mysql,kafka,docker,kubernetes,terraform,aws,grafana,prometheus,git,linux&perline=13" alt="Data and infra"/>
</p>

<!-- ═══════════════════════════ STATS ═══════════════════════════ -->
## GitHub & LeetCode

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com?user=bhanu-prakash920&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub streak"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhanu-prakash920&layout=compact&theme=tokyonight&hide_border=true&border_radius=10&langs_count=6" alt="Top languages"/>
</p>
<p align="center">
  <a href="https://leetcode.com/bunnykusha">
    <img src="https://leetcard.jacoblin.cool/bunnykusha?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats"/>
  </a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bhanu-prakash920/bhanu-prakash920/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/bhanu-prakash920/bhanu-prakash920/output/github-contribution-grid-snake.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/bhanu-prakash920/bhanu-prakash920/output/github-contribution-grid-snake.svg"/>
  </picture>
</p>

<p align="center">
  <i>Open to <b>Backend</b> and <b>AI Engineering</b> internships and new-grad roles. If you're building something ambitious, <a href="mailto:kushabhanuprakash07@gmail.com">let's talk</a>.</i>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%"/>
