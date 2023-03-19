## Data Cleaning: Inspecting, cleaning and transforming the FIFA 21 dataset
![](datacleaning.jpg)
Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset.
It is an important part of data analysis that allows data analsyst to have accurate, defensible data that generates reliable visualizations, models, and business decisions

## Introduction

This challenge was hosted by Promise Chinonso to enables participants learn how to clean data with any of the data cleaning tool.
The aim of this project is to exhibit my skills in cleaning/ transforming a rough FIFA 21 dataset and ready for analysis.


## Power Query concept applied

- Calculated columns
- Conditional columns
- Split columns
- Reordered columns and sort colums

## Problem Statement

- To clean, trim and change incorrect datatype to appropriate datatype
- To create conditional columns for appropriate columns
- To Replace or fill in missing values
- To remove/replace duplicate entries and null values


## Data Sourcing

This dataset was downloaded from kaggle website. It contains the details of football players alongside their performance, updated up till 2021 and there are 18979 rows and 77 columns present in the FIFA 21 data. see download link [here](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring)


## Data Transformation/ Cleaning

Data was efficiently cleaned and transformed with power query editor of Power BI. Some the steps taking in cleaning the dataset are:

### Making first row as header in the FIFA dataset table
 Promoting headers is making the top row of a table that acts as a title for the type of information they will find in each column. it makes the dataset more readable and easy to understand
 
 ### Formatting the dataset for better view
 Highlighted the whole dataset, go to the format tab the click on clean and trim to remove unwanted spaces
 Before Cleaning            |                   After Cleaning
 :-------------------------:|:--------------------------:
 ![](Beforecleaning.jpg)    |        ![](Aftercleaning.jpg)
 
 The dataset was downloaded unclean and not well formatted, i have to clean it for better view

### Changed Datatype
Some of the columns datatype were wrongly auto detected by power query which has to be changed to the appropriate datatype
Auto detected               |         Changed datatype
 :-------------------------:|:--------------------------:
 ![](unchangeddatatype.jpg) |  ![](changeddatatype.jpg)
 
 ### Create a conditional column 
 Created a conditional column to help separate data in values column for k & m as thousand and million
 ![]() 

