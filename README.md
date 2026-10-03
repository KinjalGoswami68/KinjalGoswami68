<div align="center">
<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/hero.svg" alt="Kinjal - AI/ML engineer" width="100%" />
</div>

<br/>

## > crawl.status

```text
identity   : from future import ML_Engineer
me = ML_Engineer(stack=["torch", "sklearn"])
session    : AI Intern @ DataFlirt · Bangalore
mode       : building practical AI systems, in public
interests  : Machine Learning · LLMs · GenAI · RAG · AI Agents · AI data systems
learning   : ML engineering · production AI · LLM cost and quality
contributes: open source
```

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > currently_crawling

| Target | Status | Why it matters |
|:--|:--|:--|
| ML engineering | `indexing` | Training is the easy part. Evaluation, deployment and monitoring are what make a model useful. |
| RAG + agents | `indexing` | Retrieval quality and tool use decide whether LLM apps are reliable. |
| Self-healing data pipelines | `crawling` | AI systems are only as good as the data they are fed, and that data keeps changing. |
| LLM cost discipline | `crawling` | Measuring tokens and cost per run turns a demo into something you can operate. |

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > the_web

Every node is a skill, and every thread is a place I used it. The projects sit at the edge of the web, where the skills connect.

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#150f2e', 'primaryTextColor': '#e9d5ff', 'primaryBorderColor': '#8b5cf6', 'lineColor': '#6d5bd0', 'secondaryColor': '#0d1117', 'tertiaryColor': '#0d1117', 'clusterBkg': '#0d1117', 'clusterBorder': '#30363d', 'fontFamily': 'monospace'}}}%%
flowchart TD
    ROOT(("KINJAL<br/>root node")):::root

    subgraph CORE["core nodes"]
        ML["Machine Learning"]
        LLM["LLMs"]
        GENAI["GenAI"]
        RAG["RAG"]
        AGENTS["AI Agents"]
    end

    subgraph BUILD["build layer"]
        PY["Python"]
        API["FastAPI"]
        SQL["PostgreSQL"]
        DOCK["Docker + Cloud"]
        GIT["Git / GitHub"]
    end

    subgraph SHIPPED["shipped"]
        SENT["SentinelAI"]:::hero
        DF["DataFlirt<br/>AI intern"]:::hero
        CRA["Contract Risk Analyzer"]:::proj
        OTS["Orbital Terrain Scanner"]:::proj
    end

    ROOT --- ML
    ROOT --- LLM
    ROOT --- PY
    ROOT --- API
    ROOT --- GIT

    ML --- LLM
    LLM --- GENAI
    LLM --- RAG
    LLM --- AGENTS
    GENAI --- RAG
    RAG --- AGENTS

    PY --- API
    API --- SQL
    API --- DOCK
    GIT --- PY

    SENT -.- API
    SENT -.- SQL
    SENT -.- ML
    SENT -.- LLM
    DF -.- PY
    DF -.- API
    DF -.- SQL
    DF -.- DOCK
    DF -.- LLM
    CRA -.- ML
    CRA -.- LLM
    CRA -.- PY
    OTS -.- PY
    OTS -.- ML

    classDef root fill:#3b0a0a,stroke:#dc2626,stroke-width:3px,color:#ffffff;
    classDef hero fill:#2e1065,stroke:#a78bfa,stroke-width:3px,color:#ffffff;
    classDef proj fill:#0f172a,stroke:#3b82f6,stroke-width:2px,color:#dbeafe;
    linkStyle default stroke:#6d5bd0,stroke-width:1px;
```

<div align="center">

<img src="https://img.shields.io/badge/Python-150f2e?style=flat-square&logo=python&logoColor=a78bfa" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-150f2e?style=flat-square&logo=fastapi&logoColor=a78bfa" alt="FastAPI" />
<img src="https://img.shields.io/badge/PostgreSQL-150f2e?style=flat-square&logo=postgresql&logoColor=a78bfa" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-150f2e?style=flat-square&logo=docker&logoColor=a78bfa" alt="Docker" />
<img src="https://img.shields.io/badge/Playwright-150f2e?style=flat-square&logo=playwright&logoColor=a78bfa" alt="Playwright" />
<img src="https://img.shields.io/badge/Supabase-150f2e?style=flat-square&logo=supabase&logoColor=a78bfa" alt="Supabase" />
<img src="https://img.shields.io/badge/Hugging%20Face-150f2e?style=flat-square&logo=huggingface&logoColor=a78bfa" alt="Hugging Face" />
<img src="https://img.shields.io/badge/Streamlit-150f2e?style=flat-square&logo=streamlit&logoColor=a78bfa" alt="Streamlit" />
<img src="https://img.shields.io/badge/Git-150f2e?style=flat-square&logo=git&logoColor=a78bfa" alt="Git" />

</div>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > active_session: DataFlirt

```text
$ crawl --session active

