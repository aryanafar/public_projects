# SQL_food_sales_analytics_projects
This is an individual SQL-based project involving food sales analytics from parsing JSON files. I created, lodaded, and staged tables, and validated, cleansed, and preliminarily analyzed the data. After this analysis, I answered the question of whether or not to withold customer data from 3rd party sales channels.

## nb_1_create_load_prod_mapping.ipynb
This notebook contains the process for creating and loading the product mapping table.

## nb_2_parse_peak_sales_json.ipynb
This notebook contains the process for parsing the peak sales json.

## nb_3_create_load_staging.ipynb
This notebook contains the process for creating and loading the staging tables.

## nb_4_validate_staging.ipynb
This notebook contains the process for validating all of the datatypes and values of the staging tables.

## nb_5_cleansing_customer_data.ipynb
This notebook contains the process for cleansing the customer data.

## nb_6_prelim_analytics.ipynb
This notebook contains the process for preliminary SQL analytics on the data.

## nb_7_to_withold_or_not.ipynb
This notebook contains the written argument for witholding or not witholding data from 3rd party sales channels.

## peak_product_mapping.csv
This CSV maps the relationship between the Peak product ID and the AGM product ID.

## peak_sales_2020_10_03.json
This is a nested JSON of the sales, parsed into individual CSV's in nb_2_parse_peak_sales_json.ipynb.