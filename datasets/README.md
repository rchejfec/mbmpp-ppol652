# PPOL 652 — Curated Datasets

Here are the curated datasets we will cover on Day 1. We have put these together to make it easier to get started and navigate a policy question quickly, though you are free to bring or acquire your own public data.

The datasets and their source documentation are organized across **6 Policy Themes** below (plus companion join-bridge tables in [`advanced_joins/`](advanced_joins/)).

> **How to view and download the datasets:** Do not rely on GitHub's browser preview to inspect CSV files—GitHub truncates or blocks web previews for files larger than 1 MB ("Sorry about that, but we can't show files that are this big right now"). To use any dataset, **download it to your computer** (click the file link, then click **Download raw file** / **Raw** in the top-right corner) or clone the repository locally.

---

## Theme 1: Canadian Climate, Industrial Carbon Intensity & Economic Output ([`theme1_climate_economy/`](theme1_climate_economy/))

* **[`CA_GHG_Facility_Emissions_Provincial.csv`](theme1_climate_economy/CA_GHG_Facility_Emissions_Provincial.csv)** — Annual facility greenhouse gas emissions and reporting facility counts by province/territory and NAICS industry. **Source:** [ECCC Facility Greenhouse Gas Reporting Program (GHGRP)](https://open.canada.ca/data/en/dataset/a8ba14b7-7f23-462a-bdbb-83b0ef629823)
* **[`CA_GHG_National_Economic_Sectors.csv`](theme1_climate_economy/CA_GHG_National_Economic_Sectors.csv)** — National annual greenhouse gas emissions across major Canadian economic sectors and subsectors. **Source:** [ECCC National Inventory Report (NIR)](https://open.canada.ca/data/en/dataset/779c7bcf-4982-47eb-af1b-a33618a05e5b)
* **[`CA_440Mt_Carbon_Intensity_NAICS.csv`](theme1_climate_economy/CA_440Mt_Carbon_Intensity_NAICS.csv)** — Direct and indirect (Scope 1, 2, and 3) emissions, economic output, GDP, and carbon intensities by Canadian NAICS industry and final demand category. **Source:** [Canadian Climate Institute / 440 Megatonnes Emissions Intensity Database](https://440megatonnes.ca/understanding-the-canadian-emissions-intensity-database/)
* **[`CA_GDP_Provincial_Industry.csv`](theme1_climate_economy/CA_GDP_Provincial_Industry.csv)** — Annual provincial and territorial GDP (nominal and chained 2017 dollars) by NAICS industry. **Source:** [Statistics Canada Table `36-10-0711-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3610071101)

---

## Theme 2: Canadian Housing Affordability, Rental Markets & Community Transition Risk ([`theme2_housing_communities/`](theme2_housing_communities/))

* **[`CA_Housing_Affordability_Census.csv`](theme2_housing_communities/CA_Housing_Affordability_Census.csv)** — Census household counts and shares in Core Housing Need, unaffordable, unsuitable, and inadequate housing across Canada, provinces/territories, and Census Divisions by tenure. **Source:** [Statistics Canada Table `98-10-0246-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=9810024601) | [Core Housing Need Definition](https://www12.statcan.gc.ca/census-recensement/2021/ref/dict/az/definition-eng.cfm?ID=households-menage037)
* **[`CA_CMHC_Rental_Market.csv`](theme2_housing_communities/CA_CMHC_Rental_Market.csv)** — Rental vacancy rates, turnover rates, average 2-bedroom rents, and rental universe counts across provinces and Census Metropolitan Areas. **Source:** [CMHC Rental Market Survey Data Tables](https://www.cmhc-schl.gc.ca/professionals/housing-markets-data-and-research/housing-data/data-tables/rental-market)
* **[`CA_IRPP_Community_Susceptibility.csv`](theme2_housing_communities/CA_IRPP_Community_Susceptibility.csv)** — Workforce susceptibility indicators and scores for net-zero, fossil-fuel, and manufacturing/trade transitions across Canadian Census Divisions. **Source:** [IRPP Community Transformations Project](https://irpp.org/community-transformations/) | [Methodology Study](https://irpp.org/research-studies/community-transformations-project-methodology/)

---

## Theme 3: Canadian Labour Markets, Job Vacancies, Wages & Provincial Growth ([`theme3_labour_growth/`](theme3_labour_growth/))

* **[`CA_Labour_Force_Monthly.csv`](theme3_labour_growth/CA_Labour_Force_Monthly.csv)** — Monthly labour force, employment (full-time and part-time), unemployment, and population counts by province and age group. **Source:** [Statistics Canada Table `14-10-0287-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410028701) | [LFS Methodology](https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=3701)
* **[`CA_Job_Vacancies_Wages_Quarterly.csv`](theme3_labour_growth/CA_Job_Vacancies_Wages_Quarterly.csv)** — Quarterly job vacancies, payroll employees, job vacancy rates, and average offered hourly wages by province/territory and NAICS sector. **Source:** [Statistics Canada Table `14-10-0442-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410044201) | [JVWS Methodology](https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=5217)
* **[`CA_GDP_Provincial_Industry.csv`](theme1_climate_economy/CA_GDP_Provincial_Industry.csv)** — Annual provincial and territorial GDP by NAICS industry (located in [`theme1_climate_economy/`](theme1_climate_economy/)). **Source:** [Statistics Canada Table `36-10-0711-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3610071101)

---

## Theme 4: Canadian Health & Long-Term Care Spending and Demographic Aging ([`theme4_health_demographics/`](theme4_health_demographics/))

* **[`CA_Health_Spending_CIHI.csv`](theme4_health_demographics/CA_Health_Spending_CIHI.csv)** — Annual provincial and territorial long-term care (nursing/residential and home/community care) and total health expenditure by financing sector. **Source:** [CIHI National Health Expenditure Trends (NHEX)](https://www.cihi.ca/en/national-health-expenditure-trends)
* **[`CA_Population_Estimates.csv`](theme4_health_demographics/CA_Population_Estimates.csv)** — Annual July 1 population estimates by province/territory and age bracket (`2000–2025`, also used as a per-capita denominator across Themes 1–4). **Source:** [Statistics Canada Table `17-10-0005-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1710000501)
* **[`CA_CPI_Inflation_Monthly.csv`](theme4_health_demographics/CA_CPI_Inflation_Monthly.csv)** — Monthly Canadian Consumer Price Index and Bank of Canada core inflation measures (also used to deflate nominal dollar series across Themes 1–4). **Source:** [Bank of Canada CPI Portal](https://www.bankofcanada.ca/rates/price-indexes/cpi/) | [Statistics Canada Table `18-10-0004-01`](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000401)

---

## Theme 5: Comparative Conflict, Security, Alliances & Trade Disputes ([`theme5_conflict_security_trade/`](theme5_conflict_security_trade/))

* **[`AllianceSystems.csv`](theme5_conflict_security_trade/AllianceSystems.csv)** — Interstate military alliance-year panel tracking the share of democratic members and offensive/defensive pact commitments. **Source:** [Chiba, Johnson & Leeds (2015) PDF](theme5_conflict_security_trade/Chiba_et_al_2015_AllianceSystems.pdf) ([DOI](https://doi.org/10.1086/682074))
* **[`BombingVietnam.csv`](theme5_conflict_security_trade/BombingVietnam.csv)** — Province-level US ordnance volumes by munition type, historical population density, geography, and subsequent poverty outcomes in Vietnam. **Source:** [Miguel & Roland (2005/2011) PDF](theme5_conflict_security_trade/Miguel_Roland_2005_BombingVietnam.pdf) ([DOI](https://doi.org/10.1016/j.jdeveco.2010.07.004))
* **[`ClimateConflict.csv`](theme5_conflict_security_trade/ClimateConflict.csv)** — Sub-Saharan African country-year panel of armed conflict onset, temperature, precipitation, GDP, and Polity regime scores. **Source:** [Burke et al. (2009) PDF](theme5_conflict_security_trade/Burke_et_al_2009_ClimateConflict.pdf) ([DOI](https://doi.org/10.1073/pnas.0907998106))
* **[`UNSC.csv`](theme5_conflict_security_trade/UNSC.csv)** — Cross-national dataset of bilateral trade with the five permanent UN Security Council members, GDP per capita, civil war, self-determination factions, and democracy. **Source:** [White, Cunningham & Beardsley (2018) PDF](theme5_conflict_security_trade/White_et_al_2018_UNSC.pdf) ([DOI](https://doi.org/10.1177/0022343317744826))
* **[`WTO.csv`](theme5_conflict_security_trade/WTO.csv)** — Country-year panel of WTO trade dispute involvement, logged total imports, and Polity regime scores. **Source:** [Chaudoin, Kucik & Pelc (2016) PDF](theme5_conflict_security_trade/Chaudoin_et_al_2016_WTO.pdf) ([DOI](https://doi.org/10.1093/isq/sqw009))

---

## Theme 6: Comparative Development, Gender, Public Health & Governance ([`theme6_development_gender_governance/`](theme6_development_gender_governance/))

* **[`DisastersGender.csv`](theme6_development_gender_governance/DisastersGender.csv)** — Cross-national dataset of natural disaster fatalities, female-to-male life expectancy ratios, women's socioeconomic rights, GDP per capita, political stability, and freedom levels. **Source:** [Neumayer & Plümper (2007) PDF](theme6_development_gender_governance/Neumayer_Plumper_2007_DisastersGender.pdf) ([DOI](https://doi.org/10.1111/j.1467-8306.2007.00563.x))
* **[`ElectoralDiffusion.csv`](theme6_development_gender_governance/ElectoralDiffusion.csv)** — European country-election year panel of parliamentary and federal institutional arrangements and majority party vote shares. **Source:** [Bol, Pilet & Riera (2015) PDF](theme6_development_gender_governance/Bol_et_al_2015_ElectoralDiffusion.pdf) ([DOI](https://doi.org/10.1111/1475-6765.12091))
* **[`OilCooperation.csv`](theme6_development_gender_governance/OilCooperation.csv)** — Cross-national dataset of per-capita coal and resource income, GDP per capita, and economic, political, and social globalization indices. **Source:** [Ross & Voeten (2015) PDF](theme6_development_gender_governance/Ross_Voeten_2015_OilCooperation.pdf) ([DOI](https://doi.org/10.1093/isq/sqv003))
* **[`ProstitutionTrafficking.csv`](theme6_development_gender_governance/ProstitutionTrafficking.csv)** — Cross-national dataset of prostitution legality, human trafficking inflow ratings, migrant stock, GDP per capita, democracy, and Catholic population share. **Source:** [Cho, Dreher & Neumayer (2013) PDF](theme6_development_gender_governance/Cho_et_al_2013_ProstitutionTrafficking.pdf) ([DOI](https://doi.org/10.1016/j.worlddev.2012.05.023))
* **[`Smoking.csv`](theme6_development_gender_governance/Smoking.csv)** — Cross-national dataset of per-capita cigarette consumption, tobacco production, GDP per capita, urban population share, life expectancy, health spending share of government expenditure, and rule of law. **Source:** [Perkins & Neumayer (2014) PDF](theme6_development_gender_governance/Perkins_Neumayer_2014_Smoking.pdf) ([DOI](https://doi.org/10.1007/s00038-014-0585-3))

---

## Companion Lookup & Join Bridges ([`advanced_joins/`](advanced_joins/))

* **[`Country_Concordance_Crosswalk.csv`](advanced_joins/Country_Concordance_Crosswalk.csv)** — Concordance mapping raw country name spellings across the comparative datasets to ISO-3 codes (`OilCooperation.csv`) and canonical country names. **Source:** [ISO 3166-1 Alpha-3 Standard](https://www.iso.org/iso-3166-country-codes.html)
* **[`Country_Macro_Regime_Comparison.csv`](advanced_joins/Country_Macro_Regime_Comparison.csv)** — Cross-national comparison table aligning GDP per capita, democracy, freedom, political stability, rule of law, and OECD indicators across the comparative datasets. **Source:** Comparative Politics Source Studies (Themes 5–6)
* **[`Vietnam_Province_Lookup.csv`](advanced_joins/Vietnam_Province_Lookup.csv)** — Lookup table mapping numeric `province` codes in `BombingVietnam.csv` to Vietnamese province names, statistical regions, and North/South zones. **Source:** [Miguel & Roland (2005/2011) PDF](theme5_conflict_security_trade/Miguel_Roland_2005_BombingVietnam.pdf)
* **[`BombingVietnam_Ordnance_USDoD.csv`](advanced_joins/BombingVietnam_Ordnance_USDoD.csv)** & **[`BombingVietnam_VLSS_Survey.csv`](advanced_joins/BombingVietnam_VLSS_Survey.csv)** — Two-table split of `BombingVietnam.csv` separating historical US ordnance records from post-war survey outcomes. **Source:** [Miguel & Roland (2005/2011) PDF](theme5_conflict_security_trade/Miguel_Roland_2005_BombingVietnam.pdf)
