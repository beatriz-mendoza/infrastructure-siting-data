# Infrastructure Siting Data

**Public data analysis for community opposition risk in US infrastructure siting.**

This repository contains notebooks and analysis exploring the public data signals that drive community opposition to renewable energy and infrastructure development. All data used is publicly available — no proprietary sources.

Built by [Beatriz Mendoza](https://github.com/beatriz-mendoza), Co-Founder & CEO of [LANDMARQ](https://landmarq.io).

---

## Notebooks

| Notebook | Description | Data sources |
|----------|-------------|-------------|
| [01_county_opposition_patterns.ipynb](notebooks/01_county_opposition_patterns.ipynb) | Geographic clustering of infrastructure opposition across US counties | LBNL Wind Siting DB, EIA, HIFLD |
| [02_permitting_timelines.ipynb](notebooks/02_permitting_timelines.ipynb) | Permitting timeline analysis — what predicts delays? | EIA-860, state energy commission records |
| [03_nimby_signal_exploration.ipynb](notebooks/03_nimby_signal_exploration.ipynb) | Exploratory analysis of public signals correlated with opposition outcomes | Multiple public sources |

---

## Setup

```bash
git clone https://github.com/beatriz-mendoza/infrastructure-siting-data
cd infrastructure-siting-data
pip install -r requirements.txt
jupyter notebook
```

### Requirements
pandas>=2.0
geopandas>=0.14
matplotlib>=3.7
seaborn>=0.12
requests>=2.31
jupyter>=1.0
numpy>=1.24


---

## Data sources

All data is publicly available and downloaded directly in the notebooks:

- **EIA Form 860** — US power plant locations, capacity, and operating status
- **LBNL Wind & Solar Siting Databases** — project-level siting outcomes including approval/denial
- **HIFLD (Homeland Infrastructure Foundation-Level Data)** — grid infrastructure, substations
- **US Census Bureau** — county demographic and socioeconomic data
- **EPA EJSCREEN** — environmental justice screening tool, cumulative burden data

---

## Related

- [nimby-risk-research](https://github.com/beatriz-mendoza/nimby-risk-research) — academic evidence base
- [landmarq-methodology](https://github.com/beatriz-mendoza/landmarq-methodology) — scoring model documentation
- [LANDMARQ Platform](https://landmarq.io/platform-overview)

- 
