# Capstone_Project
### Optimizing The Business Processes of Retail and E-Commerce Platforms with Data Analytics and Machine Learning 

#### Improving techniques of conducting business with the help of data science tools and techniques like Market Basket Analysis, Customer Segmentation using RFM analysis and Clustering, Sales Forecasting to improve overall business to increase sales and profits.

#### The retail industry has drastically changed from brick-and-mortar stores to e-commerce and has overall increased in the previous decade as the advancement of technology never stopped. We can see the online presence of a small convenience store near our homes or big-size stores, on platforms like Google or social media with their dedicated sites for e-commerce. So, in the new tech world now the business owners have changed their techniques of conducting business with the help of digitalized tools and with the help of software like CRM where they can record data for billing, shipping, taxes, sales, inventory, and many more. As the current world thrives on data and almost every possible problem can be solved with data so with the help of data science business owners can make decisions and can predict their business for the near future with help of data science. It is not limited to decision making or predicting the outcomes in near future, but the data can also help us in recommending the product placement to increase sales and forecast their sales, inventory requirements, make informed marketing strategies, and many more. The data can help both the retail store and e-commerce to advance their business in numerous ways. Our multiple data-oriented insights and predictions will help the business owners in decision making and planning for their business.

#### Market Basket Analysis is to make a recommendation system for an e-commerce website and to help a retail store with its product placement to increase sales.

#### Customer Segmentation i.e., categorizing the customer based on RFM score to find loyal customers and to find the potential customers churn with the help of RFM Analysis. 

#### Sales Forecasting to understand the business direction. Inventory Management to stock freight in the future. 

#### Analytical Reporting to analyze business data with the help of business intelligence dashboards and visualizations to display the business's key performance indicators (KPIs), assess performance measures, and generate actionable insights.

### Steps for Running Python Notebook:

•	For running python file, you will need titanized_sales___profit_data.xlsx file. Keep this file in the same folder where you keep the python file otherwise you need to change to path location in the code where we are reading this file.

•	Our Excel file has four different sheets and has been explained  in below points.

•	Titanized Sales Data sheet is our raw data.

•	Customer ID sheet is created by us to assign the Customer ID to different Customers by using VLOOKUP function which was required for our analysis.

•	Product ID sheet is created by us to assign the Product ID to different Products by using VLOOKUP function which was required for our analysis.

•	Source & Credits sheet is the authority to use this data by Strategy Titan.

•	While Running RFM analysis part we have written one code for saving generated results to .CSV file which will be saved into your current python file running environment as rfm_365.csv but still for safe side we are attaching this file as well.

•	We have commented code for reading the file when running it in Google Colab if you wish to run python file in Google Colab you just need to uncomment them  and comment jupyter notebook reading file code before running it.

### Steps for Running Tableau File:

•	For running Tableau file, you will need titanized_sales___profit_data_tableau.xlsx  and rfm_365.csv files. Keep this file in the same folder where you keep the Tableau file.

•	Rfm_365.csv is extracted from the python notebook after performing customer segmentation using RFM analysis.

•	Basically, we have used 3 data sources two as mentioned in first point and third one is the joined file based upon these two files.

•	If it asks for rfm_365 then locate file source rfm_365.csv.

•	If it asks for titanized_sales___profit_data_tableau then locate file source titanized_sales___profit_data_tableau.xlsx. 

•	we have also created a join between these 2 files if it asks you to locate them again then please locate them once more.



