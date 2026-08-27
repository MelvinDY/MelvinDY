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

An Indonesian Computer Science graduate from UNSW, building in Sydney. The degree
made me an engineer and the work made me an analyst, and the analyst is the one
I am betting on.

The engineering is not a hedge. It is the reason I can take a question from the
raw extract all the way to the thing somebody makes a decision in, without
handing it to another team halfway and hoping the definitions survive the trip.

**Now:** Data Analyst and Automation Engineer Intern at **Foresight Analytics**,
turning LSEG and Bloomberg market data into models the firm reports on, with the
pipelines running on Azure.

**Open to:** Data Analyst, Analytics Engineer and graduate roles in Sydney.

---

### Data work

Four case studies, each written up in full. Three run on live sources and the
fourth is generated data, which is labelled as such on the page rather than left
for you to work out.

| Study | What it is | The finding |
|---|---|---|
| [**Woolworths vs Coles Price Analytics**](https://melvindarialyogiana.com/projects/data/grocery) | Competitor benchmarking, a year of prices from two retailers | **7.1%** parity rate in household against 62.5% in pantry. The two chains compete where shoppers can price from memory and barely at all where they cannot |
| [**Australian Labour Market Dashboard**](https://melvindarialyogiana.com/projects/data/labour-market) | End to end pipeline on live ABS data | **2017**, the year the gender full-time gap started closing for a different reason |
| [**SaaS Sales &amp; Revenue Analytics**](https://melvindarialyogiana.com/projects/data/saas) | Cohort retention from 12.5K invoices | **37%** of the discount-promo cohort was still a customer at month six. Neighbouring cohorts kept about 71% |
| [**YouTube Trending Analytics**](https://melvindarialyogiana.com/projects/data/youtube) | Forensics on 40,000 trending videos | **38 hours** is how long the average video survives on the Trending page before it vanishes |

### The one I would open first

[**woolworths-vs-coles-analytics**](https://github.com/MelvinDY/woolworths-vs-coles-analytics)
is the repo I would rather be judged on, because it contains the parts most
portfolios leave out.

- A collector that has run daily since July 2026, writing one immutable CSV a
  day, on the rule that **a day nobody collected is never filled in**.
- Entity resolution across two catalogues: national brands matched on brand,
  pack size within 2% and a fuzzy name score, home brands held separately as
  substitutes rather than as the same product. Every accepted pair carries its
  score, so any match can be pulled up and shown why.
- A year of history backfilled from an open tracker keyed on the same retailer
  product ids, and then **checked against my own collected days at 99.97% over
  22,616 observations** before a single figure was built on it.
- A **pre-registered** test. The item list and the expected numbers were
  committed to git before any bucket-level figure was computed, so the commit
  timestamp proves the predictions came first. Seven of twelve landed in range.
  The one that failed hardest is the most interesting thing on the page.
- [`docs/data_quality.md`](https://github.com/MelvinDY/woolworths-vs-coles-analytics/blob/master/docs/data_quality.md),
  four failures that reached published figures before they were caught, written
  up in full. One of them **reversed a headline I had already published**, and
  the correction is on the site rather than quietly applied. Every test in the
  project passed on all four.

### Software

The analyst half is the bet, but the engineering is what makes the analysis
shippable, so it gets a section.

| Project | What it is | Stack |
|---|---|---|
| **Podium** | Q&A platform for Atlassian townhalls, built as the UNSW COMP3900 capstone with Atlassian. Published on the Atlassian Marketplace and still in use there | Atlassian Forge, React, Node |
| [**Research Dashboard**](https://research-dashboard-demo.vercel.app/demo) | Fund manager research dashboard for an investment research house, reading a SharePoint list live through the Microsoft Graph API so the research team maintains it without a developer | Next.js, Graph API, Azure SQL |
| **DORA** | Snowflake warehouse computing the four DORA delivery metrics, enriched in-warehouse with Cortex | Snowflake, Cortex, dbt |
| [**Rate My Accom NSW**](https://github.com/MelvinDY/ratemyaccom) | Review platform for NSW student housing, with university-email verification, multi-dimensional ratings and rate limiting | Next.js, TypeScript, PostgreSQL |
| [**Ignite**](https://github.com/MelvinDY/ignite) | The official PPIA UNSW platform, carrying member profiles, event tooling and a directory for the Indonesian student community | Next.js, TypeScript |
| [**OnlyCode**](https://github.com/tangkenzee/OnlyCode) | Gamified peer-to-peer coding platform with real-time collaboration, skill-based matchmaking and sandboxed execution | React, TypeScript, WebSocket |

Podium and DORA carry no link because their repos are private. Those two, Haven
and the rest are described in full at
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

Three hackathons, four awards: **1st place** at the CSESoc Flagship Hackathon
2025 for [OnlyCode](https://github.com/tangkenzee/OnlyCode); **Most Fun Idea and
3rd Best Design** at UNIHACK 2026 for
[Peersuade](https://devpost.com/software/peersuade), across 1,010 participants
from 20+ universities; and the **Golden Rubbish Bin** for best terrible idea at
the UNSW Terrible Ideas Hackathon for
[Stall Wars](https://github.com/MelvinDY/Stall_Wars).
