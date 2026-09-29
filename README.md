# Awesome-Consumer-Packaged-Goods-Planning

## Top Consumer Packaged Goods (CPG) Planning Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Demand Planning, Supply Planning, S&OP/IBP, Replenishment, Inventory Optimization & Retail/CPG Forecasting*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Consumer Packaged Goods (CPG) Planning**. These systems support demand forecasting, supply and replenishment planning, sales & operations planning (S&OP), integrated business planning (IBP), and inventory optimization for CPG and retail supply chains.



**Examples** include o9 Solutions, Blue Yonder, RELEX Solutions, Anaplan, Board, ToolsGroup, Kinaxis, OMP Plus, Logility, and Infor Demand Management (the category leaders).



**Open-source emphasis**: Enterprise CPG planning and S&OP platforms are almost entirely commercial. Open options are limited to forecasting libraries, experimental S&OP prototypes, and optimization solvers. This section expands those building blocks while remaining realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[o9 Solutions](https://o9solutions.com/)**  

  AI-driven digital brain platform for enterprise demand, supply, and integrated business planning across CPG and complex supply chains.



- **[Blue Yonder](https://blueyonder.com/)**  

  Cloud supply chain planning suite covering demand, supply, inventory, and retail/CPG operations with AI-assisted decisioning.



- **[RELEX Solutions](https://www.relexsolutions.com/)**  

  Unified retail and CPG planning platform strong on demand forecasting, replenishment, and store-level optimization.



- **[Anaplan](https://www.anaplan.com/)**  

  Connected planning platform widely used for demand, supply, and S&OP/IBP processes in CPG and retail.



- **[Board](https://www.board.com/)**  

  Business planning and performance management platform with supply chain and demand planning capabilities.



- **[ToolsGroup](https://www.toolsgroup.com/)**  

  Demand forecasting and inventory optimization software focused on service-level-driven planning for CPG and distribution.



- **[Kinaxis](https://www.kinaxis.com/)**  

  Concurrent planning platform (RapidResponse) for end-to-end supply chain planning, what-if scenarios, and S&OP.



- **[OMP Plus](https://omp.com/)**  

  Advanced planning and scheduling / supply chain planning solutions used in process and CPG industries.



- **[Logility](https://www.logility.com/)**  

  Supply chain planning platform covering demand, inventory, and replenishment for manufacturers and CPG companies.



- **[Infor Demand Management](https://www.infor.com/)**  

  Demand planning and forecasting capabilities within Infor’s supply chain and ERP portfolio for CPG and manufacturing.



## Open-Source GitHub Projects

- **[Prophet](https://github.com/facebook/prophet)**  

  Open-source forecasting library (Meta) widely used for demand time series with seasonality, holidays, and trend—common in CPG prototypes.



- **[OpenForecast packages (smooth, greybox, etc.)](https://github.com/openforecast-org)**  

  Open-source R and Python forecasting toolkits implementing exponential smoothing, intermittent demand, and evaluation methods.



- **[statsmodels / scikit-learn / neural forecasting stacks](https://github.com/statsmodels/statsmodels)**  

  Core open statistical and ML libraries used to build custom demand forecasting pipelines for CPG SKUs.



- **[Experimental S&OP / demand planning apps](https://github.com/)**  

  Community prototypes combining demand forecasting, MRP-style netting, capacity scenarios, and simple executive views.



- **[OR-Tools / open optimization solvers](https://github.com/google/or-tools)**  

  Open optimization libraries used for inventory, replenishment, and constrained supply planning experiments.



- **[Time-series feature and intermittent demand open tools](https://github.com/)**  

  Packages for classifying demand patterns (smooth vs intermittent) and generating lag/seasonality features for CPG data.



- **[Inventory policy open calculators](https://github.com/)**  

  Scripts for safety stock, reorder points, and service-level-based order quantities driven by open forecasts.



- **[Apache Airflow / orchestration for planning pipelines](https://github.com/apache/airflow)**  

  Open workflow orchestration used to schedule forecast refresh, data prep, and planning model runs.



- **[dbt and open analytics for demand data prep](https://github.com/dbt-labs/dbt-core)**  

  Open transformation tools commonly used to prepare clean demand history and hierarchical signals for planning models.



- **[Documentation and open forecasting playbooks](https://facebook.github.io/prophet/)**  

  Guides for building transparent demand forecasts and linking them to basic inventory decisions.



### Additional Strong Open-Source Options

- Building demand forecasts with **Prophet**, **smooth**, or classical/ML ensembles on historical shipments and orders.

- Using open optimization solvers for simple replenishment and allocation experiments.

- Prototyping S&OP-style scenario comparison in lightweight web or notebook apps.

- Accepting that multi-echelon inventory optimization, consensus S&OP workflows, hierarchical forecasting at scale, retailer collaboration, and enterprise what-if concurrency still require commercial platforms (o9, Blue Yonder, RELEX, Kinaxis, Anaplan, ToolsGroup, etc.).

- Focusing open-source efforts on transparent models, research, and reducing black-box dependence in the forecasting layer.



**Frameworks for building custom systems**: Clean demand history (dbt) → forecast with open libraries → compute safety stock/ROP → optionally optimize with OR-Tools → present scenarios in notebooks or a simple UI. Suitable for analytics teams and mid-size CPG experiments. Large CPG and retail planning organizations almost always run commercial planning platforms for production S&OP/IBP.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Planning systems influence inventory, service levels, and financial outcomes. Open-source tools are not substitutes for validated commercial planning platforms in production CPG environments. This list is not supply-chain or financial advice.



---

**Made for demand planners, supply chain analysts, and open forecasting advocates.**

Let's keep planning decisions data-driven, transparent, and as open as practical.
