# Data-Analytics-and-Software-Development-Capstone

Capstone project for the Data Analytics and Software Development, Associate of Applied Sciences degree from Green River College.

Authors: Addison Farley, RJ Trenchard, Mason Sain, Will Castillo, Noah Lanctot

Version 1.0

This application runs a script every 24 hours that will pull relevant energy data from the Energy Information Administration (EIA) API, process and clean it, then will send it to a BigQuery database for storage.

To run this file, you will need to have a Google Cloud account with BigQuery enabled. From Google Cloud, you need to create and download an account service key json (https://console.cloud.google.com/iam-admin/serviceaccounts/) and add that file to your program's directory. Once done, update the filepath and commented fields in the solv4solvx.py file. Once finished, the script will pull 2 days worth of energy data for the PNW area and upload it to your desired SQL database in BigQuery every 24 hours.


![System Diagram](https://github.com/AddisonFarley/SDEV-280-Capstone/assets/93640684/be911ae9-fa23-4860-b27a-48c698645905)

