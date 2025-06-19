# 👋 hi, I'm Blessing.
<h3>Data Analyst 📊 &nbsp;||&nbsp; Business Intelligence 👩‍💻 </h3>

---

## 📌 About Me
I’m [Blessing Chinecherem Udeh](https://www.linkedin.com/in/udeh-blessing?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) a results-driven, process-oriented Data Analyst with hands-on experience in building clean, efficient data pipelines and crafting interactive visuals that turn raw data into compelling stories. Over the past few years, I’ve dedicated myself to the data analytics space helping businesses solve real problems and make smarter decisions. Today, I’m taking this experience further by developing sophisticated recommendation systems and predictive models that add even more value. I love making data approachable and actionable, and I’m always excited to tackle challenges that push me to keep learning and growing
---
## 🧩 Key Competences:
- #### Analytics
- #### Data Wrangling
- #### Data Governance
- #### Data Preprocessing
- #### Data Reporting
- #### Interactive Visual
- #### Data Preprocessing
---

## 🛠️ Data toolkits
<p align="left">
  <a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank" rel="noreferrer">
    <img src="https://img.icons8.com/color/48/000000/microsoft-excel-2019--v1.png" alt="Excel" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40"/>
  </a>
  <a href="https://powerbi.microsoft.com/" target="_blank" rel="noreferrer">
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI" width="40" height="40"/>
  </a>
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  </a>
  <a href="https://azure.microsoft.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="Microsoft Azure" width="40" height="40"/>
  </a>
  <a href="https://cloud.google.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="Google Cloud" width="40" height="40"/>
  </a>
  <a href="https://aws.amazon.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="40" height="40"/>
  </a>
  
  ---
  
 ## 🎓 Certifications 
 - Certificate of completion with credit in Data Anlysis from Digital Dreams.
---
## Education 
📚 BSC in Economic from Enugu State University of Science and Technology.
---

## Projects
PROCUREMENT_AND_SALES_RECORD
---

## 📅 Data Tools

Microsoft Excel: Data analysis
Microsoft Powerbi: Dashboard, Data visualization
---

## 📈 Project Objective
- Top performing profitable and Loss-making products and regions
- Analyze customer ratings to enhance product quality and service
- Track employee hours to identify workload distribution and efficiency.
- Detect seasonal sales trends, high-revenue regions, and procurement inefficiencies.
- Assess supplier efficiency, procurement costs, and lead times.
- Measures customer satisfaction per product/region
---
 ## 📊 Insights
 1. Financial Performance Insights
- Northern Region generates the highest revenue, while East Region has the lowest, indicating a need for targeted sales strategies.
- Some transactions are losing money because the cost of buying the products is too high or the selling price is too low, reducing overall profits.
- Certain high-selling products still have low profit margins, meaning pricing strategies need adjustment.
2. Customer Satisfaction Insights
- Products with higher customer ratings (above 4.5) have higher repeat purchases, indicating strong brand loyalty.
- Northern Region consistently receives the highest customer ratings, suggesting better service or product availability.
- Some highly rated products like smartwatch have low sales, showing an opportunity for better marketing or pricing adjustments.
3. Procurement Efficiency Insights
- Supplier hardwave haven offers the lowest cost prices, making them the most cost-effective choice.
- Supplier Lead Times vary significantly, affecting product availability and possibly customer satisfaction.
- Smart watch has high procurement costs but low sales need reassessment to reduce unnecessary expenses.
4. Workforce Productivity Insights
- Certain products require significantly more employee hours, impacting efficiency.
- Southern Region has the highest employee workload, aligning with its high revenue but posing risks of burnout.
- No clear correlation between more employee hours and higher customer ratings, suggesting inefficiencies in workforce allocation.
5. Trends and Patterns
- Seasonal trends indicate that revenue peaks in specific months sales go up and down at different times, so businesses should plan their inventory wisely to avoid running out of stock during busy periods or having too much during slow times.
- When suppliers deliver products faster, customers are happier. Hence the importance choosing reliable suppliers to keep customers satisfied.
- Some high-selling items might have low profit margins, while fewer sales of certain products could bring in more profit,
Profitability and sales volume don’t always align, meaning some high-selling products may not be the most profitable.

 ## Data visualization/ Dashboards
 # DASHBOARDS
![CSD](https://github.com/user-attachments/assets/14c78be6-04bf-4dca-9632-22612a1cc64d)
![customer experience](https://github.com/user-attachments/assets/163da22b-6f73-4fc2-b598-1e41ed91fceb)
![customers experience dashboard](https://github.com/user-attachments/assets/6ea4b982-3687-41d4-827f-084d9d26c05c)
![procurement dp](https://github.com/user-attachments/assets/cf301cc4-ea60-4589-bb0f-3e864b3de669)
![TOTAL REVENUE](https://github.com/user-attachments/assets/ba5be7c3-5f93-47bf-a22e-15bd3710094d)

---

## Project 2
EDA RETAIL
---
## 📅 Data Tools.
python/pandas
1. **DATACLEANING**
- Check for missing values
```
print(df.isnull().sum())
```
No missing values Found

![Isnull](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/project%20EDA%201.PNG)


- Convert 'Date' column to datetime format
```
df["Date"] = pd.to_datetime(df["Date"], format="%m/%d/%Y")
```
2. **Descriptive Statistics**
- Summary statistics
```
print(df.describe())
```
- Check the mean, median, mode of sales column
```
print("Mean Sales:", df['Total Amount'].mean())
print("Median Sales:", df['Total Amount'].median())
print("Mode Sales:", df['Total Amount'].mode()[0])
print("Standard Deviation:", df['Total Amount'].std())
```
![DesriptiveStaistics](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/PJ%20EDA%207.PNG)

2. **Time Series Analysis (Sales Trend Over Time)**
- Group by date and sum sales
```
df_time_series = df.groupby('Date')['Total Amount'].sum()
```
- Plot sales trend over time
```
plt.figure(figsize=(12,6))
df_time_series.plot(title='Sales Trend Over Time', marker='o', linestyle='-')
plt.xlabel('Date')
plt.ylabel('Total Amount')
plt.grid()
plt.show()
```
![SALESSTRENDOVERTIME](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/PJ%20EDA%202.PNG)

3. **Customer & Product Analysis**
- Top 5 customers by total purchases
```
top_customers = df.groupby('Customer ID')['Total Amount'].sum().sort_values(ascending=False).head(5)
print(top_customers)
```
![top5customers](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/PJ%209.PNG)
- Top 5 best-selling products
```
top_products = df.groupby('Product Category')['Total Amount'].sum().sort_values(ascending=False).head(5)
print(top_products)
```
![topproduct](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/pj%2010.PNG)
4. Data Visualization
-  Sales Distribution
```
plt.figure(figsize=(10,5))
sns.histplot(df['sales'], bins=20, kde=True)
plt.title('Sales Distribution')
plt.show()
```
![SD](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/PJ%20EDA%204.PNG)

- Sales by Product Category (Bar Chart)
```
plt.figure(figsize=(12,6))
df.groupby('product_category')['sales'].sum().sort_values().plot(kind='barh', color='skyblue')
plt.title('Total Sales by Product Category')
plt.xlabel('Total Sales')
plt.ylabel('Product Category')
plt.show()
```
![PD](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/PJ%20EDA%205.PNG)

- Correlation Heatmap
```
sns.heatmap(numeric_df.corr(), annot=True, cmap='coolwarm', fmt=".2f")
```
![CH](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/PJ%20EDA%206.PNG)

 ## RECOMMENDATION
1.**Focus on High-Spending Customers**
- A small percentage of customers  are responsible for a large portion of revenue.
  
**These are the following customers**
  
- Customer ID

CUST015    2000

CUST412    2000

CUST970    2000

CUST547    2000

CUST281    2000

  **Action**
- Implement loyalty programs or exclusive discounts for top customers.
- Send personalized emails and early access to new products to keep them engaged.

2.**Optimize Sales on High-Traffic Days**
- There are more significantly sales on weekends
  
**Action**
- Launch flash sales or promotions on high-traffic days.
- Ensure inventory and staffing are adequate on those days to meet demand.

3 **Stock High-Performing Product Categories**
- Electronics are purchased more often
  
**Action**
- Increase inventory for top-performing categories.
- Use product bundling to promote lower-performing product like Beauty categories alongside bestsellers.

4.**Leverage Gender-Based Insights**
- Sales are unevenly distributed across gender groups.
  
**Action**
- Create gender-specific promotions or ads targeting the higher-spending group.
- Explore product feedback to better cater to the needs of underrepresented groups.

5 **Plan Inventory Based on Seasonal Sales Trends**
- Sales trends over time reveal seasonal patterns.
**Action**
- Prepare early restocking plans and marketing campaigns aligned with peak months. The peak months are April,May and October ~
- Using predictive models to forecast future sales during peak seasons,
![PMF](https://github.com/NECHEBLESSING/EDA.Retail/blob/main/EDA%20200.PNG)

- Showing forecast predictions of same months in 2025 will be the peak months.
6 **Simplify Product Mix Based on Market Basket Analysis**
- Certain products are frequently bought together Like (Clothing and Beauty)

 **Action**
- Offer combo deals or bundles to increase average transaction value.
- Redesign store layout (online or physical) to promote frequently paired products.
  
7.**Improve Data Collection**
- Insight: The current dataset lacks deeper demographics (like age, location).
  
**Action**
- Encourage customers to create detailed profiles during sign-up.
- Offer small incentives for completing surveys that enhance customer understanding.

## 📞 Contact Me

- 📧 [Email](danielchinecheremblessing@gmail.com)
- 🔗 LinkedIn: [Blessing Chinecherem Udeh](https://www.linkedin.com/in/udeh-blessing?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
- 💬 WhatsApp: +234905036
- ☎️ Phone: +234905036



 
 

 




