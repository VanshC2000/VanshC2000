> "*Torture the data long enough, and it will confess*" - Ronald H. Coase (and my machine learning professor, every few sentences).

# Hi there, it's Vansh 👋

## About me

I'm a recent graduate of the MSc. in Management Analytics Program at Wilfrid Laurier University in Waterloo, Ontario. I have developed a strong foundation in business analytics and am driven by a passion for leveraging data to derive business insights and tell powerful stories. Equipped with skills in machine learning, data visualization, statistical analysis, and data interpretation, I am excited to embark on a career as a business analyst, where I can apply my skills to help organizations make informed, data-driven decisions.

Before I decided to jump across a pond (or 7) from Mumbai, India, I worked at a leading global ad network as a Senior Digital Campaign Manager. I managed a large number of high-budget digital ad campaigns for four different projects. To optimize these campaigns, I monitored several web analytics dashboards and tweaked campaign settings based on current and predicted trends. While not a traditional marketing analytics position, it broadened my understanding of data analytics and strengthened my number-crunching skills. I also found a sense of achievement in knowing that an improvement in the performance of a digital campaign or project can be directly attributed to the decisions and optimisations made by me. This role influenced my career switch to data analytics. 

When I'm not developing predictive models, cleaning messy data or reading to keep up with this dynamic industry, you'll find me in the kitchen experimenting with wacky food recipes 👨‍🍳. On the weekends, you'll find me on a hike, pretending I'm a movie protagonist on a quest for spiritual enlightenment 🌄.

## Projects

### 1. [Dashboard: Maven Café Sales and Promotional Offer Insights](https://github.com/VanshC2000/Cafe_Sales_and_Promo_Insights)
#### Objective
This project analyzes 30 days of customer activity at Maven Café to evaluate overall sales performance, effectiveness of promotional offers, and the impact of different marketing channels. The dashboard is designed to uncover behavioral patterns and guide future decisions in planning marketing campaigns.

#### Description of data
The dataset consists of three linked tables:
- Offers: Details about each offer including type, reward value, duration, and delivery channels.
- Customers: Demographics such as age, gender, income, and loyalty membership date.
- Events: Logs of transactions and offer-related events (received, viewed, completed) with timestamps.

#### Skills
Power BI, DAX, Data Modeling, Data Visualization, Marketing Analytics, Data Storytelling, Analytical Reporting

#### Results
The dashboard revealed clear behavior patterns: social media was the most effective channel for offer delivery, sales showed steady growth across the month, and certain customer segments had higher offer completion rates. These insights were used to recommend expanding offer deliveries on social media and refining audience targeting based on engagement behavior.

---
### 2. [E-Commerce Order and Customer Analysis Using SQL & Tableau](https://github.com/VanshC2000/E_Commerce_Data_Analysis)
#### Objective
This project analyzes a year of transactional data from an e-commerce retailer to identify patterns in sales performance, customer segmentation, and return behavior. The objective was to build end-to-end data insights using SQL for querying and Tableau for interactive visual storytelling.

#### Description of data
The dataset was sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail). It was first normalized using Power Query, and includes four primary tables: Invoice, which contains transaction-level data with timestamps and customer IDs; Invoiceline, detailing individual line items such as quantity and price; Product, which lists product names and stock codes; and Customer, which provides customer IDs and countries. The data originates from a real but anonymized UK-based business, which is referred to in this project as ShopSmart UK.

#### Skills
MySQL, Tableau, MS Excel, Power Query, Database Normalization, Data Visualization, Exploratory Data Analysis, Cohort Analysis, RFM Segmentation, KPI Design, Analytical Reporting

#### Results
Sales revenue nearly tripled from ~$509K in Q2 2011 to $1.46M by November, with over 90% of sales coming from domestic orders. Customer analysis revealed that the largest segment (622 customers) had low recency and frequency scores, with many following predictable bi-weekly or monthly purchasing cycles. Order and return patterns showed that lower-value orders (under $50) had significantly lower cancellation rates.

---

### 3. [Predicting the Popularity of Online News Articles](https://github.com/VanshC2000/Article_Popularity_Prediction/)
#### Objective
The objective of this report is to predict the popularity of articles posted on Mashable by analyzing different models. The focus is on automating the selection process of articles based on their potential to generate high shares, which directly impacts revenue.

#### Description of Data
The public dataset used in this analysis has details of 39645 articles posted on Mashable, a renowned news website and entertainment company. Broadly, this dataset contained information about keywords used, data channels, the day of posting, hyperlinks, the language used, overall sentiment and the total shares for each article. There were 60 possible metrics in the dataset that could have been used to predict shares.

#### Skills
R, Data Analysis, Machine Learning, Predictive Modeling, Model Comparison and Evaluation, Report Writing

#### Results
The Random Forest model is recommended for effectively predicting and selecting high-share articles on Mashable.

---

### 4. [Detecting Visual Product Defects Using Deep Learning](https://github.com/VanshC2000/anomaly-detection-deep-learning)
#### Objective
This project explores the use of deep learning to automate the inspection process of finished, standardised goods using deep learning models. This reduces the  costs incurred manually inspecting goods at the end of the production process.

#### Description of data 
For this study, an anomaly detection dataset compiled by MVTec was used. In the dataset, there were 224 images of ‘normal’ optical fibre cables, and 92 images of cables that had visible anomalies. While the dataset used contained images of only optical fibre cables, the study applies to all standardised goods.

#### Skills
Python, Machine Learning, Deep Learning, Model Comparison and Evaluation, Report Writing

#### Results
To identify anomalies in a dataset of finished product images, developing a convolutional neural network based on VGG16 yielded the best results, with an F2 Score of 0.953.

---
