# PPOL 652 — Course Reference & Practitioner Resource Bank

**Complexity Seminar: How Do You Address Policy Problems with Data? (Fall 2026)**

Beyond the short pre-course readings, these open-access books, practitioner guides, and official data portals are useful references to bookmark during the seminar and throughout the MPP program. Every item below links directly to its open-access edition or official portal.

---

## 1. Pre-Course Preparation

* Roger D. Peng & Elizabeth Matsui (2016), [*The Art of Data Science: A Guide for Anyone Who Works with Data*](https://bookdown.org/rdpeng/artofdatascience/) ([Leanpub edition](https://leanpub.com/artofdatascience))
* Radiolab (2009), [*"Numbers"* (Season 6, Episode 3)](https://radiolab.org/podcast/91697-numbers)

---

## 2. Core Data Reasoning, Visualization & Spreadsheet Workflows

* Jack Dougherty & Ilya Ilyankou (2021), [*Hands-On Data Visualization: Interactive Storytelling from Spreadsheets to Code*](https://handsondataviz.org/)
* Karl W. Broman & Kara H. Woo (2018), ["Data Organization in Spreadsheets"](https://doi.org/10.1080/00031305.2017.1375989) ([Open Preprint](https://kbroman.org/Paper_DataOrg/)), *The American Statistician*, 72(1), 2–10
* Datawrapper Academy ([`academy.datawrapper.de`](https://academy.datawrapper.de/)) & [*The Datawrapper River*](https://www.datawrapper.de/academy/how-to-use-the-river)
* Claus O. Wilke (2019), [*Fundamentals of Data Visualization: A Primer on Making Informative and Compelling Figures*](https://clauswilke.com/dataviz/)
* Jane E. Miller (2015), [*The Chicago Guide to Writing about Numbers* (2nd ed.)](https://press.uchicago.edu/ucp/books/book/chicago/C/bo19910133.html), University of Chicago Press

---

## 3. Reproducible Pipelines, Code, Version Control & `uv`

* Matthew Gentzkow & Jesse M. Shapiro (2014), [*Code and Data for the Social Sciences: A Practitioner's Guide*](https://web.stanford.edu/~gentzkow/research/CodeAndData.pdf)
* Arthur Turrell / Bank of England, [*Coding for Economists*](https://aeturrell.github.io/coding-for-economists/) — see especially [Setting Up VS Code](https://aeturrell.github.io/coding-for-economists/setup-ide.html) and [Command Line Basics](https://aeturrell.github.io/coding-for-economists/ug-command-line.html)
* Grant McDermott, [*Data Science for Economists* (`EC 607`)](https://github.com/uo-ec607/lectures)
* Rohan Alexander (2023), [*Telling Stories with Data: With Applications in R*](https://tellingstorieswithdata.com/)
* Nick Huntington-Klein (2022), [*The Effect: An Introduction to Research Design and Causality*](https://theeffectbook.net/)

### Understanding Version Control (Conceptual Git for Agentic Workflows)
In an agent-assisted workflow, you can let the coding agent run the day-to-day Git commands for you—its main return on investment is giving you a clean history and a safety net when an agent modifies files autonomously. These two short, command-free reads explain *why* version control exists and what happens under the hood:
* *The Turing Way* — [*Guide to Version Control*](https://book.the-turing-way.org/reproducible-research/vcs/) (a gentle, non-technical introduction to commits, diffs, and project history)
* Jenny Bryan (2018), ["Excuse Me, Do You Have a Moment to Talk About Version Control?"](https://peerj.com/preprints/3159/), *The American Statistician*, 72(1), 20–27

### Python Environments & `uv`
Rather than installing packages into a global system Python (where conflicting versions and path issues quickly accumulate), we use **`uv`** to keep each project's Python version and libraries isolated and reproducible:
* *Bite Code!* — [*Relieving Your Python Packaging Pain*](https://www.bitecode.dev/p/relieving-your-python-packaging-pain) & [*A Year of `uv`: Pros, Cons, and Should You Migrate*](https://www.bitecode.dev/p/a-year-of-uv-pros-cons-and-should) (why traditional Python installations break and how `uv` fixes them)
* Astral — [*`uv`: Unified Python Packaging*](https://astral.sh/blog/uv-unified-python-packaging) | [Installing `uv`](https://docs.astral.sh/uv/getting-started/installation/) | [Working on Projects (`uv init`, `uv add`, `uv run`)](https://docs.astral.sh/uv/guides/projects/)

---

## 4. AI-Empowered Economists & Policy Researchers (An Evolving Menu)

There is no single canonical way to pair empirical economics or policy analysis with coding agents; the practices below are an evolving menu of choices from active researchers ranging from zero-code social science setups to full multi-agent repositories:

* Chris Blattman (University of Chicago) — [*Claude Blattman: AI Workflows for Social Scientists*](https://claudeblattman.com/) ([GitHub repository](https://github.com/chrisblattman/claudeblattman)) — written specifically for social scientists with little or no software engineering background on moving from browser chat to a project folder, `CLAUDE.md`, and verification habits.
* Benjamin Golub (Northwestern University) — [*Modern AI for Economics Research*](https://markusacademy.substack.com/p/modern-ai-for-economics-research) (Markus' Academy talk & notes) — a clear conceptual overview of why working inside an IDE and repository beats "the bureaucracy of browser tabs," alongside staged prompting and AI stress-testing.
* Paul Goldsmith-Pinkham (Yale University) — [*Claude Code for Applied Economists*](https://markusacademy.substack.com/p/claude-code-for-applied-economists) (8-part short video/post tutorial) & [*Research in the Time of AI*](https://paulgp.substack.com/p/research-in-the-time-of-ai) — practical walkthrough of terminal/IDE agents, data wrangling, plan mode, and where human economic judgment remains essential.
* Pedro H. C. Sant'Anna (Emory University) — [*Claude Code Academic Workflow (`claude-code-my-workflow`)*](https://github.com/pedrohcgs/claude-code-my-workflow) & [*AI Agents for Economic Research* (VoxDev Guide PDF)](https://voxdev.org/sites/default/files/2026-03/AI_Agents_for_Economic_Research.pdf) — an advanced, ready-to-fork template illustrating structured quality gates, reusable skills, and replication checks.
* OpenEcon — [*AI-Research-Setup Guide*](https://github.com/hanlulong/AI-research-setup) (step-by-step macOS/Windows setup for economics students) & [*Awesome AI for Economists*](https://github.com/hanlulong/awesome-ai-for-economists) (living directory of tools and guides).
* Anton Korinek (University of Virginia / NBER) — [*Generative AI for Economic Research* (`genaiforecon.org`)](https://www.genaiforecon.org/) — companion site to his *Journal of Economic Literature* survey mapping AI use cases across ideation, writing, coding, and data analysis.
* Gábor Békés (Central European University) — [*Data Analysis with AI*](https://gabors-data-analysis.com/ai-course/) — applied empirical data-analysis exercises and prompts from the co-author of *Data Analysis for Business, Economics, and Policy*.

---

## 5. Official Canadian & International Open Data Portals

### McGill Library & Canadian Research Data Repositories
* McGill University Library — [Data & Statistics Research Guide](https://libraryguides.mcgill.ca/data/home) | [Maps & Geospatial Data Guide](https://libraryguides.mcgill.ca/maps/home)
* Borealis (The Canadian Dataverse Repository) — [`borealisdata.ca`](https://borealisdata.ca/)

### Canadian Federal, Provincial & Think Tank Data
* Statistics Canada — [Data Tables Portal](https://www150.statcan.gc.ca/n1/en/type/data) | [Web Data Service (API) Guide](https://www.statcan.gc.ca/en/developers/wds/user-guide)
* Bank of Canada — [Valet API & Data Portal](https://www.bankofcanada.ca/valet/docs) | [Consumer Price Index (CPI) Portal](https://www.bankofcanada.ca/rates/price-indexes/cpi/)
* Open Government Portal Canada — [`search.open.canada.ca/opendata`](https://search.open.canada.ca/opendata/) | [ECCC Facility Greenhouse Gas Reporting (GHGRP)](https://open.canada.ca/data/en/dataset/a8ba14b7-7f23-462a-bdbb-83b0ef629823) | [National Inventory Report (NIR) Emissions](https://open.canada.ca/data/en/dataset/779c7bcf-4982-47eb-af1b-a33618a05e5b)
* Canadian Institute for Health Information (CIHI) — [National Health Expenditure Trends (NHEX)](https://www.cihi.ca/en/national-health-expenditure-trends)
* Canada Mortgage and Housing Corporation (CMHC) — [Housing Market Information Portal (HMIP)](https://www03.cmhc-schl.gc.ca/hmip-pimh/en#Profile/1/1/Canada)
* Canadian Climate Institute / 440 Megatonnes — [Canadian Emissions Intensity Database](https://440megatonnes.ca/understanding-the-canadian-emissions-intensity-database/)
* Institute for Research on Public Policy (IRPP) — [Community Transformations Project](https://irpp.org/community-transformations/)

### Comparative & International Data
* World Bank — [World Development Indicators (WDI)](https://databank.worldbank.org/source/world-development-indicators)
* Our World in Data — [`ourworldindata.org`](https://ourworldindata.org/)
* OECD — [OECD Data Explorer](https://data-explorer.oecd.org/)
* Quality of Government (QoG) Institute — [QoG Standard Datasets](https://www.gu.se/en/quality-government/qog-data/data-downloads/standard-dataset)
