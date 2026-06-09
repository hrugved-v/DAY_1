Created a project folder structure: data/raw, data/processed, notebooks/, sql/, dashboard/, reports/. Initialise Git repo and push to GitHub.
Installed all dependencies: pandas, numpy, matplotlib, seaborn, plotly, sqlalchemy, requests, scipy, jupyter. Create requirements.txt.
Loaded all 10 provided CSV datasets using Pandas. Print .shape, .dtypes, and .head() for each. Note any anomalies.
Fetched live NAV from mfapi.in: GET https://api.mfapi.in/mf/125497 (HDFC Top 100 Direct). Parse JSON response and save as raw CSV.
Fetched NAV for 5 key schemes: SBI Bluechip (119551), ICICI Bluechip (120503), Nippon Large Cap (118632), Axis Bluechip (119092), Kotak Bluechip (120841).
Explored fund master — print unique fund houses, categories, sub-categories, risk grades. Understand AMFI scheme code structure.
Validated AMFI codes — confirm every code in fund_master exists in nav_history. Write a short data quality summary.
Git commited: "Day 1: Data ingestion complete"
Deliverables: data_ingestion.py, live_nav_fetch.py, requirements.txt, GitHub repo with Day 1 commit
