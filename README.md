<h1>Customer Churn Analysis System
(Synthetic Data – Exploratory Data Analysis Project)</h1>
<h2>Overview</h2>

<P>Customer churn is one of the most critical challenges faced by businesses such as banks, telecom companies, and subscription-based services. When customers stop using a service, it leads to revenue loss and increases the cost of acquiring new customers.</P>

<p>This project focuses on building a Customer Churn Analysis System using synthetic data. The system generates realistic customer data and performs Exploratory Data Analysis (EDA) to identify patterns, trends, and key factors influencing customer churn.</p>

<h2>The workflow includes:</h2>

1.Synthetic data generation<br>
2.Data preprocessing and cleaning<br>
3.Statistical analysis<br>
4.Churn behavior analysis<br>
5.Data visualization<br>
6.Insight generation<br>

<h2>Dataset Description</h2>

<p>The dataset is synthetically generated with 100,000 customer records to simulate real-world scenarios.</p>

<p>Column Name:	Description
Customer_ID:	Unique identifier<br>
Age:	Age (18–70)<br>
Gender:	Male / Female<br>
Tenure:	Years with company (0–10)<br>
Balance:	Account balance (0–200,000)<br>
CreditScore:	Credit score (300–900)<br>
EstimatedSalary:	Annual income (10,000–150,000)<br>
NumOfProducts:	Number of products used (1–4)<br>
IsActiveMember:	Active status (Yes/No)<br>
Churn:	0 = No, 1 = Yes<br></p>
  
<h2>Objectives</h2>

<p>The main objective of this project is to perform EDA on customer data and identify key factors affecting churn.</p>

<p>Specific Goals:</p>
1.Generate realistic synthetic dataset<br>
2.Perform data cleaning and preprocessing<br>
3.Compute descriptive statistics<br>
4.Analyze churn behavior<br>
5.Perform group-based and relationship analysis<br>
6.Visualize patterns using charts<br>
7.Extract actionable business insights<br>

<h2>Project Highlights</h2>
<h3>1. Data Generation</h3>
1.Created a synthetic dataset using Python libraries<br>
2.Simulated real-world customer behavior<br>
3.Generated logical churn patterns based on:<br>
4.Low balance<br>
5.Low credit score<br>
6.Inactive membership<br>
<h3>2. Data Cleaning & Preprocessing</h3>
1.Checked for missing values<br>
2.Verified data types<br>
3.Encoded categorical variables (Gender)<br>
4.Ensured consistency across dataset<br>
<h3>3. Descriptive Statistics</h3>

<h3>Calculated key statistical measures:</h3>

1.Mean<br>
2.Median<br>
3.Mode<br>
4.Standard Deviation<br>

<p>This helps in understanding:</p>

1.Data distribution<br>
2.Variability<br>
3.Central tendency<br>
<h3>4. Churn Behavior Analysis</h3>
1.Identified high churn segments<br>
2.Compared churn vs non-churn customers<br>
<p>Observed patterns in:</p>
1.Balance<br>
2.Activity status<br>
3.Credit score<br>
<h3>5. Group-Based Analysis</h3>

<p>Analyzed churn across different groups:</p>

1.Age groups vs churn<br>
2.Gender vs churn<br>
3.Active vs inactive members<br>
4.Number of products vs churn<br>
<h3>6. Relationship Analysis</h3>

<p>Studied relationships between variables:</p>

1.Balance vs churn<br>
2.Credit score vs churn<br>
3.Tenure vs churn<br>

<p>Used correlation analysis to identify strong predictors.</p>

<h3>7. Data Visualization</h3>

<p>Used various plots for better understanding:</p>

1.Bar charts (churn distribution)<br>
<img width="736" height="567" alt="image" src="https://github.com/user-attachments/assets/7c48a0e9-d779-4027-893d-2d29b31709a0" />

2. Pie charts (churn percentage)<br>
<img width="510" height="510" alt="image" src="https://github.com/user-attachments/assets/9a8895ab-2faf-4d58-84e6-bd003e6b7e65" />

3. Histograms (age distribution)<br>
<img width="696" height="543" alt="image" src="https://github.com/user-attachments/assets/6b81ade4-a5fe-4f69-a9f4-1f77dc9cbb9e" />

4. Scatter plots (balance vs salary)<br>
<img width="751" height="570" alt="image" src="https://github.com/user-attachments/assets/b41eba9e-6990-4665-98a6-c6661e9b4930" />

5. Box plots (balance vs churn)<br>
<img width="750" height="568" alt="image" src="https://github.com/user-attachments/assets/09a4ad03-df58-4400-9b3f-0d6bf22a7ab6" />

6. Heatmaps (correlation matrix)<br>
<img width="785" height="666" alt="image" src="https://github.com/user-attachments/assets/e72edce6-2390-4733-9823-42f4f0c65144" />

<h3>Tools & Technologies</h3>
1.Python<br>
2.pandas<br>
3.numpy<br>
4.matplotlib<br>
5.seaborn<br>
<h2>Results & Insights</h2>
1.Customers with low account balance are more likely to churn<br>
2.Inactive members show significantly higher churn rates<br>
3.Low credit score increases churn probability<br>
4.Customers with fewer products tend to leave more<br>
5.Certain age groups show higher churn patterns<br>
<h2>Conclusion</h2>

<p>This project successfully demonstrates how synthetic data and EDA techniques can be used to analyze customer churn behavior.</p>

<p>The system helps in:</p>

1.Identifying key churn drivers<br>
2.Understanding customer segments<br>
3.Supporting data-driven decision making<br>

<p>The modular approach ensures the project is scalable and can be extended to real-world datasets.</p>
