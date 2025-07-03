 🚗 Automobile Market Analysis Using Python (EDA Project)

This project presents a comprehensive Exploratory Data Analysis (EDA) of customer data from Austo Motor Company, aimed at understanding key trends in car purchases based on customer demographics, financial attributes, and product preferences.

The analysis was conducted using Python and key data science libraries, and results are summarized in both a Jupyter Notebook and a professional PDF business report.

---

 📌 Project Objectives

- Identify which customer segments prefer Sedans, SUVs, or Hatchbacks
- Analyze the relationship between salary, loans, and car purchases
- Explore how factors like gender, marital status, and partner's employment influence spending behavior
- Deliver actionable insights to inform marketing and sales strategy

---

 📊 What I Did in This Project

- Data Cleaning:
  - Handled missing values in `Gender` and `Partner Salary`
  - Corrected data entry errors (e.g., “Femal”, “Femle” → “Female”)
  - Imputed missing values using logical relationships (e.g., `Total Salary - Salary = Partner Salary`)
  - Checked and confirmed absence of duplicate records

- Data Preprocessing:
  - Verified data types and structures
  - Converted appropriate columns to categorical/numeric formats
  - Created derived variables for deeper insights

- Univariate Analysis:
  - Analyzed distributions of age, salary, price, car type, etc.
  - Visualized data using histograms, box plots, and count plots

- Bivariate & Multivariate Analysis:
  - Explored relationships between variables (e.g., income vs. car type)
  - Used heatmaps to examine correlations
  - Grouped data by categorical variables to extract trends

- Insight Generation:
  - Answered key business questions using data-driven logic
  - Derived actionable marketing strategies for customer segments
  - Presented findings in a clean and readable PDF report

---

 ❓ Key Business Questions Answered

1. Do men tend to prefer SUVs more compared to women?  
   → Compared gender-based SUV ownership and purchasing behavior.

2. What is the likelihood of a salaried person buying a Sedan?  
   → Explored sedan preference ratios across professional categories.

3. What evidence or data supports Sheldon Cooper's claim that a salaried male is an easier target for a SUV sale over a Sedan sale?  
   → Validated the claim using segmented preference analysis.

4. How does the amount spent on purchasing automobiles vary by gender?  
   → Compared average and total spending by male and female customers.

5. How much money was spent on purchasing automobiles by individuals who took a personal loan?  
   → Analyzed car spending among customers with personal loans.

6. How does having a working partner influence the purchase of higher-priced cars?  
   → Investigated how partner employment status affects car pricing behavior.

---

 🛠️ Tools & Technologies

- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Platform: Jupyter Notebook

---

 📁 Files Included

- `Project_Python_for_Data_Science_Austo_Automobiles.ipynb` – Python notebook with full analysis
- `Business Report - Automobile Market Analysis Using Python-Based Data Science.pdf` – Clean, presentation-ready business report

---

 📈 Key Insights

- Sedans are the most popular vehicle type overall
- Female customers prefer SUVs and tend to spend more on average
- Younger customers are more likely to rely on personal loans
- Households with dual incomes lean toward higher-priced models
- High income correlates strongly with SUV preference, while Hatchbacks are favored by low-income customers

---

 💡 Business Impact

The findings from this analysis can help Austo Motor Company:
- Design targeted marketing campaigns by gender and income level
- Offer loan-based promotions to first-time or young buyers
- Optimize inventory and product offerings for different regions and professions

---

 🚀 How to Use

You can run the `.ipynb` notebook using Jupyter:

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Project_Python_for_Data_Science_Austo_Automobiles.ipynb
