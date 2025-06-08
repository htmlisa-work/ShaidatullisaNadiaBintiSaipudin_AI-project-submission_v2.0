# 📊 Employee Sentiment Analysis

## 🚀 Project Introduction

This project analyzes an unlabeled dataset of employee email messages to assess sentiment and engagement across a two-year period. Using a combination of natural language processing (NLP), exploratory data analysis (EDA), employee scoring, flight risk detection, and predictive modeling, the project transforms raw communication data into actionable organizational insights.

The goal is to help teams and HR departments understand sentiment trends, recognize top performers, flag potential retention risks, and make data-driven decisions to improve employee engagement.

---

## ⚙️ Setup Instructions

1. Clone this repository or download and extract the ZIP package.

2. Navigate to the project directory.

3. Install dependencies using:

   ```bash
   pip install -r requirements.txt
   ```

4. Make sure you have Python 3.x installed.

---

## 📝 Usage Instructions

To run the full analysis:

1. Open `FinalLLM_EmployeeSentimentAnalysis.ipynb` in Jupyter Notebook, JupyterLab, or another compatible IDE.
2. Run all cells from top to bottom to reproduce the full workflow.
3. Ensure the dataset `test.csv` is placed inside the `data/` folder.
4. Output files will be generated automatically in the appropriate directories.

---

## 📂 Output Files

Running the notebook will generate:

* `employee_messages_labeled.csv` – sentiment-labeled messages
* `monthly_sentiment_scores.csv` – per-employee, per-month sentiment scoring
* `flight_risk_employees.csv` – list of employees flagged as flight risks
* Visualizations in `project_output/visualizations/`
* Optional final PDF report in `project_output/`

---

## 🌟 Highlights

### ✅ Top 3 Positive Employees

* [eric.bass@enron.com](mailto:eric.bass@enron.com)
* [john.arnold@enron.com](mailto:john.arnold@enron.com)
* [sally.beck@enron.com](mailto:sally.beck@enron.com)

### ⚠️ Top 3 Negative Employees

* [bobette.riner@ipgdirect.com](mailto:bobette.riner@ipgdirect.com)
* [don.baughman@enron.com](mailto:don.baughman@enron.com)
* [rhonda.denton@enron.com](mailto:rhonda.denton@enron.com)

### 🔥 Employees Flagged as Flight Risks

*(See full list in `flight_risk_employees.csv`)*

* [lydia.delgado@enron.com](mailto:lydia.delgado@enron.com)
* [john.arnold@enron.com](mailto:john.arnold@enron.com)
* [patti.thompson@enron.com](mailto:patti.thompson@enron.com)

> **Flight Risk Rule**: Any employee who sent 4 or more negative messages within any 30-day rolling period.

---

## 🔍 Key Insights

* **Sentiment Breakdown**: Positive sentiment was more frequent overall, with negative messages typically being longer and more detailed.
* **Monthly Trends**: While positivity led overall, recurring negative spikes were observed in some months.
* **Employee Behavior**: Most employees maintained a balanced tone, but a few stood out with consistently high negativity.
* **Flight Risk Detection**: Rolling window logic successfully identified individuals showing signs of disengagement.
* **Model Performance**: The linear regression model explained **\~71%** of sentiment score variation (R² = 0.7075, MSE = 2.45).

---

## 📌 Summary & Recommendations

* 🎯 **Recognize Top Contributors**: Celebrate consistently positive communicators.
* 🧩 **Address Chronic Negativity**: Support employees with recurring negative sentiment through feedback loops or HR outreach.
* 🚨 **Track Flight Risks**: Prioritize flagged individuals for check-ins or intervention.
* 📈 **Enhance Modeling**: Incorporate more advanced models (e.g., Gradient Boosting) and context features like department/team.
* 📊 **Set Up Monitoring**: Build a live dashboard to detect short-term sentiment shifts in real time.

---

## 👩‍💻 Author

**Shaidatullisa Nadia Binti Saipudin**
📅 *Finalized: 8th June 2025*
