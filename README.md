🏎️ F1 2025 Race Predictor
by Mythri Shivakumar

🚀 Overview
A Python script that predicts the 2025 Chinese Grand Prix race grid using Australian GP 2025 results and China Sprint Qualifying times. Powered by fastf1 for real F1 data and a Random Forest model for the heavy lifting. Outputs are clean table.

🏁 Features
✔ Aus 2025 Blind Prediction – Predicts the grid using 2024 averages, team strength & experience.
✔ Aus 2025 Actual Results – Pulls real results from fastf1, compares them (wet race chaos included).
✔ China 2025 Race Prediction – Blends 20% of Aus results with 80% of Sprint Quali ranks for final predictions.
✔ Clean Output – Structured tables with tabulate—just the facts, no fluff.
✔ Scalable – Ready for Practice & Quali data when available.

🛠️ Setup
1️⃣ Clone the repo
https://github.com/MythriShivakumar/F1_Race_Prediction.git
2️⃣ Install dependencies
pip install fastf1 tabulate pandas numpy scikit-learn
3️⃣ Run the notebook 

📌 Notes
Requires an active internet connection for fastf1 data retrieval.
Predictions improve with more race data—stay tuned for updates!
