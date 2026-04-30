#  IPL Data Pipeline & Analysis (Pandas Project)

##  Overview

This project builds a complete **data analysis pipeline** on IPL (Indian Premier League) datasets using **Python (Pandas)**.

It simulates a real-world workflow:

**Ingest → Clean → Transform → Analyze → Report → Export**

---

##  Dataset

We use two datasets:

* `deliveries.csv` → Ball-by-ball data
* `matches.csv` → Match-level metadata

📎 Source: Kaggle IPL Dataset (2008–2020)

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib (optional)
* Jupyter Notebook (VS Code)

---

##  Project Structure

```
IPL_Pipeline/
│
├── data/
│   ├── deliveries.csv
│   └── matches.csv
│
├── output/
│   ├── runs_per_match.csv
│   ├── top_batters.csv
│   ├── strike_rate.csv
│   ├── economy.csv
│   ├── team_scores.csv
│   ├── death_overs.csv
│   └── ipl_analysis.xlsx
│
├── analysis.ipynb
└── README.md
```

---

##  Pipeline Stages

###  Stage 1: Data Ingestion

* Loaded datasets using Pandas
* Inspected shape, columns, and data types

---

###  Stage 2: Data Cleaning & Validation

* Handled missing values
* Fixed data types
* Validated match IDs between datasets

---

###  Stage 3: Data Transformation

* Created derived columns
* Standardized column names
* Merged datasets into a unified DataFrame

---

###  Stage 4: Core Analysis

####  Key Use Cases:

1. Total Runs per Match
2. Runs per Team per Match
3. Top 10 Batters
4. Strike Rate of Batters
5. Top Bowlers by Economy
6. Most Consistent Batters
7. Highest Individual Score
8. Boundary Analysis
9. Boundary Percentage
10. Dot Ball Analysis
11. Runs per Over Analysis
12. Powerplay Performance
13. Death Overs Performance
14. Run Distribution (1st vs 2nd Innings)
15. Toss Impact Analysis
16. Player of Match Contribution
17. Venue-wise Analysis
18. City-wise Analysis
19. Season-wise Trends
20. Winning Team Analysis

---

###  Stage 5: Derived Insights

* Identified key performers
* Compared match phases (powerplay, death overs)
* Analyzed venue and season trends

---

###  Stage 6: Reporting

* Cleaned and formatted DataFrames
* Structured outputs for readability

---

###  Stage 7: Data Export

* Exported results to CSV files
* Generated Excel summary file

---

##  Key Insights

* Death overs (16–20) have the highest scoring rates
* Certain venues (e.g., batting-friendly pitches) consistently produce high scores
* Toss impact is moderate (~50–55%)
* Some players dominate via boundaries, while others rely on consistency
* Strike rate is crucial in death overs, while average matters for consistency

---

##  How to Run

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd IPL_Pipeline
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib openpyxl
```

### 3. Run the notebook

Open `analysis.ipynb` in VS Code or Jupyter and run all cells.

---

##  Outputs

* CSV files in `/output` folder
* Excel file: `ipl_analysis.xlsx`

---

##  Project Outcome

This project demonstrates:

* End-to-end data pipeline design
* Data cleaning and transformation
* Multi-source data merging
* Efficient aggregation using Pandas
* Insight generation from real-world data

---

##  Author

**Akshat Walvekar**

---


