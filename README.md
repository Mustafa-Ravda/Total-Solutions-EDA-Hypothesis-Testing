# Total-Solutions-EDA-Hypothesis-Testing

# 🛒 Total Solutions Purchase Analysis

## 1. 📘 Project Background

This project involves a comprehensive analysis of sales order data from **Total Solutions**, a prominent retail conglomerate with a network of stores across India.  
The primary objective is to extract actionable insights into business performance across various metrics and to rigorously validate previously observed key performance indicators against current data.  

The dataset encompasses detailed information on:
- Purchase amounts  
- User demographics  
- Product categories  
- Age groups  
- Other critical features  

The analytical scope includes:
- ✅ Robust data cleaning  
- ✅ In-depth Exploratory Data Analysis (EDA)  
- ✅ A series of hypothesis tests to confirm or refute historical business assumptions  

---

## 2. 📊 Overview of Insights

<details>
<summary>👥 <strong>Gender Demographics and Purchase Contribution</strong></summary>

- The dataset comprises a total of **5,891 users**  
  - 👨‍💼 Males: **4,225 users** (75.47% of total purchases)  
  - 👩‍💼 Females: **1,666 users** (24.43% of total purchases)

</details>

<details>
<summary>🧓 <strong>Age Group Performance</strong></summary>

- **26-35** age group:
  - 📈 Highest number of purchases: **104,912**  
  - 👥 Highest users: **2,053**  
  - 💰 Total purchase amount: **₹975M+**  
- **36-45**: Second highest with **52,396 purchases**  
- **0-17** age group:
  - 📉 Lowest purchases: **7,064**  
  - 📉 Lowest users: **218**  
  - 💡 Surprisingly higher average purchase/user than 55+ age group

</details>

<details>
<summary>🏙️ <strong>City Category Performance</strong></summary>

- 🥇 **City Category A**: 42.25% of total purchases  
- 🥈 **City Category B**: 30.83%  
- 🥉 **City Category C**: 26.91%  

- 📌 City B: Highest total purchases in age groups 18–55  
- 🌍 City C: Highest user acquisition across age groups  
- 💡 Insight: City B = higher average purchase/user vs. City A and C

</details>

<details>
<summary>💍 <strong>Marital Status and Purchase Behavior</strong></summary>

- **Unmarried** users:
  - 📊 Avg purchase/user: ₹423,573  
  - 👥 User base: 3,417  
- **Married** users:
  - 📉 Avg purchase/user: ₹405,722  
  - 👥 User base: 2,474  

</details>

---

## 3. ✅ Summary of Hypothesis Testing

<details>
<summary>🧪 <strong>Hypothesis 1: Average Purchase by Men (18-25 Age Group)</strong></summary>

- 🔍 **Original Observation**: Avg purchase ≈ ₹10,000  
- ✅ **Conclusion**: T-test shows the avg purchase is **no longer ₹10,000**

</details>

<details>
<summary>🧪 <strong>Hypothesis 2: % of Men Spending >₹10,000 (18-25 vs 26-35)</strong></summary>

- 🔍 **Question**: Is % the same between these two age groups?  
- ✅ **Conclusion**: Z-test confirms the % is consistent

</details>

<details>
<summary>🧪 <strong>Hypothesis 3: % of Women Spending >₹10,000</strong></summary>

- 🔍 **Original Observation**: 35% of women spent > ₹10,000  
- ❌ **Conclusion**: Z-test shows this is **no longer 35%**

</details>

<details>
<summary>🧪 <strong>Hypothesis 4: Variance by Gender (18-25 Age Group)</strong></summary>

- 🔍 **Question**: Is variance of purchase amounts different by gender?  
- ✅ **Conclusion**: Levene test shows a **significant difference**

</details>

---

## 4. 📌 Business Recommendations

- 📉 **Re-evaluate Marketing for Men (18-25)**  
  The average spend has shifted. Tailor pricing, product bundles, and offers accordingly.

- 🔁 **Uniform Strategy for Men (18-35)**  
  Since the % of high spenders is consistent, streamline campaigns across both age brackets.

- 👩 **Investigate Shift in Women’s Spending**  
  Adapt marketing and product design to re-engage and elevate average spend.

- 🎯 **Gender-Specific Promotions for Age 18-25**  
  Purchase variance justifies personalized product recommendations and ads.

- 🧑‍💼 **Prioritize the 26–35 Age Group**  
  They dominate in users and purchases. Double down on loyalty programs and stock preferences.

- 🏙️ **Strategic City-Level Investment**
  - 📌 City B: High purchase volume = upselling opportunity  
  - 📌 City C: High user base = target for increasing purchase value

- 💖 **Focus on Unmarried Customers**  
  Bigger user base and higher avg spend. Customize offers for solo-lifestyle or aspirational products.

- 📈 **Commit to Iterative, Data-Driven Decision Making**  
  Regularly revisit KPIs and hypotheses to stay in sync with evolving customer behavior.

---

