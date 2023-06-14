# Data-Analytics-and-Software-Development-Capstone

Capstone project for the Data Analytics and Software Development, Associate of Applied Sciences degree from Green River College.

Authors: Addison Farley, RJ Trenchard, Mason Sain, Will Castillo, Noah Lanctot

Version 1.0

This application runs a script every 24 hours that will pull relevant energy data from the Energy Information Administration (EIA) API, process and clean it, then will send it to a BigQuery database for storage.

A .env file is required in order for this script to run. 

Copy the below text, fill in the 'xxx' as applicable, and save in the root directory as .env:
# for help: https://cloud.google.com/bigquery/docs/authentication/service-account-file
KEY_PATH = "xxx"
# for help: https://www.eia.gov/opendata/
API_KEY = "xxx"
# name of the BigQuery project
PROJECT_ID = "xxx"
# name for the project's dataset
DATASET_ID = "xxx"
# name for the dataset's table
TABLE_ID = "xxx"

**Notice**
In order for you to have a valid key path, you will need a Google Cloud service key json in your root directory. If you do not know how to get this, follow the guide linked above the KEY_PATH .env variable.

To run this file, you will need to have a Google Cloud account with BigQuery enabled. From Google Cloud, you need to create and download an account service key json (https://console.cloud.google.com/iam-admin/serviceaccounts/) and add that file to your program's root directory.

Once the .env file is updated and placed in the root directory, this entire program can be ran via a local machine or a hosted machine 24/7 through main.py.

![System Diagram](https://github.com/AddisonFarley/SDEV-280-Capstone/assets/93640684/be911ae9-fa23-4860-b27a-48c698645905)
