# MasterMatch

## OBJECTIVES

The main objective of this project is to allow prospective master's students (users) to filter and select a master's program according to their preferences. 

In order to accomplish this objective, the following data source will be used:
- A dataset containing 60442 different master's degree programs from 99 countries around the world. Each program has specified requirements which users will be able to filter through.  The data is originally from mastersportal.eu, however the scrapped and final version is from Kaggle (see bibliography).  

## DATA DESCRIPTION

### _Data on Worldwide Master's Programs _

This repository contains a comprehensive dataset of 60,442 master's degree programs from 99 countries around the world. The dataset provides a rich variety of information on each program, making it a valuable resource for anyone interested in higher education research, academic advising, and international education policy.

The dataset is composed of 23 columns, providing detailed information about each program:

- **country_name**: The name of the country where the university is located.
- **country_code**: The ISO country code corresponding to country_name.
- **university_name**: The name of the university offering the master's program.
- **university_rank**: The global ranking of the university.
- **program_name**: The name of the master's program.
- **program_type**: The type or field of the master's program.
- **deadline**: The application deadline for the program.
- **duration**: The duration of the program, typically in years or semesters.
- **language**: The language of instruction in the program.
- **tution_1_currency**: The currency of the first tuition fee listed.
- **tution_1_money**: The amount of the first tuition fee listed.
- **tution_1_type**: The type of the first tuition fee (e.g., per semester, per year, total).
- **tution_2_currency**: The currency of the second tuition fee listed, if applicable.
- **tution_2_money**: The amount of the second tuition fee listed, if applicable.
- **tution_2_type**: The type of the tuition payment (e.g., national, international, EU/EEA etc.), if applicable.
- **tuition_price_specification**: Additional specifications about the tuition price.
- **start_date**: The start date of the program.
- **ielts_score**: The minimum IELTS score required for the program, if any.
- **structure**: The structure of the program.
- **academic_req**: Academic requirements for admission to the program.
- **facts**: Additional facts or notes about the program.
- **city**: The city where the university is located.
- **program_url**: The URL of the program's webpage.

Please note that some columns may contain null or missing values, depending on the specific program or university. This is a result of the diverse and international nature of the dataset. Therefore, pay close attention to the instructions in the 'CODE DESCRIPTION' section below. 

## PROJECT DESCRIPTION

MasterMatch is a platform that aims to simplify the process of searching and selecting Master's programs for prospective students globally. This web application provides a user-friendly interface that allows students to filter through a vast array of Master's programs based on their interests and requirements, enabling them to efficiently extract and filter information that matters most to them.
The application's primary objective is to provide a comprehensive and straightforward platform for prospective students to search, compare and contrast a broad base of Master's programs, thereby empowering them to make informed decisions when selecting the program that best suits their needs and aspirations.

## CODE DESCRIPTION 

In order to run the final MasterMatch program, you are only required to download one single .ipynb file in order to run it called 'MasterMatch'. 

To execute the code it will be necessary to have Jupyter Notebooks or Google Collaboratory. The MasterMatch project was developed in Google Collaboratory. To run the program, execute the following script and follow the specified instructions: 

### '_MasterMatch_'

Having realised our project in one single .ipynb file, in  order to use it, you must simply download this file. Before running it, it is additionally necessary to download the dataset provided in the 'Data' folder above, and load it in the appropriate manner to your python interpreter (or google colab). In the .ipynb file we provided, the first few lines of code are dedicated to mounting the google drive and reading the csv from there. It is essential to adapt this section, as the location of the downloaded csv dataset will be a different one on your device, most likely not on google drive, except for if you upload it to your drive beforehand. Hence, please adapt the input for the read_csv command accordingly to where your dataset is stored. Additionally, ensure you run the 'CLEANING THE DATA' section in the python script before running the program to avoid crashes due to NA values. 

Regarding necessary packages, those are the packages used that must be installed to run the program:
- pandas
- numpy 
- Textwrap

Lastly, to run the program, you should make sure that the condition __name__ == "__main__" holds true in order for the algorithm to execute when running the file. Alternatively, you may run main() separately. The algorithm should now execute. 

## FINAL REPORT

In the folder 'Final Report', you will be able to find the Final Report on the MasterMatch program development which details the development of the startup from the inception till the final stages of development along with user testing, conclusions and next steps. The document is called 'Final Report'.


## BIBLIOGRAPHY

Master's Programs Dataset: https://www.kaggle.com/datasets/anasfullstack/mastersportal-programs






