<!-- Profile Header -->
<h1 align="center"> Zechong (Paul) Wang </h1>
<p align="center">
  <strong>
    Econ Research & ML · RA on CMF Microdata · Python · Stata · AWS <br/>
    UChicago MACSS Econ '26 | NYU Math + Econ '24
  </strong>
  <br/><br/>
  <strong>
    Just like on the tennis court 🎾, I get a thrill from chasing down every stray ball <br/>
    and turning it into a winning shot. I love building research-grade pipelines that make results <br/>
    reproducible, auditable, and useful for decision-makers — because in both tennis and research, <br/>
    consistency is how you win the match.
  </strong>
</p>

<p align="center">
  <a href="https://github.com/PaulWang-Uchicago"><img src="https://img.shields.io/badge/GitHub-PaulWang--Uchicago-black?logo=github" /></a>
  <a href="https://www.linkedin.com/in/wang1023/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin" /></a>
 <a href="mailto:zw2685@uchicago.edu">
  <img src="https://img.shields.io/badge/Email-Contact-blue?logo=microsoftoutlook&logoColor=white" />
</a>
</p>

---

### Selected Projects

## Emerald Heatwaves and Concrete Crimes: Greenness-Cooling Synergies in Toronto, 2014-2024
[View Repository →](https://github.com/PaulWang-Uchicago/Coding-Sample/tree/main/Large-Scale%20Computing%20Project)
Leveraging a large-scale fusion of 411,996 geocoded crime incidents, 158 GB of Landsat-8/9 imagery, 489,328 aggregated hourly foot-traffic records, and 3,432 school-point records, I develop a novel, hex-cell–based analytical framework to quantify how urban greening (NDVI) and surface cooling (LST) jointly influence crime patterns in Toronto from 2014 to 2024. By fusing these layers in a distributed geospatial pipeline (Dask and Rasterio‑Dask), I discover a non‑linear, zone‑specific greenness–cooling synergy. Robust statistical models that incorporate hex and month fixed effects and HC3 heteroskedasticity-consistent standard errors confirm that the triple-interaction term (High-school × NDVI × LST) yields a −0.321 SD effect, equating to a 12 % reduction in monthly crime in school corridors. The project demonstrates how large-scale computation can turn environmental amenities into actionable safety policy.

## FOMC Sentiment & Manufacturing New Orders
[View Repository →](https://github.com/PaulWang-Uchicago/Coding-Sample/tree/main/FOMC%20Project)
This project investigates whether the tone of Federal Open Market Committee (FOMC) communications can improve forecasts of monthly U.S. manufacturing new orders. I construct two dictionary-based sentiment indices from FOMC minutes and statements using a curated economic vocabulary and explore their predictive value alongside traditional macroeconomic indicators (e.g., PPI, oil prices, CPI, unemployment). Finding that sentiment scores alone explain little variance in the target, I develop a multi-stage unsupervised pipeline, including TF–IDF clustering, BERTopic, FinBERT tone detection, and PCA, to extract latent textual features from Fed communications. I integrate these with macro series and autoregressive lags into a Random Forest model that achieves high out-of-sample performance (R² = 0.9835, RMSE = 0.042). Despite the rich text-mining framework, results show that realized fundamentals, especially cost pressures and order momentum, remain the dominant drivers of manufacturing behavior, while FOMC tone contributes only marginally. This suggests that while central-bank rhetoric shapes expectations, it exerts limited influence on high-frequency production planning. I conclude that sentiment features may be more useful for structural regime classification than for real-time forecasting of industrial outcomes.

---
### Computational Macroeconomics -- Coding sample
[View Repository →](https://github.com/PaulWang-Uchicago/Coding-Sample/tree/main/Economic%20Modeling) This repository highlights my ability to formulate and solve dynamic macroeconomic models using a variety of numerical techniques. The files demonstrate how I approach stochastic growth, consumption–savings, and money-in-utility models with different solution strategies, ranging from basic root-finding to advanced projection methods.

---
### CMF Data Corrections & Anomaly Detection -- Coding sample
[View Repository →](https://github.com/PaulWang-Uchicago/Coding-Sample/tree/main/cmf_data_corrections) This repository showcases part of my Research Assistant work for Professor Richard Hornbeck on the Census of Manufactures (CMF) microdata project at the University of Chicago.  
It contains Jupyter notebooks and Python scripts I developed to improve the quality of digitized historical manufacturing census records (1850–1880).  
The files fall into two main categories:

- **Finder tools**: Notebooks that systematically detect anomalies, inconsistencies, and transcription errors in establishment-level CMF datasets (1860–1880), including both general schedules and supplemental schedules. These tools highlight outliers, missing values, and cross-variable inconsistencies for review.  
- **Correction tools**: Notebooks and scripts that apply targeted fixes to identified issues across years and schedules. These include transcription corrections, variable standardization, and rule-based adjustments to ensure consistent, high-quality data across cleaned CMF datasets.  

---
### Trie Search Crawler
[View Repository →](https://github.com/PaulWang-Uchicago/Coding-Sample/tree/main/trie_search) This repository contains the core implementation of a lightweight search engine built on top of a Trie data structure.

