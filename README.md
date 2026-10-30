Available for Research & Data Projects

# Pawan Jangra Data Analyst & Economic Researcher

New Delhi, India · Society for Social & Economic Research · 7+ years

[⚙ pawan1198](https://github.com/pawan1198) [in LinkedIn](https://linkedin.com/in/pawanjangra1198) [🌐 SSER](https://indianstatistics.org) [✍ Medium](https://medium.com/@pawanjangra1198) [📅 Book a Session](https://topmate.io/pawanjangra1198)

0

Repositories

0

Stars Earned

0

Years Research

0

Countries Analysed

R Console — pawan@sser

\> # Load Pawan's stack

\> library(data.table)

\> library(ggplot2)

\> library(ggiraph)

\> library(shiny)

\> # Analyse India trade data

\> dt \<- fread("india_trade.csv")

\> dt\[year == 2024,

.(exports = sum(value)),

by = commodity\]

\[1\] HHI concentration risk: LOW

\[2\] Top sector: Engineering goods

>

About Me

I'm an independent data analyst and economic researcher specialising in **Indian microdata** — government surveys (PLFS, NSS), trade statistics (DGCI&S/DGFT HS-code), agricultural markets, and public finance. I build reproducible analytical pipelines in **R** and publish them as interactive Quarto documents, Shiny dashboards, and research reports.

### 🏛 Current Affiliation

Independent Research Consultant working with the **Society for Social and Economic Research (SSER)**, New Delhi. Former Technical & Course Assistant, **IDEAs Advanced Certificate Programme**, OP Jindal Global University.

### 🔬 Research Focus

**Labour markets** (PLFS wage inequality, employment transitions) · **Agricultural economics** (price transmission, food security) · **Public finance** (GST compliance, fiscal policy) · **Trade analysis** (HHI concentration, import risk)

### 📋 Field Experience

Designed and led **door-to-door surveys** using ODK/KoboToolbox/SurveyCTO. Managed data from collection through cleaning, validation, and reporting. Trained field investigators and coordinated multi-state survey operations.

### 📚 Education Content

Authored an **18-chapter R statistics textbook** and a **25-chapter data.table book** using Indian economic data as examples. Created cheat sheets and tutorials used by researchers transitioning to R.

Domain Expertise

Labour Markets (PLFS) NSS Microdata Agricultural Price Analysis Edible Oils & Fertilizers Foreign Trade (HS-code) GST Analytics Choropleth Mapping Shiny Dashboards IMF GFS (180 countries) Survey Methodology (PPS, SRS) Time Series Forecasting Panel Data Econometrics RBI Bank Credit Analysis ARIMA / ETS Forecasting Quarto Publishing Data Journalism

Technical Skills

### R — Core Analysis

data.table98%

ggplot295%

ggiraph90%

Shiny / shinydashboard85%

gt / gtsummary88%

### R — Specialist

sf / tmap (mapping)80%

forecast / fable78%

Quarto / R Markdown92%

rvest / RSelenium72%

plm / fixest (panel)75%

### Python & Tools

Python / pandas75%

openpyxl / xlwings70%

Git / GitHub Actions80%

Linux / Bash70%

ODK / SurveyCTO / KoBo85%

Data Sources & Ecosystems

MOSPI / PLFS NSS Microdata DGCI&S / DGFT RBI Databases Ministry of Commerce FCI / NITI Aayog IMF GFS World Bank WDI ILO Rilostat FAOSTAT WID.world UN Comtrade PPAC / ICED GST Portal

Featured Repositories

[📦 portfolio ★ 1 Quarto-powered personal portfolio with custom SCSS themes, animated slide-in drawer, and automated content listing — 28 integrated items across data viz, articles, and blog. Quarto SCSS GitHub Pages HTML](https://github.com/pawan1198/portfolio) [📚 r-cheatsheets ★ 6 Comprehensive R cheat sheets covering data.table, ggplot2, and statistical methods — with Indian economic data examples and visual reference guides. data.table ggplot2 R Markdown HTML](https://github.com/pawan1198/r-cheatsheets) [📊 ggplot ★ 2 Gallery of ggplot2 visualisations including TidyTuesday entries, ggiraph interactive charts, and economic data plots with custom themes and publication-ready styling. ggplot2 ggiraph TidyTuesday HTML](https://github.com/pawan1198/ggplot) [📖 statistics-with-R ★ 0 18-chapter Quarto statistics textbook using Indian agricultural and economic data. Covers foundations through panel data, time series, and APA 7th edition reporting. Quarto data.table Book HTML](https://github.com/pawan1198/statistics-with-R) [🐍 Python-for-Beginners ★ 2 Jupyter notebook series for social science researchers starting Python — emphasises practical data tasks (pandas, visualisation) over abstract programming concepts. Python Jupyter pandas Jupyter Notebook](https://github.com/pawan1198/Python-for-Beginners) [🏦 GST Analytics (2017–2026) Private End-to-end R pipeline parsing India GST collection data — 11 ggplot2 visualisations, Shiny dashboard with ARIMA/ETS forecasting, and a LinkedIn PDF carousel. Shiny forecast ggplot2 GST Data R](https://github.com/pawan1198) [🗺 PLFS Labour Market Analysis Quarto Full PLFS 2018–2022 labour market analysis — choropleth maps (sf), ggiraph interactive plots, gt tables, wage inequality trends, and employment transition matrices. data.table sf / maps ggiraph PLFS R](https://github.com/pawan1198) [🏦 RBI Bank Credit Pipeline Analysis Parsed 42 monthly RBI Excel releases (Jan 2014–Apr 2026), spliced two data sources, handled corrupted date cells — key finding: NBFC credit fastest-growing indicator. data.table readxl ggplot2 RBI R](https://github.com/pawan1198)

Research & Analysis Work

India Labour Market: PLFS Microdata Analysis (2018–2022)

MOSPI · PLFS Rounds 1–4 · Quarto + Shiny

Comprehensive wage inequality and employment transition analysis across India's 36 states/UTs. Built choropleth maps with state-name mismatch fixes, ggiraph interactive plots showing LFPR by gender and sector, and a gt-formatted summary report.

Labour Economics Microdata Survey Analysis sf / Choropleth

India Foreign Trade: HHI Concentration Risk (2000–2024)

DGCI&S / DGFT · HS-code disaggregated data · data.table pipeline

Bilateral trade analysis at HS-2/4/6 level, computing Herfindahl-Hirschman Index for import concentration risk across 180+ partner countries. Identified commodity-level diversification gaps and export competitiveness trends.

International Trade HHI Analysis HS-code Data Policy Research

NSS 75th Round: Health & Education Microdata (Schedule 25.0 & 25.2)

NSSO · NSS 75th Round · 16-page Word report

Extracted and analyzed NSS microdata on household health expenditure and educational outcomes. Produced interactive ggiraph plots, gt tables with footnotes, and a formatted 16-page research report via Node.js/docx.

Health Economics Education NSS Microdata Survey Design

IMF Government Finance Statistics: 180-Country Revenue Analysis

IMF GFS · Cross-country Panel · Statistical Artifact Identification

Analyzed government revenue trends across 180 countries in the IMF GFS dataset. Identified a sample-composition artifact masking true fiscal trajectories in apparent revenue trends — flagged as methodological finding for working paper.

Public Finance IMF Data Panel Data Fiscal Policy

RBI Sectoral Bank Credit: Jan 2014 – Apr 2026

RBI · 42 Monthly Excel Releases · Data Splicing Pipeline

Built a robust pipeline parsing 42 monthly RBI Excel releases across two data source formats. Handled corrupted date cells, column-schema changes, and splice-point discontinuities. Key finding: broad-based industrial credit recovery with NBFC credit as fastest-growing segment.

Banking RBI Data Credit Analysis NBFC

Real-Time Global Inequality Dashboard

WID.world · ILO Rilostat · priceR API · Shiny

Built a live Shiny dashboard integrating three international APIs — WID.world wealth shares, ILO labour statistics, and priceR purchasing-power adjustment — with India as default country and reactive country-switcher.

Inequality API Integration Shiny Dashboard Global Data

GitHub Activity Dashboard

0

Public Repos

0

Stars Earned

0

Following

0

Followers

LANGUAGE BREAKDOWN · By Repository Count

SKILLS RADAR · Self-Assessment

COMMIT ACTIVITY · Monthly Estimate (2024–2026)

Pinned Repositories

### portfolio ★1

Quarto personal site with animated drawer & 28 content items

### r-cheatsheets ★6

data.table · ggplot2 · Indian economic data examples

### ggplot ★2

ggiraph interactive charts & TidyTuesday gallery

### statistics-with-R

18-chapter textbook with Indian agricultural data contexts

### Python-for-Beginners ★2

Jupyter notebooks for social science researchers

### Portfolio site

pawan1198.github.io/portfolio, live Quarto site

Get in Touch

[💼 LinkedIn pawanjangra1198](https://linkedin.com/in/pawanjangra1198) [𝕏 X / Twitter @pawanjangra1198](https://x.com/pawanjangra1198) [📅 Book a Session topmate.io/pawanjangra1198](https://topmate.io/pawanjangra1198) [✍️ Medium @pawanjangra1198](https://medium.com/@pawanjangra1198)

### Open to Opportunities

📊 Freelance Data Analysis 🔬 Research Collaboration 📋 Survey Design & Field Coordination 📚 R Tutorials & Workshops ✍️ Technical Writing 🌐 Open Educational Resources
