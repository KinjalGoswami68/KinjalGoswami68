<div align="center">
<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/hero.svg" alt="Kinjal - AI/ML engineer" width="100%" />
</div>

<br/>

## > crawl.status

```text
identity   : CS student / AI-ML engineer in the making
mode       : building practical AI systems, in public
session    : AI/ML Intern @ a Bangalore-based startup
interests  : Machine Learning · LLMs · GenAI · RAG · AI Agents · Backend systems
learning   : DSA · ML engineering · production AI
contributes: open source
```

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > currently_crawling

| Target | Status | Why it matters |
|:--|:--|:--|
| ML engineering | `indexing` | Training is the easy part. Evaluation, deployment and monitoring are what make a model useful. |
| RAG + agents | `indexing` | Retrieval quality and tool use decide whether LLM apps are reliable. |
| DSA + C++ | `queued, daily` | Strong fundamentals keep every other layer fast and clean. |
| Open source | `crawling` | Reading real codebases and shipping fixes upstream. |

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
        CPP["C++"]
        API["FastAPI"]
        SQL["SQL"]
        GIT["Git / GitHub"]
    end

    subgraph SHIPPED["shipped"]
        SENT["SentinelAI"]:::hero
        CRA["Contract Risk Analyzer"]:::proj
        OTS["Orbital Terrain Scanner"]:::proj
        OSINT["OSINT tooling"]:::proj
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
    PY --- CPP
    API --- SQL
    GIT --- PY

    SENT -.- API
    SENT -.- SQL
    SENT -.- ML
    SENT -.- LLM
    CRA -.- ML
    CRA -.- LLM
    CRA -.- PY
    OTS -.- PY
    OTS -.- ML
    OSINT -.- PY
    OSINT -.- AGENTS

    classDef root fill:#3b0a0a,stroke:#dc2626,stroke-width:3px,color:#ffffff;
    classDef hero fill:#2e1065,stroke:#a78bfa,stroke-width:3px,color:#ffffff;
    classDef proj fill:#0f172a,stroke:#3b82f6,stroke-width:2px,color:#dbeafe;
    linkStyle default stroke:#6d5bd0,stroke-width:1px;
```

<div align="center">

<img src="https://img.shields.io/badge/Python-150f2e?style=flat-square&logo=python&logoColor=a78bfa" alt="Python" />
<img src="https://img.shields.io/badge/C++-150f2e?style=flat-square&logo=cplusplus&logoColor=a78bfa" alt="C++" />
<img src="https://img.shields.io/badge/FastAPI-150f2e?style=flat-square&logo=fastapi&logoColor=a78bfa" alt="FastAPI" />
<img src="https://img.shields.io/badge/PostgreSQL-150f2e?style=flat-square&logo=postgresql&logoColor=a78bfa" alt="SQL" />
<img src="https://img.shields.io/badge/Supabase-150f2e?style=flat-square&logo=supabase&logoColor=a78bfa" alt="Supabase" />
<img src="https://img.shields.io/badge/Hugging%20Face-150f2e?style=flat-square&logo=huggingface&logoColor=a78bfa" alt="Hugging Face" />
<img src="https://img.shields.io/badge/Streamlit-150f2e?style=flat-square&logo=streamlit&logoColor=a78bfa" alt="Streamlit" />
<img src="https://img.shields.io/badge/Git-150f2e?style=flat-square&logo=git&logoColor=a78bfa" alt="Git" />

</div>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > featured_node: SentinelAI

<table>
<tr>
<td width="60%" valign="top">

**Production LLM quality-monitoring system.**

SentinelAI watches an LLM application in production and flags quality drift before users notice. Responses are embedded with TF-IDF and scored with **Isolation Forest** and **CUSUM** change detection. Anomalies trigger **Slack webhook** alerts.

`FastAPI` · `Supabase Postgres` · `Render` · `Isolation Forest` · `CUSUM` · `Slack alerts`

[**Repository**](https://github.com/KinjalGoswami68/YOUR_SENTINELAI_REPO) · [**Live demo**](YOUR_SENTINELAI_DEMO_URL)

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

[Repository](https://github.com/KinjalGoswami68/YOUR_CONTRACT_RISK_REPO)

</td>
<td width="50%" valign="top">

**Orbital Terrain Scanner**

[1-2 lines: what it scans, what data or imagery it uses, and what it outputs.]

`[tech]` · `[tech]` · `[tech]`

[Repository](https://github.com/KinjalGoswami68/YOUR_ORBITAL_REPO)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**OSINT tooling**

[1-2 lines: what it collects, how it processes the data, what problem it solves.]

`[tech]` · `[tech]` · `[tech]`

[Repository](https://github.com/KinjalGoswami68/YOUR_OSINT_REPO)

</td>
<td width="50%" valign="top">

**More threads**

Smaller experiments, notebooks and builds live in my repositories.

[Browse all repositories](https://github.com/KinjalGoswami68?tab=repositories)

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

## > active_session

```text
$ crawl --session active

role    : AI/ML Intern
org     : YOUR_STARTUP_NAME · Bangalore, India
focus   : [what you build there: LLM features, RAG pipelines, agents, backend APIs]
stack   : [Python · FastAPI · ... edit to match]
status  : in progress
```

## > open_source_threads

| Repository | Contribution | Status |
|:--|:--|:--|
| [arkorlab/arkor](https://github.com/arkorlab/arkor/pull/212) | PR #212, a port-fallback fix in the CLI | `merged` |
| [YOUR_ORG/YOUR_REPO](https://github.com/YOUR_ORG/YOUR_REPO) | [short description] | `open` |

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
[daily ]  DSA practice in C++ and Python
[queued]  GSoC 2027 preparation
```

## > open_connection

<div align="center">

<a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/linkedin-open%20node-150f2e?style=for-the-badge&logo=linkedin&logoColor=a78bfa" alt="LinkedIn" /></a>
<a href="https://x.com/KGoswami70"><img src="https://img.shields.io/badge/x-follow%20thread-150f2e?style=for-the-badge&logo=x&logoColor=a78bfa" alt="X" /></a>
<a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/email-send%20packet-150f2e?style=for-the-badge&logo=gmail&logoColor=a78bfa" alt="Email" /></a>
<a href="YOUR_PORTFOLIO_URL"><img src="https://img.shields.io/badge/portfolio-visit%20site-150f2e?style=for-the-badge&logo=googlechrome&logoColor=a78bfa" alt="Portfolio" /></a>

</div>

<img src="https://raw.githubusercontent.com/KinjalGoswami68/KinjalGoswami68/main/assets/divider.svg" width="100%" alt="" />

```text
kinjal@web:~$ ./crawl --status
[ok] connection closed. the web stays alive and the spider keeps crawling.
```