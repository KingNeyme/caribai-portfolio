<div align="center">

# CaribAI Portfolio

### Data, AI & machine learning, built by hand, through a Caribbean lens

End-to-end projects in **data analytics, data science, data engineering, machine learning,
AI engineering and research**, each solving a realistic problem for a Caribbean business.

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![pandas](https://img.shields.io/badge/pandas-3.x-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/JupyterLab-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Anaconda](https://img.shields.io/badge/conda-44A833?logo=anaconda&logoColor=white)](https://www.anaconda.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Status](https://img.shields.io/badge/status-actively%20building-brightgreen)](#projects)

[**Website**](https://caribailabs.com) · [**LinkedIn**](https://www.linkedin.com/in/nehemiah-monrose-049467325) · [**Roadmap**](ROADMAP.md) · [**Contact**](mailto:caribailabs@gmail.com)

</div>

---

## 👋 About

I'm **Nehemiah Monrose**, a self-taught data practitioner from **Saint Lucia** 🇱🇨 and the
founder of **[CaribAI Labs](https://caribailabs.com)**.

Most data tools, datasets and case studies aren't built with the Caribbean in mind. This
repository is my answer to that: a portfolio of projects grounded in Caribbean
realities. EC$ pricing, cruise ship days, Carnival and Jounen Kwéyòl, hurricane season,
import-dependent supply chains. Each one is built the way it would be for a real client.

**Every project is delivered the way it would be for a real client:** a brief, a documented
look at the data, reproducible analysis, clear recommendations, and a tool the client can
keep using.

---

## 📂 Projects

| # | Project | Focus | Skills | Status |
|:-:|---|---|---|:-:|
| 01 | [**Spice & Sea Restaurant:** *"Why are margins slipping?"*](project-01-spice-and-sea/) | Data Analytics | pandas · data cleaning · business metrics · Streamlit dashboard | 🟡 In progress |
| 02 | **Saint Lucia Tourism Arrivals** | Data Analytics | SQL · public data · visualisation | ⚪ Planned |
| 03 | **Restaurant Demand Forecasting** | Data Science | time series · seasonality | ⚪ Planned |
| 04 | **Did the Promotion Work?** | Data Science | experiments · hypothesis testing | ⚪ Planned |
| 05 | **Retail Analytics Pipeline** | Data Engineering | ETL · data modelling · data quality | ⚪ Planned |
| 06 | **Customer Churn Prediction** | Machine Learning | classification · scikit-learn | ⚪ Planned |
| 07 | **Hotel Price & Demand Model** | Machine Learning | regression · feature engineering | ⚪ Planned |
| 08 | **"Ask the Caribbean Data" Assistant** | AI Engineering | LLMs · RAG · vector search | ⚪ Planned |
| 09 | **Evaluating an AI Assistant** | Research & Evaluation | evaluation design · metrics | ⚪ Planned |
| 10 | **Capstone: Client Engagement** | All tracks | end-to-end delivery | ⚪ Planned |

➡️ What each focus area covers and what's coming next: **[ROADMAP.md](ROADMAP.md)**.

---

## ⭐ Featured: Spice & Sea Restaurant

> *"We're busier than ever but at the end of the month there's less money left."*
> Marcia, owner of Spice & Sea, Castries, Saint Lucia

Two years of messy restaurant data, about **193,000 sales lines** from two different POS
systems, plus staff shifts, supplier invoices (some in US$), the chef's plate costing sheet,
and the Port Castries cruise schedule. The goal: find out *why* margins are slipping and
give the owner a dashboard she can use every week.

**Deliverables:** cleaned dataset · analysis notebook · one-page memo to the owner ·
live Streamlit dashboard

[**→ View the project**](project-01-spice-and-sea/)

---

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| Language | Python 3.12 |
| Analysis | pandas, NumPy, Jupyter |
| Visualisation | matplotlib, Plotly, Streamlit |
| Databases *(coming)* | SQLite, PostgreSQL |
| Machine learning *(coming)* | scikit-learn |
| AI engineering *(coming)* | LLM APIs, embeddings, vector search |
| Workflow | conda, git, GitHub, Kaggle |

---

## 🗂️ Repository structure

```
caribai-portfolio/
├── README.md                    ← you are here
├── ROADMAP.md                   ← focus areas and upcoming projects
└── project-01-spice-and-sea/
    ├── README.md                ← project overview and results
    ├── BRIEF.md                 ← the client's request and deliverables
    ├── data/raw/                ← original data, never edited
    └── notebooks/               ← analysis, in order (01_, 02_, ...)
```

Every project follows the same layout, so any of them can be picked up and re-run.

---

## ▶️ Run a project yourself

You need [Anaconda](https://www.anaconda.com/download) or Miniconda.

```bash
git clone https://github.com/KingNeyme/caribai-portfolio.git
cd caribai-portfolio
conda env create -f project-01-spice-and-sea/environment.yml
conda activate spice-sea
jupyter lab
```

Then open the project's `notebooks/` folder and run the notebooks in order.

---

## 📊 About the data

Client projects use **synthetic data**, generated to realistically mirror how a Caribbean
business operates (seasonality, pricing, suppliers, staffing), including the messiness of
real exports. No real customer or business data is used. Projects built on **public data**
(e.g. tourism statistics) cite their sources in the project README.

---

## 📫 Connect

I'm open to **freelance data work, roles, research collaborations**, and any initiative where
the Caribbean is part of the conversation.

- 🌐 **Website:** [caribailabs.com](https://caribailabs.com)
- 💼 **LinkedIn:** [Nehemiah Monrose](https://www.linkedin.com/in/nehemiah-monrose-049467325)
- ✉️ **Email:** [caribailabs@gmail.com](mailto:caribailabs@gmail.com)

<div align="center">

*Built in Saint Lucia* 🌴

</div>
