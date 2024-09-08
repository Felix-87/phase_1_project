<p align="center">
  
  ![detail-ifc-01](https://github.com/user-attachments/assets/8dfffb06-3fa7-4432-afcb-a8db6edba756)


# Overview
This project explores the criteria to be adpoted when making a decision on the Make and Purpose of aircraft to purchase and operate for either business or private enterprises given aviation accidents dataset. Best choice is one that possesses aggregate lowest risk in terms of Asst risk(Damage degree on aicraft) and User Related Risk(Severity of injury).
Based on the analysis AviationData.csv, Cessna Make of aircraft has the lowest aggregate risk.

# Business Understanding
My company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. I am charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. I must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.
## Key business questions
1.Which aircrafts are operated for business or private enterprises?

2.Which aircrafts lowest asset risk? This is the potential loss of aircraft in the event of an accident?

3.Which aircraft posses lowest risk to users(crew and passengers) in the event of ana accident?

4.Which aircraft has a combination of lowest risk category on asset risk and user risk?

# Data Understanding and Analysis

## Source of data

Aviation accidents dataset; AviationData.csv. https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

## Description of data
Imported relevant python libraries and loaded data using pandas for preparation.
 import pandas as pd
 import numpy as np
### Loading data
 Loaded data using pandas; pd.read_csv('AviationData.csv') to load and convert to a dataframe.
 data1 = pd.read_csv('AviationData.csv', encoding= 'ISO 8859-1')

### Data cleaning
This is the process of checking for validity, completeness,accuracy, consistency and uniformity of data. The cleaned data is saved in a .csv file
clean_df1.to_csv('clean_aviation_data.csv', index=False)

## Visualizations

![image](https://github.com/user-attachments/assets/04dc6e82-2ed2-4334-9bcd-0706a76ce0a5)


![image](https://github.com/user-attachments/assets/7e445e81-b121-419d-9347-3579b8517c64)


![image](https://github.com/user-attachments/assets/31b749e9-0dcd-437d-9a08-4958743aef22)


# Conclusion


This analysis relied on AviationData.csv dataset provided and following the criteria set to achieve the research objective.

Critical variables include; Injury_Severity, Aircraft_Damage, Make, Purpose_Of_Flight and Total_Uninjured to select the aircraft with the lowest risk.

Cessna Make of aicrafts showed to posses lowest risks. 

Cessna aircrafts operated for private(personal) enterprises appeared to have lower risks than those operated for business enterprises.

## Summary of conclusions including three relevant findings

1. Aircrafts for personal purpose has the highest frequency. This implies that low risk aircrafts are majorly operated for private enterprises than for business enterprises. 
 
2. The interpretation of the above visual is that; those aircrafts with low risk are majorly operated for personal(private) enterprises. Cessna aircrafts has the highest frequency for personal purpose whereas Piper aircrafts have the highest frequency in business purpose.

3. Cessna make appears to be of a lowest risk aircraft. This can be extracted to show which purpose (business or personal) has the lowest risk.





