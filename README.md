
📂 Repository Structure
powerbi-cricket-analysis/
├── data/                    # Raw cricket datasets (CSV/Excel/JSON)
│   └── matches_data.csv
├── powerbi/                 # Power BI-specific files and assets
│   ├── cricket_dashboard.pbix         # Main Power BI dashboard file
│   ├── visuals/                      # Exported PNG/SVGs of visuals
│   ├── measures.md                   # DAX measures used
│   └── queries/                      # Power Query M code snippets
├── reports/                 # Report exports and descriptions
│   ├── overview_report.pdf
│   └── player_performance.pdf
├── exports/                 # Optional: CSV exports from Power BI
│   ├── team_wins.csv
│   └── top_players.csv
├── documentation/          # Project documentation and notes
│   ├── README.md
│   └── analysis_plan.md
├── LICENSE
└── .gitignore

# 🏏 Power BI Cricket Analytics Dashboard

This repository hosts a Power BI-based analysis of cricket match data. The goal is to visualize trends, performance metrics, and match outcomes through an interactive dashboard.

---
## 📁 Structure

- `data/`: Contains cleaned datasets used in Power BI
- `powerbi/`: Main `.pbix` dashboard, DAX measures, Power Query scripts
- `reports/`: PDF reports exported from Power BI
- `exports/`: Data tables exported from Power BI visuals
- `documentation/`: Analysis plan and README

---

## 📊 Dashboard Highlights

Key features of the dashboard include:

- Team vs. Team Win Comparison
- Venue-wise Performance Analysis
- Toss Effect on Match Results
- Top Players (Batting & Bowling) by Performance
- Timeline-based Win Trends

> 📌 See the `.pbix` file in `/powerbi/` to open and explore the full interactive report.

---

## ⚙️ Requirements

- Power BI Desktop (latest version)
- Source Dataset: CSV files located in `/data/`

---

## 🚀 Getting Started

1. Download or clone the repo
2. Open `powerbi/cricket_dashboard.pbix` in Power BI Desktop
3. Make sure the data source path is updated if you move the dataset
4. Refresh the dataset to load the latest data

---

## 📄 Documentation

- See `documentation/analysis_plan.md` for analysis strategy
- DAX Measures used are documented in `powerbi/measures.md`
- Power Query M transformations can be found in `powerbi/queries/`

---

## 🤝 Contributing

Pull requests are welcome. For any major changes, please open an issue first to discuss improvements or feature requests.

---

## 📜 License

This project is licensed under the MIT License.