role    : AI Intern
org     : DataFlirt · Bangalore, India
mission : build and run the data systems that feed AI
```

| Workstream | What I build |
|:--|:--|
| Self-healing data agents | Async Python crawlers with a versioned selector registry, drift detection, and automated repair that promotes a fix or rolls it back |
| Data layer for AI | Relational schemas, indexing, deduplication and replayable raw-payload archives |
| Low-latency APIs | FastAPI services with caching, pagination and measured p50/p95 response times |
| Cloud deployment | Containers, scheduled jobs and queues on AWS or GCP |
| LLM cost discipline | Measured tokens and cost per run wherever LLMs are used |

`Python` · `asyncio` · `httpx / aiohttp` · `Playwright` · `FastAPI` · `PostgreSQL` · `pydantic` · `pytest` · `Docker` · `AWS / GCP`

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > featured_node: SentinelAI

<table>
<tr>
<td width="60%" valign="top">

**Production LLM quality-monitoring system.**

SentinelAI watches an LLM application in production and flags quality drift before users notice. Responses are embedded with TF-IDF and scored with **Isolation Forest** and **CUSUM** change detection. Anomalies trigger **Slack webhook** alerts.

`FastAPI` · `Supabase Postgres` · `Render` · `Isolation Forest` · `CUSUM` · `Slack alerts`

[**Repository**](https://github.com/KinjalGoswami68/-SentinelAI) · [**Live demo**](https://sentinelai24455.streamlit.app/)

</td>
<td width="40%" align="center" valign="middle">

<a href="https://github.com/KinjalGoswami68/YOUR_SENTINELAI_REPO">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=KinjalGoswami68&repo=YOUR_SENTINELAI_REPO&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&icon_color=dc2626&border_color=30363d&show_owner=false" alt="SentinelAI repo card" />
</a>

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > other_nodes

<table>
<tr>
<td width="50%" valign="top">

**Contract Risk Analyzer**

DistilBERT fine-tuned on the CUAD dataset to classify contract clauses across 34 risk categories (~75% accuracy). Llama 3.3 70B on Groq explains each flagged clause in plain English. The frontend is Streamlit.

`DistilBERT` · `CUAD` · `Groq` · `Streamlit`

[Repository](https://github.com/KinjalGoswami68/contract-risk-analyzer)

</td>
<td width="50%" valign="top">

**Orbital Terrain Scanner**

[1-2 lines: what it scans, what data or imagery it uses, and what it outputs.]

`[tech]` · `[tech]` · `[tech]`

[Repository](https://github.com/KinjalGoswami68/terrain-web-app)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**More threads**

Smaller experiments, notebooks and builds live in my repositories. [Browse all repositories](https://github.com/KinjalGoswami68?tab=repositories)

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > open_source_threads

<table>
<tr>
<td valign="top">

**HonmaruAI: Web Client Auth & Real-Time Sync**

August 2026 · Cloudflare Workers · [Merged PR #10](https://github.com/Torutesu/HonmaruAI/pull/10)

- Turned the reference web client into a real signed-in client: session-token auth, a browser create/decide flow reaching the WebSocket relay, and a CORS fix that unblocked all browser API calls.
- Iterated through multiple rounds of maintainer review, closing authorization gaps the review surfaced (org-membership checks, invite-role validation, identity uniqueness) and adding a test for each fix before merge.

</td>
</tr>
<tr>
<td valign="top">

**arkor: CLI Port-Fallback Fix**

[Merged PR](https://github.com/arkorlab/arkor/issues/199)

- Diagnosed and fixed a port-fallback bug in the `arkor dev` CLI command, taking the fix through multiple rounds of maintainer code review before it was merged into main.

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KinjalGoswami68&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&icon_color=dc2626&count_private=true" width="49%" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KinjalGoswami68&layout=compact&hide=html&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" width="49%" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=KinjalGoswami68&hide_border=true&background=0d1117&ring=8b5cf6&fire=dc2626&currStreakLabel=a78bfa&sideLabels=c9d1d9&currStreakNum=e9d5ff&sideNums=e9d5ff&dates=8b949e" width="98%" alt="Streak stats" />

</div>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > frontier_nodes

```text
[queued]  LLM evaluation + observability     (taking SentinelAI further)
[queued]  Agent workflows and tool use
[queued]  Retrieval quality in RAG systems
[active]  Cost-aware LLM systems             (tokens and cost per run)
```

## > open_connection

<div align="center">

<a href="https://www.linkedin.com/in/kinjal-goswami-03738a376"><img src="https://img.shields.io/badge/linkedin-open%20node-150f2e?style=for-the-badge&logo=linkedin&logoColor=a78bfa" alt="LinkedIn" /></a>
<a href="https://x.com/KGoswami70"><img src="https://img.shields.io/badge/x-follow%20thread-150f2e?style=for-the-badge&logo=x&logoColor=a78bfa" alt="X" /></a>
<a href="mailto:kinjalgoswami682@gmail.com"><img src="https://img.shields.io/badge/email-send%20packet-150f2e?style=for-the-badge&logo=gmail&logoColor=a78bfa" alt="Email" /></a>

</div>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

```text
kinjal@web:~$ ./crawl --status
[ok] connection closed. the web stays alive and the spider keeps crawling.
```