🌍 Tourism Data Analytics (Portfolio Project)


End-to-end analytics project showcasing data wrangling (Python/Pandas), SQL analytics (SQLite), and visualization (Matplotlib & Tableau).

The dataset simulates monthly tourism flows for Calgary, Banff, and Jasper (2023–2024), including origin countries, segments, booking channels, revenue, and satisfaction scores.

✨ Key Features

🗂 Synthetic Dataset (Calgary, Banff, Jasper; 2023–2024)

⚙️ ETL Pipeline with Python (Pandas) for data cleaning & transformation

🗄 SQLite Database + SQL Queries for reproducible KPIs

📊 Charts (Matplotlib) → visitors & revenue trends, segment mix, city revenue

📈 Tableau Dashboards (optional) for interactive insights

tourism-data-analytics-portfolio/
├─ data/         # datasets + SQLite DB
├─ docs/         # detailed report with visuals
├─ outputs/      # generated CSVs & charts
├─ scripts/      # helper scripts (batch/shell)
├─ sql/          # SQL queries
├─ src/          # Python source code
├─ tableau/      # Tableau dashboards/screenshots
├─ LICENSE
├─ Makefile
├─ README.md
└─ requirements.txt


⚡ Quick Start

Clone the repo and run the analysis:

# 1. Create virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run analysis (generate CSVs + charts)
python src/run_analysis.py

# 4. Build SQLite database + export SQL KPIs
python src/build_db.py


Outputs are saved to /outputs:

📊 visitors_over_time.png

💰 revenue_over_time.png

🏙 revenue_by_city.png

👥 segment_mix.png

plus KPI CSVs

📊 Example Visuals




📑 Documentation

Detailed Report
 — includes insights, charts, and methodology

SQL Queries
 — reproducible KPI calculations

Outputs Catalog
 — snapshot of generated results

🌐 Tableau Dashboard

👉 Add Tableau Public Link Here

🛠 Tech Stack

Python: Pandas, Matplotlib

SQL: SQLite

Visualization: Tableau (optional)

Automation: Makefile + scripts

📜 License

MIT — feel free to use and adapt.