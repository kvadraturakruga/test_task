Exploratory Data Analysis on public dataset from BigQuery Iowa Liquor Sales

1. Authorise after running the very first chepter
2. Replace "project_id" with your Project ID from your GCP console (https://console.cloud.google.com/)

%%bigquery --project project_id df
SELECT
*
FROM bigquery-public-data.iowa_liquor_sales.sales

3. Run cells 