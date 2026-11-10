<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0d3b6e,100:0d1117&height=200&section=header&text=Gourav%20Gore&fontSize=56&fontColor=e6f1ff&fontAlignY=40&desc=Data%20Engineer%20%C2%B7%20ETL%20Pipelines%20%C2%B7%20Data%20Warehousing%20%C2%B7%20Analytics&descAlignY=62&descSize=16&animation=fadeIn"/>

<a href="https://www.linkedin.com/in/gourav-gore">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=6CB6FF&center=true&vCenter=true&width=640&lines=Building+reliable+ETL+%26+ELT+pipelines;Modelling+data+warehouses+for+analytics;Turning+raw+data+into+business+insight;Open+to+Data+Engineering+roles" alt="Typing summary"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gourav%20Gore-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gourav-gore)
[![Email](https://img.shields.io/badge/Email-gaurav.gore19%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:gaurav.gore19@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/gaurav190901?style=flat-square&logo=github&label=Followers&color=24292f)](https://github.com/gaurav190901?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=gaurav190901&style=flat-square&color=6cb6ff&label=Profile+views)](https://github.com/gaurav190901)

**[About](#about-me) · [How I Build](#how-i-build-pipelines) · [Tech Stack](#tech-stack) · [Projects](#featured-projects) · [Activity](#github-activity) · [Contact](#get-in-touch)**

</div>

## About Me

I'm a Data Engineer who builds reliable, well-tested data pipelines. My work covers the full path from raw source data to analytics-ready datasets: ingestion, transformation, warehouse modelling, and the dashboards that business teams use to make decisions.

- **Focus areas:** ETL/ELT pipeline design, data warehousing, data quality, and workflow automation
- **Open to:** Data Engineering roles and collaboration on data projects

<details>
<summary><b>What I'm learning right now</b> (click to expand)</summary>
<br/>

| Topic | Status |
|:---|:---|
| Advanced dbt and Snowflake patterns | In progress |
| Apache Spark performance tuning | In progress |
| Kafka and real-time streaming | Up next |
| Cloud-native ETL (AWS Glue, Google Dataflow) | Up next |

</details>

## How I Build Pipelines

```mermaid
flowchart LR
    A[(Source systems<br/>APIs · CSV · databases)] --> B[Ingest<br/>Python · Airflow]
    B --> C[Transform<br/>SQL · dbt · Spark]
    C --> D{Data quality<br/>checks}
    D -- pass --> E[(Warehouse<br/>Snowflake · BigQuery · PostgreSQL)]
    D -- fail --> F[Alert and<br/>quarantine]
    E --> G[Dashboards<br/>Tableau · Power BI]
```

## Tech Stack

| Area | Tools |
|:---|:---|
| **Languages & Processing** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) |
| **Orchestration & Transformation** | ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) |
| **Databases & Warehouses** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white) |
| **BI & Visualization** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |

## Featured Projects

| Project | Language | Stars | Last updated |
|:---|:---|:---|:---|
| [**Airbnb Data Pipeline**](https://github.com/gaurav190901/AirBNB) | ![Language](https://img.shields.io/github/languages/top/gaurav190901/AirBNB?style=flat-square&color=6cb6ff) | ![Stars](https://img.shields.io/github/stars/gaurav190901/AirBNB?style=flat-square&color=6cb6ff) | ![Last commit](https://img.shields.io/github/last-commit/gaurav190901/AirBNB?style=flat-square&color=6cb6ff&label=) |
| [**Credit Card Transaction Analysis**](https://github.com/gaurav190901/Credit-Card-Transaction-Analysis) | ![Language](https://img.shields.io/github/languages/top/gaurav190901/Credit-Card-Transaction-Analysis?style=flat-square&color=6cb6ff) | ![Stars](https://img.shields.io/github/stars/gaurav190901/Credit-Card-Transaction-Analysis?style=flat-square&color=6cb6ff) | ![Last commit](https://img.shields.io/github/last-commit/gaurav190901/Credit-Card-Transaction-Analysis?style=flat-square&color=6cb6ff&label=) |
| [**Real Estate EDA**](https://github.com/gaurav190901/Real-Estate-EDA) | ![Language](https://img.shields.io/github/languages/top/gaurav190901/Real-Estate-EDA?style=flat-square&color=6cb6ff) | ![Stars](https://img.shields.io/github/stars/gaurav190901/Real-Estate-EDA?style=flat-square&color=6cb6ff) | ![Last commit](https://img.shields.io/github/last-commit/gaurav190901/Real-Estate-EDA?style=flat-square&color=6cb6ff&label=) |

*Click a project below for details.*

<details>
<summary><b>Airbnb Data Pipeline</b> · Python, SQL, Tableau</summary>
<br/>

Batch ETL pipeline that cleans and transforms 48K+ Airbnb listings into an analytics-ready dataset, visualized in Tableau.

```mermaid
flowchart LR
    A[(Raw Airbnb<br/>listings)] --> B[Clean & validate<br/>Python] --> C[Transform<br/>SQL] --> D[Tableau<br/>dashboard]
```

[View repository →](https://github.com/gaurav190901/AirBNB)

</details>

<details>
<summary><b>Credit Card Transaction Analysis</b> · SQL, Power BI</summary>
<br/>

Multi-dimensional analysis of credit card transactions using SQL, with interactive Power BI dashboards.

```mermaid
flowchart LR
    A[(Transaction<br/>data)] --> B[SQL analysis] --> C[Power BI<br/>dashboards]
```

[View repository →](https://github.com/gaurav190901/Credit-Card-Transaction-Analysis)

</details>

<details>
<summary><b>Real Estate EDA</b> · Python, Pandas</summary>
<br/>

Exploratory data analysis that combines multiple real estate data sources into a clear insight layer.

```mermaid
flowchart LR
    A[(Source 1)] --> C[Merge & clean<br/>Pandas]
    B[(Source 2)] --> C
    C --> D[Exploratory<br/>analysis] --> E[Insights]
```

[View repository →](https://github.com/gaurav190901/Real-Estate-EDA)

</details>

## GitHub Activity

<div align="center">

<img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gaurav190901&theme=github_dark" alt="GitHub stats"/>
<img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gaurav190901&theme=github_dark" alt="Repositories per language"/>

<br/><br/>

<img width="80%" src="https://streak-stats.demolab.com?user=gaurav190901&theme=github-dark-blue&hide_border=true" alt="GitHub contribution streak"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gaurav190901/gaurav190901/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gaurav190901/gaurav190901/output/github-snake.svg"/>
  <img src="https://raw.githubusercontent.com/gaurav190901/gaurav190901/output/github-snake-dark.svg" alt="Snake animation eating my GitHub contribution graph"/>
</picture>

</div>

## Get in Touch

<div align="center">

I'm always happy to talk about data engineering, pipeline architecture, or new opportunities.

[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gourav-gore)
[![Send an email](https://img.shields.io/badge/Send%20an%20email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gaurav.gore19@gmail.com)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0d3b6e,100:0d1117&height=100&section=footer"/>

</div>
