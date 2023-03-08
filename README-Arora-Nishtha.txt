Objective: Data de-identification and modification

About the project: The purpose of the project is to de-identify and modify the 'Covid-19' data. This project is completed by the students of 'Masters of Business Analytics'(Monash University, Clayton) as a part of 'Assignment 3' semester 1 assessment for ETC5512 (Wild-caught data) curricula.

As we know, Covid-19 has had a significant impact on the fiscal, home and work experiences of Melbourne residents during 2020. Data has been collected to measure this impact with regards to mental health, financial stability and home life. The data focuses on 2019 and 2020 statistics.

Data source: 

The orignal data is a hypothetical example of of data that might have been collected during the period of January 2021 for 1000 Melbourne residents in a way explained below.

Collection of data via an online survey in January 2021 for 1000 Melbourne residents via a platform called Qualtrics.

For completion of survey, mailed invites used and QR code scanned. 

The questionnaire of the survey consists of the participant's identity questions and also, questions related to their mental health, financial stability and home life.

Files necessary to read data:

1. release-data-Arora-Nishtha.csv: This is the final release data file in 'Comma-separated values' (.csv) format. This file contains all the observations necessary to measure the impact of Covid-19 for Melbourne residents during 2020, concerning mental health, financial stability and home life.

The dimension for this data set is 1000 rows and 42 columns. Here, all the variables are in the correct data type and are de-identified.

2. data-dictionary-Arora-Nishtha.csv: This is the codebook for the above data file (release-data-Arora-Nishtha.csv). This codebook is also in the .csv format which is an appropriate type here. 

The file consists of all variable names with their description/original-question in the released data, item-specific information i.e. if the variable is directly taken from the original raw data or has been derived after certain changes, labels for factorial data and their levels and count for each level of every variable that has a specified value in the data set(not range of values e.g. income variables).

Therefore, this codebook is a guidebook to read the 'release-data-Arora-Nishtha.csv' file with ease and efficiency.

3. data-dictionary-Arora-Nishtha.xlsx: This is similar to file no. 2 (mentioned above) with similar features and uses. But this is an extra file which is in 'Excel Microsoft Office Open XML Format Spreadsheet file' (.xlsx) format.

Although this file, is not necessary and not in the correct format for this particular project, but has been kept along with the other data files only for safety. i.e. incase of any issue that might occur while opening file no.2, then this file would act as a safety net and would help in reading file no. 1 efficiently.


Calculation demonstration (example): 

Question: To find out the difference in the number of people with 'Good' mental health in 2019 and 2020.

Answer: (after calculations from data)
        Count of people with 'Good' mental health in 2019: 485
        Count of people with 'Good' mental health in 2020: 357
        
        Difference: 485- 357 = 128
        
There has been a decline in people with 'Good' Mental health. Therefore, a negative impact of Covid-19 on mental health for the residents of Melbourne.
        

Software used:
R version 4.0.5

Author:
Name: Nishtha Arora
Student ID: 32296622
Email ID: naro0004@student.monash.edu

This project was completed under the guidance of the Faculty of Department of Econometrics and Business Statistics, Monash University, Clayton.