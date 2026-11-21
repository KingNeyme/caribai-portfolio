# 🍽️ Spice & Sea Restaurant: *"Why are margins slipping?"*

![Track](https://img.shields.io/badge/track-Data%20Analytics-1f6feb)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

← [Back to the portfolio](../README.md)

---

## The problem

**Spice & Sea** is a 60-seat restaurant in Castries, Saint Lucia, serving lunch and dinner
to a mix of locals, tourists and cruise ship visitors. The owner came with this:

> *"We're busier than ever but at the end of the month there's less money left.
> I don't know if it's food costs, staff, the menu, or the slow season.
> I need to know what's actually going on and what I should change."*

It's a vague, real-world request that mixes several questions together. The job is to
turn it into questions data can answer, answer them with evidence, and give the owner
something she can act on. [Read the full brief →](BRIEF.md)

## The data

Two years (Jan 2024 – Dec 2025) of exports from the restaurant's systems, as handed over by the client:

| File | Contents | Rows |
|---|---|--:|
| `pos_export_2024.csv` | every item sold, old POS system | ~91,000 |
| `pos_export_2025.csv` | every item sold, new POS system | ~102,000 |
| `staff_shifts.csv` | clock-ins and clock-outs | ~15,800 |
| `supplier_invoices.csv` | deliveries from four suppliers (EC$ and US$) | ~3,900 |
| `menu.csv` | menu items with price history | 42 |
| `plate_costs.csv` | head chef's monthly cost per plate | 624 |
| `cruise_calendar.csv` | cruise ship calls at Port Castries | ~380 |

The data is **deliberately messy**, like real exports: two date formats, inconsistent item
names, mixed currencies, voids and refunds, duplicates and gaps. Part of the work is finding
and documenting all of it before trusting a single number.

*All data is synthetic, generated to realistically mirror a Caribbean restaurant's operations.*

## Questions

1. Is revenue actually growing? Month over month, year over year?
2. What's happening to food cost as a % of revenue, and which items drive it?
3. Is labour cost tracking demand, or are we overstaffed on slow days?
4. Which menu items earn the most **profit**, not just the most sales?
5. How big are the seasonal swings (Carnival, Jounen Kwéyòl, cruise days, Christmas, Aug–Sep)?

## Deliverables

- [ ] **Data inventory & issues log:** every problem in the raw data, documented
- [ ] **Cleaned dataset:** with every cleaning decision recorded
- [ ] **Analysis notebook:** answers each question, runs top to bottom
- [ ] **One-page memo to the owner:** what's happening, how sure we are, what to do
- [ ] **Live Streamlit dashboard:** the weekly numbers that matter
- [ ] **Published:** Kaggle dataset + notebook, case study on [caribailabs.com](https://caribailabs.com)

## Key findings

*Analysis in progress. The headline findings, charts and recommendations will be
summarised here.*

## Structure

```
project-01-spice-and-sea/
├── README.md            ← this page
├── BRIEF.md             ← the client's request
├── DATA_INVENTORY.md    ← what's in the data and every quality issue found
├── environment.yml      ← conda environment (spice-sea)
├── data/
│   └── raw/             ← original exports, never edited
└── notebooks/
    └── 01_data_profiling.ipynb
```

## Run it

```bash
conda env create -f environment.yml
conda activate spice-sea
jupyter lab
```

Open `notebooks/` and run the notebooks in order.
