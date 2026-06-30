# COVID-19 Data Analysis Project

An Exploratory Data Analysis (EDA) project focusing on the distribution, recovery trends, and mortality metrics of COVID-19 cases using Python, Pandas, and Seaborn.

## 📊 Core Insights

### 1. Univariate Analysis
* **Distribution Shape:** The raw data is heavily **right-skewed**, with extreme outliers extending up to ~135,000 cases.
* **Log-Scale Transformation:** Applying a log-scale reveals a **bimodal distribution** with two prominent peak outbreak intensities: one localized tier at $10^1$–$10^2$ cases and a major surge tier at $10^3$–$10^4$ cases.

### 2. Bivariate & Multivariate Analysis
* **Recovery & Mortality Lifecycles:** Both `Cured` and `Deaths` scale linearly with `Confirmed` cases over time. 
* **Regional Branching:** Clear geometric branching trajectories in the low-to-mid range suggest varying regional healthcare outcomes or timeline variations.
* **Data Anomalies:** A distinct reporting gap/vertical leap is observed around 110,000 cases, highlighting cumulative backlogged data audits.
