# BigQuery-Projects
### Project 5: Data Preparation for BI Reporting using Google BigQuery

In this project, I practiced writing SQL queries in BigQuery using the free Google Analytics 4 (GA4) dataset. My focus was on analyzing eCommerce funnel progression.

[View Project on Google BigQuery if you have an account](https://console.cloud.google.com/bigquery?sq=450854397335:f6e0ae0e1322400e8f236a08a46514af)

[View BigQuery SQL as download file](https://github.com/shvetsihorr/SQL-Projects/blob/fc38bb18e8db4a3c14e7cd1e6501e5c08fabd5ee/BigQuery%20Data%20Preparation%20for%20BI%20Reporting%20using%20Google%20BigQuery.sql)

<img width="1464" alt=" Data Preparation for BI Reporting using Google BigQuery" src="https://github.com/user-attachments/assets/1f2e7b65-508b-488c-b676-308f1ec851a2">


### Project 6: Conversion Calculation by Date and Traffic Channel using Google BigQuery

For this task, I created a query to calculate conversions from session start to purchase, segmented by date and traffic channel.

Note: The query considered both session and user IDs to ensure accurate counts of unique sessions by unique users, as different users might have the same session IDs.

This analysis provided insights into how conversions progress through different stages of the user journey, segmented by date and traffic channel.

[View Project on Google BigQuery if you have an account](https://console.cloud.google.com/bigquery?sq=450854397335:1ad7f81432424c209dcf7e359b8c61b4)

[View BigQuery SQL as download file](https://github.com/shvetsihorr/SQL-Projects/blob/fa9fb14e9c05db5a098d7b09e855c01072a30b78/BigQuery%20-Conversion%20Calculation%20by%20Date%20and%20Traffic%20Channel%20using%20Google.sql)

<img width="1470" alt="Conversion Calculation by Date and Traffic Channel" src="https://github.com/user-attachments/assets/d95a81df-55cd-4664-9162-2b9184ebee2c">

### Project 7. Comparison of Conversion Rates Between Different Landing Pages using Google BigQuery

For this task, I analyzed conversion rates across different landing pages.
Objective: I created a query to extract the page_path from the page_location in session start events for the year 2020. For each unique landing page, I calculated:

- The number of unique sessions by unique users.
- The number of purchases.
- The conversion rate from session start to purchase.

Note: Since session start and purchase events may have different URLs, I merged these events using user and session identifiers to ensure accurate conversion tracking.

This analysis provided insights into how different landing pages perform in terms of driving conversions.

[View Project on Google BigQuery if you have an account](https://console.cloud.google.com/bigquery?sq=450854397335:1d00f422ab3e4b49979d80373f5f2a13)

[View BigQuery SQL as download file](https://github.com/shvetsihorr/SQL-Projects/blob/88569480d9cc22fac289a54a948f9926570c6e37/BigQuery%20Comparison%20of%20Conversion%20Rates%20Between%20Different%20Landing%20Pages.sql)

<img width="1385" alt="Comparison of Conversion Rates Between Different Landing Pages" src="https://github.com/user-attachments/assets/2a35c45a-9039-493f-a4c0-b0fe6e68dcbf">

### Project 8. Correlation Analysis Between User Engagement and Purchases using Google BigQuery

For this task, I assessed the correlation between user engagement and purchase behavior. I determined for each unique session:
- Whether the user was engaged (if session_engaged parameter equals ‘1’).
- The total engagement time during the session (sum of engagement_time_msec across events).
- Whether a purchase occurred during the session.

I then calculated the correlation coefficients:

- Between user engagement and purchase occurrence.
- Between total engagement time and purchase occurrence.

I merged session start events with other session events using user and session identifiers to ensure accurate correlation analysis.

[View Project on Google BigQuery if you have an account](https://console.cloud.google.com/bigquery?sq=450854397335:307578fcb5cf4a2e948e76f160aa3215)

[View BigQuery SQL as download file](https://github.com/shvetsihorr/SQL-Projects/blob/1edaa46ff6e6e641ed3154a2673ca337ec639227/Correlation%20Analysis%20Between%20User%20Engagement%20and%20Purchases%20using%20Google%20BigQuery.sql)

<img width="1355" alt="Correlation Analysis Between User Engagement and Purchases" src="https://github.com/user-attachments/assets/ee52b29a-cd4a-4dcd-9f09-e93899114659">
