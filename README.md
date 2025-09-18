# CS-GO-Analysis
  A data-driven project analyzing Counter-Strike: Global Offensive (CS:GO) datasets.
Explore player performance, match outcomes, weapon usage, and other game statistics through Python-based data science techniques.
✨ Features
📊 Exploratory Data Analysis (EDA) of CS:GO matches
🎯 Player performance breakdowns (kills, deaths, assists, K/D ratio)
🔫 Weapon usage and efficiency insights
🌍 Map-wise win/loss trends
📈 Visualizations with Matplotlib & Seaborn
🧠 Data preprocessing for further ML/AI applications
🧱 Tech Stack
•	Language: Python 3.x
•	Libraries: NumPy, Pandas, Matplotlib, Seaborn
•	Notebook: Jupyter (.ipynb)
•	Dataset: CSV format (csgo (1).csv)
📁 Project Structure
csgo-analysis/
├─ Untitled19.ipynb       # Jupyter Notebook with analysis code
├─ csgo (1).csv           # Dataset (matches, stats)
├─ requirements.txt       # Python dependencies
└─ README.md
📊 Dataset
Expected columns (varies by source but typically includes):
•	match_id (int)
•	map (string)
•	round (int)
•	player (string)
•	team (string)
•	kills (int)
•	deaths (int)
•	assists (int)
•	weapon (string)
•	outcome (win/lose)
Dataset: csgo (1).csv (sourced from Kaggle or similar platforms).
🚀 Quick Start (Local)
Clone & enter
git clone https://github.com/<your-username>/csgo-analysis.git
cd csgo-analysis
Python env & install
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
Run the notebook
jupyter notebook Untitled19.ipynb
📦 requirements.txt (minimal)
numpy
pandas
matplotlib
seaborn
jupyter
🤝 Contributing
•	Fork the repo
•	Create a feature branch: git checkout -b feat/something
•	Commit changes: git commit -m "feat: add X"
•	Push: git push origin feat/something
•	Open a PR
📄 License
MIT © [LOGESHKUMAR P]

