# Datasets

This folder contains two datasets, a dataset with medical diagnoses and a
dataset with mortality records. Both datasets are comma separated values (CSV)
files and utf-8 encoded. Below is a description given of both files and the
columns. DISCLAIMER: All data is FAKE data and is generated with the help of the Python
package [faker](https://github.com/joke2k/faker). So if you recognise anybody
in a record, it's not him or her...

## Mortality register dataset

The file ``mortality_register.csv`` contains (fake) data from a mortality
register. The file contains data about hundred deceased people. Each record
contains the information about one of them. The data includes the following
columns:

| Variable/Column| Description                                  |
|----------------|----------------------------------------------|
| patient_id     | A unique personal identifier                 |
| date_of_death  | The date (and time) of death of the deceased |
| place_of_death | The address of death                         |
| date_of_birth  | The date (and time) of birth                 |
| first_name     | The given name of the deceased               |
| last_name      | The last name of the deceased                |
| sex            | The sex of the deceased                      |

<!-- 
Variable, Description
patient_id, A unique personal identifier
date_of_death, The date (and time) of death 
place_of_death, The address of death
date_of_birth, The date (and time) of birth 
first_name, The given name of the deceased
last_name, The last name of the deceased
sex, The sex of the deceased
 -->

## Medical diagnosis records

The file ``hospital_data.csv`` contains information about diagnoses and
treatments in a bunch of hospitals. The diagnoses are classified with the 10th
revision of the International Statistical Classification of Diseases and
Related Health Problems (ICD-10). The file contains 800 records. Each record
represents one diagnosis and is assigned to a patient by using a unique
personal indentifier. The following variables are included:

| variable   | description                                  |
|------------|----------------------------------------------|
| patient_id | A unique personal identifier                 |
| ICD10      | The International Classification of Diseases |
| datetime   | The date and time of the diagnosis           |

<!-- 
Variable, Description
patient_id, A unique personal identifier
ICD10, The International Classification of Diseases
datetime, The date and time of the diagnosis
-->


