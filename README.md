# 🛒 Total Solutions Purchase Analysis

![Screenshot 2025-06-21 151031](https://github.com/user-attachments/assets/3ec67a94-cf58-4441-9b99-49efd6cd6bdb)


## 1. 📘 Project Background  
This project involves a comprehensive analysis of sales order data from Total Solutions, a prominent retail conglomerate with a network of stores across India. The primary objective is to extract actionable insights into business performance across various metrics and to rigorously validate previously observed key performance indicators against current data. The dataset encompasses detailed information on purchase amounts, user demographics, product categories, age groups, and other critical features. The analytical scope includes robust data cleaning, in-depth Exploratory Data Analysis (EDA), and a series of hypothesis tests designed to confirm or refute historical business assumptions.

---

## 2. 📊 Executive Summary  
The detailed analysis of the purchase data has yielded several significant insights into customer demographics, purchasing patterns, and city-wise performance:

### 👥 Gender Demographics and Purchase Contribution  
The dataset comprises a total of 5,891 users, with males constituting the majority at 4,225 users and females at 1,666 users. Correspondingly, men account for a substantial 75.47% of total purchases, while women contribute 24.43%.

### 👶 Age Group Performance
![Screenshot 2025-06-22 173053](https://github.com/user-attachments/assets/8591051a-708c-4339-a6d9-ec710bd328a0)



- The 26-35 age group demonstrates the highest engagement and purchasing activity, recording 104,912 purchases, nearly double that of the second-highest group (36-45), which registered 52,396 purchases. The 0-17 age group shows the lowest activity, with only 7,064 purchases.  
- This trend extends to user count, with the 26-35 age group having the highest number of users (2,053) and the 0-17 age group having the fewest (218).  
- Financially, the 26-35 age group leads significantly with a total purchase amount exceeding 975 million, whereas the 0-17 age group accounts for the lowest total purchase amount, over 64 million.  
- As expected, the 26-35 age group exhibits the highest average purchase amount per user. Interestingly, despite having the lowest total purchase, the 0-17 age group surpasses the 55+ age group in terms of average purchase amount per user.

### 🏙️ City Category Performance  
![Screenshot 2025-06-23 180645](https://github.com/user-attachments/assets/ed202b87-fc8f-4902-a861-421cc5e04ec3)

- City Category B accounts for the largest proportion of purchases at 42.25%, followed by City C at 30.83% and City A at 26.91%.
- City A consistently demonstrates the lowest performance across all age groups in terms of total purchases, total users, and total purchase amounts.
- Cities in Category B consistently attract the highest total purchase amount across age groups ranging from 18-25 to 51-55. This suggests a strong purchasing power and engagement in this category.
- Conversely, cities in Category C demonstrate the highest user acquisition for each age group, suggesting a broader customer base, albeit with potentially lower individual purchase values compared to City B. This implies that City B exhibits a higher average purchase amount compared to both City C and City A.


### 💑 Marital Status and Purchase Behavior
![Screenshot 2025-06-22 173839](https://github.com/user-attachments/assets/c03cecf4-d3af-4346-9cbd-028941d44560)

The unmarried customer segment exhibits a higher average purchase amount per user, at 423,573, compared to the married group, which stands at 405,722.  
Furthermore, the unmarried group also comprises a larger user base, with 3,417 users, as opposed to 2,474 users in the married group.

---

## 3. ✅ Summary of Hypothesis Testing  
Four key hypotheses were rigorously tested to validate historical claims and current trends:

### 🧪 Hypothesis 1: Average Purchase by Men (18-25 Age Group)  
**Original Observation**: The average purchase made by men aged 18-25 was approximately 10,000.  
**Conclusion**: Based on a t-test, there is sufficient evidence to conclude that the average purchase amount for men in the 18-25 age group is no longer 10,000. This indicates a significant shift from previous observations.

### 🧪 Hypothesis 2: Percentage of Men Spending >10,000 (18-25 vs. 26-35 Age Groups)  
**Original Question**: Is the percentage of men who have spent more than 10,000 the same for the 18-25 and 26-35 age groups?  
**Conclusion**: A Z-test for proportions provided sufficient evidence to conclude that the percentage of men who have spent more than 10,000 is indeed consistent between the 18-25 and 26-35 age groups.

### 🧪 Hypothesis 3: Percentage of Women Spending >10,000  
**Original Observation**: It was observed that 35% of women spent more than 10,000.  
**Conclusion**: A Z-test for proportions indicates that there is enough evidence to conclude that the proportion of women who spent more than 10,000 is no longer 35%. This suggests a change in the spending habits of women compared to historical data.

### 🧪 Hypothesis 4: Variance of Purchase Amounts by Gender (18-25 Age Group)  
**Original Question**: Are the variances of purchase amounts significantly different between men and women in the 18-25 age group?  
**Conclusion**: The Levene test provided sufficient evidence to conclude that the variance of purchase amounts between men and women in the 18-25 age group is significantly different. This highlights distinct purchasing variability between genders in this demographic.

---

## 4. 📌 Business Recommendations  
Based on the derived insights and the outcomes of the hypothesis tests, the following strategic recommendations are proposed for Total Solutions:

### 🔁 Maintain Consistent Strategies for Men Across Age Groups (18-35)  
The finding that the percentage of men spending over 10,000 is consistent between the 18-25 and 26-35 age groups (Hypothesis 2 accepted) suggests that marketing approaches for high-value male customers can be broadly similar across these two significant age segments. Focus on strategies that successfully encourage higher spending within these groups.

### 👩‍💼 Address Shift in Women's Spending Habits  
The significant change in the proportion of women spending over 10,000 (Hypothesis 3 rejected) necessitates a thorough investigation. Total Solutions should explore the reasons behind this shift and adapt their product offerings, promotions, and communication strategies to re-engage female customers and encourage higher purchase values.

### 🧬 Gender-Specific Product and Promotion Tailoring (Age 18-25)  
The distinct variances in purchase amounts between men and women in the 18-25 age group (Hypothesis 4 accepted) call for highly targeted product recommendations and promotions. Understanding the factors driving these differences can help optimize inventory and personalize marketing efforts more effectively for each gender.

---

### 🏙️ Strategic Focus on City Categories  
- **City A**: As the lowest-performing city category across all metrics (purchases, users, and purchase amount), City A requires a strategic re-evaluation. Total Solutions should investigate the underlying reasons for its low performance. This might involve market research to understand local demographics, competitive landscape, or product-market fit. Depending on the findings, strategies could range from targeted promotional campaigns to re-evaluating store presence or product assortments in this specific category.
- **City B**: Given its consistent high total purchase amount across key age groups (18-55), City B represents a high-value market. Investment should be directed towards expanding product availability, premium offerings, and loyalty programs that reward high spending.  
- **City C**: With the highest user acquisition but lower average purchases, City C offers an opportunity for growth. Strategies here should focus on converting new users into repeat customers and gradually increasing their spending through targeted promotions and value-added services.

---

### 🧑‍💼 Capitalize on the 26-35 Age Group  
This age group is consistently the most valuable across purchases, users, and total purchase amounts. Resources should be allocated to further understand and capitalize on their preferences, ensuring product availability and loyalty programs are optimized for this segment.

### 💖 Leverage Unmarried Customer Segment  
The unmarried group represents a larger user base with higher average purchase amounts. Marketing efforts and loyalty programs could be specifically designed to cater to this segment, potentially focusing on individual-centric products or experiences.

### 📈 Continuous Data-Driven Decision Making  
Regularly update and re-evaluate these insights and hypotheses with fresh data. This iterative approach will ensure that business strategies remain agile and responsive to evolving customer behaviors and market dynamics.
