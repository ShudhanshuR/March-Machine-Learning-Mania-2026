# March-Machine-Learning-Mania-2026 (KAGGLE)
KAGGLE - COMPETITION PROJECT 

🏀 March Machine Learning Mania 2026
!

# 📌 Project Overview
The NCAA March Madness is one of the most unpredictable and exciting sports events in the world. This project leverages Machine Learning to predict the outcomes of tournament games by analyzing historical performance, team seeding, and seasonal statistics.

Instead of relying on gut feelings, this engine uses a data-driven approach to forecast win probabilities for over 500,000+ possible matchups in the 2026 tournament.

# 🛠️ Tech Stack
Language: Python 3.x

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Models Tested: Logistic Regression, Random Forest, XGBoost

Data Processing: StandardScaler, SimpleImputer, OneHotEncoding

# 🚀 Key Features & Strategy
# 1. Advanced Feature Engineering
The secret to the model’s performance lies in the Relative Difference Metrics. Instead of raw scores, I engineered:

Seed Difference: The ranking gap between opponents.

Win Ratio Gap: Comparative seasonal consistency.

Avg Score Difference: Evaluating offensive firepower.

Interaction Features: Combining Win Ratios with Seeds to identify potential "Cinderella" (underdog) teams.

# 2. Leakage Prevention
I implemented a strict data cleaning pipeline to remove Data Leakage. Post-game statistics (like final scores) were excluded from training to ensure the model only uses information available before the match starts.

# 3. Handling Missing Data
Using SimpleImputer, I ensured that even for newer teams with missing historical stats, the model provides a reliable prediction by using median baseline metrics.

# 📊 Results & Analysis
Top Accuracy: 73.05% (Achieved using Random Forest).

Baseline Accuracy: 70.73% (Logistic Regression).

Insight: Ensemble methods (Random Forest/XGBoost) significantly outperformed linear models by capturing complex non-linear relationships between team stats.

# 🏁 Conclusion
This project successfully demonstrates that while "Madness" is inherent to the tournament, data-driven modeling can identify hidden patterns in team performance.

# Key Takeaways:

Relative features (differences between teams) are more predictive than absolute team stats.

Controlling for data leakage is crucial in sports analytics to maintain real-world validity.

Probabilistic forecasting (0 to 1) provides a much better risk assessment than binary (Win/Loss) classification.

## ---------Shudhanshu Ranjan---------
