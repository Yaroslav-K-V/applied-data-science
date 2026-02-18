# Applied Data Science

Exploratory data analysis exercises using Python, pandas, and seaborn.

## Notebook

**DSL.ipynb** — three dataset analyses in a single notebook:

### London Houses
- Source: [London Real Estate and Housing Market Dataset (Kaggle)](https://www.kaggle.com/datasets/abubakerasiel/london-real-estate-and-housing-market-dataset/data)
- 1,000 properties across 10 neighborhoods
- Price per m², price per room, neighborhood rankings, housing stock valuation
- Kensington vs Chelsea deep-dive, price segment comparison (budget/mid/premium)

### Retail Business
- Source: [Retail Business Analytics Dataset 10K Orders (Kaggle)](https://www.kaggle.com/datasets/amar5693/retail-business-analytics-dataset-10k-orders)
- 10,000 orders across 5 categories, 4 regions, 3 customer segments (Jan–Dec 2024)
- Revenue, profit margins, ROI ratio, per-unit metrics
- Top customers, regional heatmaps, time series trends, payment distribution

### Computer Science Students
- Source: [Computer Science Students Performance (Kaggle)](https://www.kaggle.com/datasets/nalisha/computer-science-students-performance)
- 180 students across 27 interested domains
- GPA distribution by gender, programming skills (Python, SQL, Java) vs GPA
- Domain → career pathway heatmap, skill profile combinations, student profile by domain

> All datasets are synthetic — the analyses serve as a technical exercise.

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate
pip install pandas numpy matplotlib seaborn ipykernel
```

## Author

[Yaroslav-K-V](https://github.com/Yaroslav-K-V)
