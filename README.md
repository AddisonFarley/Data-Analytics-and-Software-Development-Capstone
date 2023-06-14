# Data-Analytics-and-Software-Development-Capstone

Capstone project for the Data Analytics and Software Development, Associate of Applied Sciences degree from Green River College. This application runs a script every 24 hours that will pull relevant energy data from the Energy Information Administration (EIA) API, process and clean it, then will send it to a BigQuery database for storage.

Authors: Addison Farley, RJ Trenchard, Mason Sain, Will Castillo, Noah Lanctot

Version 1.0

A .env file is required in order for this script to run. 

Copy the below text, fill in the "xxx" as applicable, and save in the root directory as .env:
<br />
KEY_PATH = "xxx"<br />
API_KEY = "xxx"<br />
PROJECT_ID = "xxx"<br />
DATASET_ID = "xxx"<br />
TABLE_ID = "xxx"

Helpful links:
<br />
Google Cloud Authentication: https://cloud.google.com/bigquery/docs/authentication/service-account-file<br />
Google Cloud BigQuery Service Key JSON: https://console.cloud.google.com/iam-admin/serviceaccounts/<br />
EIA API Registration: https://www.eia.gov/opendata/

To run this application, you will need to have a Google Cloud account with BigQuery enabled. From Google Cloud, you need to create and download an account service key json (https://console.cloud.google.com/iam-admin/serviceaccounts/) and add that file to your program's root directory.

Once the .env file is updated and placed in the root directory, the program can be ran through main.py via a local machine or a hosted machine 24/7.

![System Diagram](https://github.com/AddisonFarley/SDEV-280-Capstone/assets/93640684/be911ae9-fa23-4860-b27a-48c698645905)
