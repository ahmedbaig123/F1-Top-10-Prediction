Problem Statement:
This project predicts whether a Formula 1 driver will finish in the Top 10 using historical race data.

📊 Dataset

Formula 1 World Championship (1950 - 2024)

🔍 Exploratory Data Analysis

Grid position shows strong monotonic relationship with Top 10 probability.

Constructor strength significantly influences outcome.

Driver performance is correlated with constructor strength.

⚙️ Features Used

Grid position

Constructor historical Top 10 rate

🤖 Models

Logistic Regression

Random Forest

📈 Best Result

Logistic Regression Accuracy: ~68%

🧠 Key Insight

Qualifying position (grid) is the strongest predictor of race outcome.

⚠️ Limitations

Historical leakage (full-career statistics used)

No time-aware split

No weather or DNF data
