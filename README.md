# performance_analytics-PBI-Kimia-Farma
Big Data Analytics

# About Project and Program
<p align="justify">
This project was a final project in Project-Based Internship program by Rakamin Academy collaboration with Kimia Farma Big Data Analytics. It is a self-development and career acceleration initiative designed for those interested in pursuing the role of Big Data Analytics at Kimia Farma. This program provides foundational learning resources, including Article Reviews (reading materials) and Company Coaching Videos (learning videos), to introduce participants to the competencies and skills required for a Big Data Analytics professional in the company. In addition to the materials, participants will be evaluated weekly through task assignments and will complete a final task as a practice of doing Exploratory Data Analysis (EDA) and delivering the result in interactive dashboards (data visualization)
</p>

# Background Information
<p align="center">
  <img src="https://github.com/user-attachments/assets/ff0199ba-8528-4a16-b4d4-6ff76456a129" alt="logo-removebg-preview">
</p>
<p align="justify">
Kimia Farma is the first pharmaceutical company in Indonesia. Founded by the Dutch East Indies Government with initially named NV Chemicalien Handle Rathkamp & Co. It was nationalized in 1958 and renamed PNF Bhinneka Kimia Farma. The company transitioned to PT Kimia Farma (Persero) in 1971 and became a publicly listed company in 2001, establishing itself as an integrated healthcare provider contributing significantly to Indonesia's health sector.
In 2020, 90.025% of Kimia Farma's shares were transferred ownership to PT Bio Farma (Persero), forming the State-Owned Pharmaceutical Holding. Along with this restructuring, the company’s name changed to PT Kimia Farma Tbk. With decades of experience, Kimia Farma is a state-owned company (BUMN) member and continues to play a vital role in national health development.
</p>

# Content
<p align="justify">
As Big Data Analytics Interns at Kimia Farma, our role involves tackling various challenges that demand a deep understanding of data and strong analytical skills. One of the important projects will be evaluating Kimia Farma's business performance from 2020 to 2023 using data-driven insight.

### Dataset 📊
In this project, we are provided 4 CSV tables
- **kf_final_transaction.csv** : customer transaction details
- **kf_inventory.csv** : product inventory stocks
- **kf_kantor_cabang.csv** : branch store details
- **kf_product.csv** : product details

### Tools 🛠️
In this project, we will use several tools, including:
- **Google BigQuery**: for querying tables,
- **Google Looker Studio**: for creating visualization dashboards,
- **Google Drive**: for video presentations,
- **GitHub**: for storing query files and results,
- **Microsoft PowerPoint**: for presentation of our work
  
### Tasks 🎯
- In this project, we are given task to import the provided datasets (`Dataset.rar`) into tables in BigQuery. The table names should match the dataset names, excluding the ".csv" extension.
- we are also required to create an analysis table based on aggregated results from the previously imported tables. The following columns are mandatory for the analysis table:
  - `transaction_id`: transaction ID code,
  - `date`: the date the transaction occurred,
  - `branch_id`: Kimia Farma branch ID code,
  - `branch_name`: name of the Kimia Farma branch,
  - `kota`: city where the Kimia Farma branch is located,
  - `provinsi`: province where the Kimia Farma branch is located,
  - `rating_cabang`: customer rating for the Kimia Farma branch,
  - `customer_name`: name of the customer making the transaction,
  - `product_id`: code for the medicine product,
  - `product_name`: name of the medicine product,
  - `actual_price`: price of the medicine,
  - `discount_percentage`: discount percentage applied to the medicine,
  - `gross_profit_percentage`: gross profit percentage expected from the medicine based on the following conditions:
    - `Price` <= Rp 50,000 -> profit 10%
    - `Price` > Rp 50,000 - 100,000 -> profit 15%
    - `Price` > Rp 100,000 - 300,000 -> profit 20%
    - `Price` > Rp 300,000 - 500,000 -> profit 25%
    - `Price` > Rp 500,000 -> profit 30%,
   - `nett_sales`: price after the discount,
   - `nett_profit`: profit earned by Kimia Farma,
   - `rating_transaksi`: customer rating for the transaction.
- In this project, we are required to create a performance analysis dashboard for Kimia Farma from 2020-2023 in Google Looker Studio. This dashboard should be based on the analysis table you previously created in BigQuery, so you will need to connect that table to Google Looker Studio. You are free to design the dashboard according to your creativity, but it must include the following:
  - **Dashboard Title**
  - **Dashboard Summary**
  - **Filter Control**
  - **Data Snapshot**
  - **Comparison of Kimia Farma’s revenue year-over-year**
  - **Top 10 branches by total transactions in each province**
  - **Top 10 branches by net sales in each province**
  - **Top 5 branches with the highest ratings but lowest transaction ratings**
  - **Indonesia's Geo Map showing total profit by province**
  - **Additional analysis that we can explore**

### Results
#### BigQuery 📊 
The `Result.rar` file contains the following SQL and CSV files:
- **query_business_performance_analysis.sql**: [SQL BigQuery](https://console.cloud.google.com/bigquery?sq=29651332863:f780718709804c418e2d05bd9b8cb699)  
- **kf_business_performance_analysis.csv**: CSV file containing the result of the `kf_business_performance_analysis.csv` file 

#### Google Looker Studio : Dashboard 📈
link : [Google Looker Studio : Dashboard](link)
<p align="center">

</p>

#### Google Drive 🎥
[](link)


#### Microsoft Power Point 📝
file name : `FinalTask_KimiaFarma_BDA_Intan Auliya.pptx`

#### GitHub Repository 📁
Link : [performance_analytics-PBI-Kimia-Farma](https://github.com/intanauliya/performance_analytics-PBI-Kimia-Farma)


## Let's Connect! 🌐  
- [LinkedIn](https://www.linkedin.com/in//)
