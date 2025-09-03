<!-- Profile Header -->
<h1 align="center"> Zechong (Paul) Wang </h1>
<p align="center">
  <strong>
    📊 Econ Research & ML · RA on CMF Microdata · Python · Stata · AWS <br/>
    🎓 UChicago MACSS Econ '26 | NYU Math + Econ '24
  </strong>
  <br/><br/>
  <strong>
    Just like on the tennis court 🎾, I get a thrill from chasing down every stray ball (or dataset) <br/>
    and turning it into a winning shot. I love building research-grade pipelines that make results <br/>
    reproducible, auditable, and useful for decision-makers — because in both tennis and research, <br/>
    consistency is how you win the match. 😎
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

### 🧠 Example Tooling / Workflow
```mermaid
flowchart LR
A[Raw Data] --> B[Cleaning & QC (pandas / tidyverse)]
B --> C[Feature Engineering]
C --> D[Modeling (sklearn / statsmodels)]
D --> E[Evaluation & Diagnostics]
E --> F[Visualization & Reporting]
F --> G[Decision / Deployment]
```
🚧 Replace or remove if not relevant; I can adapt to your actual workflow (e.g., causal diagram, experiment lifecycle).

---

### 🏅 Experience & Highlights
- 🚧 ROLE – ORG (Date Range): brief impact (e.g., Built XYZ model improving prediction accuracy by 14%).  
- 🚧 ROLE – ORG: (e.g., Designed A/B test reducing churn, implemented reproducible pipeline).  
- 🚧 Research / Lab / Assistantship: (methods, datasets, outcomes).  
- Awards / Scholarships: 🚧  
- Certifications: 🚧 (e.g., AWS Cloud Practitioner, Tableau, etc.)

(Provide details and I’ll turn them into strong impact bullets using action + method + result.)

---

### 🧩 Fun Facts

---
