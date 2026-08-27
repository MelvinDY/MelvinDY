<h1 align="center">Melvin Darial Yogiana</h1>

<p align="center">
  <b>Data Analyst &amp; Analytics Engineer</b> · Sydney, Australia
</p>

<p align="center">
  <a href="https://melvindarialyogiana.com">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/melvin-yogiana/">LinkedIn</a> ·
  <a href="mailto:melvindarialyogiana@gmail.com">Email</a>
</p>

---

Computer Science graduate from UNSW Sydney, working across analytics and data
engineering. I take a question from the raw extract through to the dashboard a
decision is made in, so definitions stay consistent across the whole pipeline
instead of being handed off midway.

**Now:** Data Analyst and Automation Engineer Intern at **Foresight Analytics**,
turning LSEG and Bloomberg market data into the models the firm reports on, with
the pipelines running on Azure.

**Open to:** Data Analyst, Analytics Engineer and graduate roles in Sydney.

---

### Data work

Four case studies, each documented end to end. Three run on live sources; the
fourth uses generated data, which is labelled as such on the project page.

| Study | What it is | Headline finding |
|---|---|---|
| [**Woolworths vs Coles Price Analytics**](https://melvindarialyogiana.com/projects/data/grocery) | Competitor benchmarking across a year of prices from two retailers | **7.1%** price parity in household goods against **62.5%** in pantry — the chains compete on items shoppers can price from memory, and barely at all elsewhere |
| [**Australian Labour Market Dashboard**](https://melvindarialyogiana.com/projects/data/labour-market) | End-to-end pipeline on live ABS data | **2017** marks the point where the gender full-time gap began closing for a different underlying reason |
| [**SaaS Sales &amp; Revenue Analytics**](https://melvindarialyogiana.com/projects/data/saas) | Cohort retention across 12.5K invoices | **37%** of the discount-promo cohort remained at month six, against roughly **71%** for neighbouring cohorts |
| [**YouTube Trending Analytics**](https://melvindarialyogiana.com/projects/data/youtube) | Analysis of 40,000 trending videos | **38 hours** is the average time a video survives on the Trending page |

### Featured repository

[**woolworths-vs-coles-analytics**](https://github.com/MelvinDY/woolworths-vs-coles-analytics)
is the fullest example of how I work, covering collection, matching, validation
and reporting.

- **Daily collection since July 2026**, writing one immutable CSV per day. Days
  with no collection are recorded as missing and never backfilled with estimates.
- **Entity resolution across two catalogues.** National brands are matched on
  brand, pack size within 2% and a fuzzy name score; home brands are held
  separately as substitutes rather than treated as the same product. Every
  accepted pair stores its match score, so any pairing can be audited.
- **A year of history backfilled** from an open tracker keyed on the same
  retailer product IDs, then validated against independently collected days at
  **99.97% agreement over 22,616 observations** before any figure was built on it.
- **A pre-registered test.** The item list and expected values were committed to
  git before any bucket-level figure was computed, so the commit timestamps
  establish that the predictions came first. Seven of twelve fell within range;
  the largest miss is analysed in detail.
- [**docs/data_quality.md**](https://github.com/MelvinDY/woolworths-vs-coles-analytics/blob/master/docs/data_quality.md)
  documents four defects that reached published figures before being caught. One
  reversed a previously published headline, and the correction is published
  alongside it. The full test suite passed in all four cases.

### Software

| Project | What it is | Stack |
|---|---|---|
| **Podium** | Q&A platform for Atlassian townhalls, built as the UNSW COMP3900 capstone with Atlassian. Published on the Atlassian Marketplace and still in use there | Atlassian Forge, React, Node |
| [**Research Dashboard**](https://research-dashboard-demo.vercel.app/demo) | Fund manager research dashboard for an investment research house, reading a SharePoint list live through the Microsoft Graph API so the research team maintains it without a developer | Next.js, Graph API, Azure SQL |
| **DORA** | Snowflake warehouse computing the four DORA delivery metrics, enriched in-warehouse with Cortex | Snowflake, Cortex, dbt |
| [**Rate My Accom NSW**](https://github.com/MelvinDY/ratemyaccom) | Review platform for NSW student housing, with university-email verification, multi-dimensional ratings and rate limiting | Next.js, TypeScript, PostgreSQL |
| [**Ignite**](https://github.com/MelvinDY/ignite) | The official PPIA UNSW platform, carrying member profiles, event tooling and a directory for the Indonesian student community | Next.js, TypeScript |
| [**OnlyCode**](https://github.com/tangkenzee/OnlyCode) | Gamified peer-to-peer coding platform with real-time collaboration, skill-based matchmaking and sandboxed execution | React, TypeScript, WebSocket |

Podium and DORA are in private repositories. Both, along with Haven and other
work, are documented at
[melvindarialyogiana.com/projects/software](https://melvindarialyogiana.com/projects/software).

### Tech

**Data**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)

**Software**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Platform**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

---

### Background

- **BSc Computer Science**, UNSW Sydney, 2023 to 2026. GPA 3.00 / 4.00.
- **Diploma in Computer Science**, UNSW College, 2022 to 2023.
- **Data and cloud engineering**, self-directed and ongoing through DataCamp,
  Microsoft and Databricks.
- Previously Software Developer on Podium (UNSW COMP3900 capstone with
  Atlassian) and Frontend Lead at PPIA UNSW.

**Awards** — 1st place, CSESoc Flagship Hackathon 2025
([OnlyCode](https://github.com/tangkenzee/OnlyCode)); Most Fun Idea and 3rd Best
Design, UNIHACK 2026 ([Peersuade](https://devpost.com/software/peersuade)),
across 1,010 participants from 20+ universities; Golden Rubbish Bin, UNSW
Terrible Ideas Hackathon ([Stall Wars](https://github.com/MelvinDY/Stall_Wars)).
