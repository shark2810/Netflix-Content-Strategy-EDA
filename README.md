# Netflix Content Strategy Analysis: Decoding the "Streaming Wars" 🎬
## 📌 Business Context
In the era of fierce competition from Disney+, HBO Max, and Amazon Prime, Netflix faces the challenge of optimizing its multi-billion dollar content budget. This project leverages historical data to answer a critical strategic question: *What type of content and release timing will maximize subscriber retention and ROI?*
## 🎯 Project Objectives
- **Content Evolution:** Evaluate shifts in format and duration over the last decade (2010–2021).
- **Acquisition Strategy:** Decode the "Release Gap" to distinguish between Licensed content and Netflix Originals.
- **Strategic Recommendations:** Provide data-driven advice on content production and library management.
## 🛠 Tech Stack & Methodology
- **Language:** Python
- **Libraries:** Pandas (Data Wrangling), Matplotlib & Seaborn (Statistical Visualization).
- **Workflow (ETL & EDA):**
  - **Data Cleaning:** Handled missing values and transformed text-based duration/date fields into numeric and datetime formats.
  - **Feature Engineering:** Extracted key variables: `duration_min` and `release_gap`.
## 💡 Strategic Insights
### 1. The Rise of "Fast & Short" Content
- **Finding:** A steady decline in average movie durations from 2010 to 2021.
- **Value:** Reflects Netflix's adaptation to modern consumption habits (Gen Z) and the rising influence of short-form video platforms.
### 2. The Dominance of Netflix Originals
- **Finding:** The "Release Gap" distribution is heavily right-skewed, with over 70% of content added within 0-1 year of its release date.
- **Value:** Confirms a strategic shift from being a "film archive" to an "exclusive digital cinema," prioritizing original productions to secure permanent IP rights.
## 🚀 Actionable Recommendations
- **Optimize Completion Rates:** Limit the duration of original productions to **90–100 minutes** to maximize user completion rates.
- **Long-tail Acquisition:** Continue acquiring low-cost classic titles (10-20 year release gap) to fill the library for niche audience segments without inflating the budget.
