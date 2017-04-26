# UTD-Data-Visualization-Project
Analysis of Hospitals in United States for 2016
Source data files:
Primary Dataset: Hospital_General_Information 
Link: https://catalog.data.gov/dataset/hospital-general-information-15fcd

Description:
This file contains general information about all hospitals in the U.S. that have been registered with Medicare, including their addresses, type of hospital, and ownership structure. It also contains information about the quality of each hospital, in the form of an overall rating (1-5, where 5 is the best possible rating & 1 is the worst), and whether the hospital scored above, same as, or below the national average for a variety of measures.

Secondary Dataset: inpatientCharges
Link: https://www.kaggle.com/speedoheck/inpatient-hospital-charges

Description:
This dataset contains variation of hospital charges in the various hospitals in the U.S. for the top 100 diagnoses (DRG-Diagnosis Related Group). The U.S. government owns the dataset. It is freely available on data.gov. The dataset keeps getting updated periodically. This dataset will show you how price for the same diagnosis and the same treatment and in the same city can vary differently across different providers. It might help you or your loved one find a better hospital for your treatment. 


Data Retreival/Joining: I have combined both the datasets with the help of common key, provider Id using inner join in R
