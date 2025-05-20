# telco-customer-analysis
Analyze telecom customer data to compare Surf vs Ultimate plans and their revenue impact.

## 📈 Project Objective

The goal is to simulate and analyze telco customer behavior across two prepaid mobile plans and evaluate revenue performance. This includes:

- Cleaning and preparing customer usage data (minutes, messages, internet)
- Calculating total monthly revenue per user
- Comparing plan profitability
- Visualizing trends and testing statistical significance

---

## 📊 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- SciPy

---

## 🧠 Analysis Summary

- Created mock datasets simulating 100 users over 6 months
- Modeled real-world prepaid plan logic (free limits + overage charges)
- Calculated revenue by customer/month
- Used t-test to test if revenue differences were statistically significant

---

## 📌 Key Insights

- **Ultimate** plan generates more revenue per customer on average.
- Statistical testing confirms the difference is **significant** (p < 0.05).
- Promoting upgrades from Surf to Ultimate could increase profit.

---

## 🛠️ How to Run the Notebook

You can open the analysis in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

Or run locally:

```bash
pip install pandas numpy matplotlib seaborn scipy
