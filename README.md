# 📊 Student Budget Intelligence Dashboard (SpendLens)

## 📌 Overview
This project analyzes student spending behavior using transaction data. The goal is to understand where money is spent, identify spending patterns, and provide insights for better financial management.

---

## 🧹 Data Cleaning
The dataset contained inconsistencies and missing values, which were handled as follows:

- Converted mixed date formats into a standard datetime format
- Replaced missing category values with "Unknown"
- Standardized category names (e.g., food → Food)
- Checked and removed duplicates
- Created new columns: Day and Month for analysis

---

## 📊 Key Visualizations

- **Monthly Spending Trend** → Shows how spending changes over time  
- **Payment Method Distribution** → Highlights UPI dominance  
- **Top Merchants Analysis** → Identifies where most money is spent  
- **Category Distribution** → Shows major expense categories  

---

## 🧠 Insights

- Most spending is concentrated in **Utilities and Education**
- Spending is higher during certain months due to one-time expenses
- **UPI is the most used payment method**
- A large portion of expenses is fixed (rent, bills, fees)

---

## 📝 Summary

The analysis shows that most of the student’s spending goes towards essential categories like Utilities and Education. Spending is higher in certain months due to one-time expenses, but remains stable overall. Weekend and lifestyle expenses like Food and Entertainment also contribute significantly.

---

## 💡 Recommendation

To improve financial management, the student should focus on controlling weekend spending, especially in Food and Entertainment. Setting a weekly limit can help reduce unnecessary expenses and improve savings.

---

## 🛠️ Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Power BI
- Jupyter Notebook

---

## 📁 Files Included

- `spendLess.ipynb` → Analysis notebook  
- `cleaned_student_spending.csv` → Cleaned dataset  
- `SpendLess.pbix` → Dashboard  
- `SpendLess.pdf` → Final report  

---

## 🚀 Outcome

This project transforms raw transaction data into meaningful insights, helping students understand spending habits and make better financial decisions.
