🎬 IMDB MOVIE ANALYSIS
Data Science Project for Movie Producers

👨‍💻 Author: Sparsh Narayan
🆔 Unique ID: 2472177
🎓 Student ID: 24CE-75

📊 Overview

This project performs a complete data analysis on an IMDB dataset containing 3000+ movies, providing actionable insights for movie producers using Data Science.

It answers key business questions related to profitability, ROI, actors, directors, and production companies.

🚀 Key Features

✅ One-click analysis using a single Python script
✅ Handles complex JSON-like IMDB data
✅ Automatic Profit & ROI calculations
✅ Robust error handling using ast.literal_eval
✅ Clean and professional output formatting
✅ Fully optimized for Google Colab & local execution

📈 Business Questions Answered
🎥 Which movie generated the highest profit?
🌍 Which language gives the best ROI?
🏆 Who are the top producers by performance?
👨‍🎤 Which actor appears most frequently?
🎬 Which directors consistently deliver results?
🤝 Which actors are frequently preferred by top directors?
📊 Sample Output
🎥 HIGHEST PROFIT MOVIE
Title: Avatar  
Profit: $2,789,900,000  
Producers: Lightstorm Entertainment  
Director: James Cameron  
Actors: Sam Worthington, Zoe Saldana  

🌍 BEST LANGUAGE: English (ROI: 345%)  
🏆 TOP PRODUCERS: Warner Bros, Universal, Disney  
👨‍🎤 TOP ACTOR: Samuel L. Jackson (23 movies)
⚙️ Tech Stack
pandas → Data manipulation
numpy → Numerical computations
ast → Safe parsing of JSON-like data
collections.Counter → Frequency analysis
📁 Project Structure
imdb-movie-analysis/
│
├── movie_analysis.py        # Main analysis script
├── imdb_data (1).csv       # Dataset (3000+ movies)
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
🚀 Quick Start
🔹 Google Colab (Recommended - 2 mins)
Open: https://colab.research.google.com
Upload imdb_data (1).csv
Copy-paste the script
Run → Get insights instantly
🔹 Local Setup
git clone https://github.com/YOUR_USERNAME/imdb-movie-analysis.git
cd imdb-movie-analysis
pip install -r requirements.txt
python movie_analysis.py
🧪 How to Run (Colab)
from google.colab import files
files.upload()  # Upload dataset

%run movie_analysis.py
📊 Key Metrics Calculated
Metric	Formula	Business Value
Profit	revenue - budget	Absolute success
ROI	(revenue - budget) / budget	Investment efficiency
Avg ROI (Language)	GroupBy	Market targeting
Actor Frequency	Count appearances	Star power
Director-Actor Mapping	Pattern analysis	Collaboration insights
🔍 Dataset Structure
budget, revenue → Profit & ROI
genres → Multi-genre analysis
production_companies → Producers
cast → Actors
crew → Directors (job = Director)
original_language → Language performance
🎯 Use Cases

✔ Movie Production Strategy
✔ Investment Decision Making
✔ Actor/Director Selection
✔ Market & Language Targeting

📄 License

MIT License – Free for personal and commercial use 🎥

❤️ Acknowledgment

Made with passion for data-driven filmmaking
📅 March 2026
