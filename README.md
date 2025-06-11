# 📊 Employee Sentiment Analysis

## 🚀 Project Introduction

This project analyzes an unlabeled dataset of employee email messages to assess sentiment and engagement across a two-year period. Using a combination of natural language processing (NLP), exploratory data analysis (EDA), employee scoring, flight risk detection, and predictive modeling, the project transforms raw communication data into actionable organizational insights.

The goal is to help teams and HR departments understand sentiment trends, recognize top performers, flag potential retention risks, and make data-driven decisions to improve employee engagement.

---

## ⚙️ Setup Instructions

1. Clone this repository or download and extract the ZIP package.
2. Navigate to the project directory.
3. Install the required dependencies.
4. Make sure you have Python 3.x installed.

---

## 📝 Usage Instructions

To run the full analysis:

1. Open `FinalLLMAssessment_v2_0.ipynb` in Jupyter Notebook, JupyterLab, or another compatible IDE.
2. Run all cells from top to bottom to reproduce the full workflow.
3. Ensure the dataset `test.csv` is placed inside the right folder.
4. Output files will be generated automatically in the appropriate directories.

---

## 📂 Output Files

Running the notebook will generate:

* Visualizations in `Visualizations/`
* CSV in `Output files/`

Check the files for more info

---

## 🌟 Highlights

**🔥 Employees Flagged as Flight Risks**

Flight Risk Rule: Any employee who sent 4 or more negative messages within any 30-day rolling period.
* lydia.delgado@enron.com – 110 negative messages
* john.arnold@enron.com – 109 negative messages
* patti.thompson@enron.com – 100 negative messages

**🔍 Key Insights**

* Overall Sentiment Balance: Positive messages (≈1,068) slightly outnumber Negative (≈927), while Neutral is rare (≈186), indicating employees mostly express clear approval or concerns.
* Monthly Mood Cycles: Sentiment scores fluctuate month to month, with peaks (e.g., +4 in Oct/Nov 2010) and troughs (–6 in Aug 2010) for individuals like Bobette Riner, revealing when morale surges or dips.

**Top 3 Monthly Positive Employees (Dec 2011):**

* eric.bass@enron.com 
* sally.beck@enron.com 
* john.arnold@enron.com 

**Top 3 Monthly Negative Employees (Dec 2011):**

* bobette.riner@ipgdirect.com 
* don.baughman@enron.com 
* rhonda.denton@enron.com 

Flight-Risk Clusters: Multiple employees repeatedly cross the 4-negative threshold in rolling windows, signaling sustained dissatisfaction rather than one-off events.

## **📌 Summary**

This analysis transforms raw message data into actionable insights: we labeled sentiment with a hybrid NLP+keyword approach, tracked monthly scores to rank top positive/negative performers, flagged those at risk of disengagement, and uncovered clear temporal patterns in morale. By monitoring flying-risk thresholds and celebrating high-positivity contributors, HR teams can proactively support employee engagement and address concerns before they escalate.

## 👩‍💻 Author

**Shaidatullisa Nadia Binti Saipudin**
📅 *Finalized: 8th June 2025*
