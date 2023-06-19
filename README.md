# Uber-Data-Analysis-  Data Engineering Project in GCP

**Introduction**
This project involves performing data analytics on Uber data using various technologies such as Python, Google Cloud Platform (GCP), GCP Storage, Compute Instance, BigQuery, Looker Studio, and a Modern Data Pipeline Tool called Mage. The project comes from a data analytics youtube tutorial. 

**Tools**  
Google Cloud Storage 
Compute Instance
BigQuery
Looker Studio
Mage Data Pipeline Tool

**Architecture**

![image](https://github.com/Kennethlhy/Uber-Data-Analysis-/assets/118910691/4efb7469-e05a-4176-b66d-1ee53be70e3a)

**Dataset**

The dataset used in the project is the TLC Trip Record Data for yellow and green taxi trips in Mar 2016, which includes fields such as pick-up and drop-off dates/times, locations, distances, fares, and more.
Dataset https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

**Data Model**

Include one fact table and others dimension tables
![image](https://github.com/Kennethlhy/Uber-Data-Analysis-/assets/118910691/bdc73a7c-3d5e-4b54-9346-9078863f0e0f)


**Data dictionary**

Please see in https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

**Challenge**
1. Mage AI faces open too much files error and shut down when opertaing in vm. Solution: open a new vm in GCP wtih more memory and CPUs so that it can have memory to open files




