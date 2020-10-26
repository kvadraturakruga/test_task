Notebook in Google Colab: https://colab.research.google.com/drive/1W58WVFX4GV8CEqQ2ZhdvKbTFJHCXhuOS?usp=sharing

Exploratory Data Analysis on public dataset from BigQuery Iowa Liquor Sales

1. Authorise after running the very first chapter
2. Replace "project_id" with your Project ID from your GCP console (https://console.cloud.google.com/)

%%bigquery --project project_id df
SELECT
*
FROM bigquery-public-data.iowa_liquor_sales.sales

3. Run cells 
