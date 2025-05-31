
# 🏦 Banking Customer Retention Insights

A data-driven project focused on understanding customer churn and loyalty patterns in the banking sector. This project uses Python for analysis and Power BI for business-ready dashboards.

---

## 📌 Business Objective

Banks face the ongoing challenge of retaining customers in a competitive environment. The goal of this project is to:

- Understand **why customers leave** (churn)
- Identify the **key indicators** of churn
- Recommend data-driven strategies to **boost retention**

---

## 🧠 Project Highlights

- Cleaned and processed raw banking customer data
- Explored trends using statistical summaries and visualizations
- Developed a Power BI dashboard for decision-makers
- Proposed retention-focused business solutions

---

## 📊 Exploratory Data Analysis (EDA)

Key questions explored:

- Which customer features correlate most with churn?
- Are certain age groups or tenure segments more at risk?
- What product combinations reduce churn likelihood?

### Sample EDA Outputs

| Feature               | Churn Trend                                              |
|----------------------|----------------------------------------------------------|
| Tenure               | Short-tenure customers churn more often                  |
| Monthly Charges      | Higher monthly fees correlate with higher churn          |
| Services Used        | Customers with more services are more loyal              |
| Age and Gender       | No strong correlation, but younger males churn more      |

---

## 📈 Visualizations

All visuals are in the `visuals/` folder.

```markdown
![Churn by Tenure](visuals/churn_by_tenure.png)
![Salary vs Churn](visuals/salary_vs_churn.png)
![Products vs Churn](visuals/products_vs_churn.png)

```
📄 Data: [data/bank_customer_data.csv](data/bank_customer_data.csv)

---

## 📊 Power BI Dashboard

The Power BI dashboard (located in `powerbi/`) provides:
- Churn segmentation
- Product usage patterns
- KPI filters and slicers by demographics

📁 File: `Banking_Customer_Churn.pbix`

Add visuals using:

```markdown
![Dashboard Overview](visuals/dashboard_overview.png)
```

---

## 📂 Dataset Description

| Column Name     | Description                                        |
|-----------------|----------------------------------------------------|
| CustomerID      | Unique customer ID                                 |
| Age             | Customer age                                       |
| Gender          | Male / Female                                      |
| Tenure          | Number of years as a customer                      |
| Services        | Banking products owned                             |
| MonthlyCharges  | Average monthly fees                               |
| Churn           | Whether the customer has left the bank (Yes/No)    |

Data available in: `data/Banking_Customer_Data.csv`

---

## 🛠 Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Power BI
- Jupyter Notebook
- GitHub for version control

---

## 🗃 Folder Structure

```
📁 data/             → Cleaned banking customer data
📁 notebook/         → Jupyter analysis file
📁 powerbi/          → Power BI reports (.pbix)
📁 visuals/          → Images for README and presentation
📄 README.md         → Project documentation
📄 LICENSE           → MIT License
```

---

## 👤 Maintainer

Maintained as an open educational and analytical resource by an independent contributor.  
Feel free to use, adapt, and cite the work with credit.

---

## 📜 License

Distributed under the MIT License.
