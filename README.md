# Crowdfunding_ETL
GWU Bootcamp Module 13 / Project 2

Submission Date - 02/01/2024

Project Participants - Andrew Jessberger, Bryan Johnson

Project Timeline - 
01/29/2024 - Downloaded starter files and began brainstorming best practices for achieving project goals.
01/30/2024 - Created derivative dataframes and populated with requested information, up to the initialization of the campaigning dataframe.
01/31/2024 - Continued dataframe creation to  completion and created necessary csv files.
02/01/2024 - Created schema template for SQL database, created crowdfunding database based on schema template, and read csv files into appropriate databases. Project Goals and process reviewed with instructor.

Coding Platforms: Visual Studio, pgAdmin

Coding Sources: Google Search, StackOverFlow, GWU Data Analytics Bootcamp Course Coursework

Project Summary - Receipt of an excel file (crowdfunding.xlsx) and framework python code. We created and transformed several derivative dataframes and csv files, based on this initial excel file, in order to meet project criteria. Several libraries were utilized to populate these dataframes such as regex, pandas, numpy (see ETL project code imports) and to create the customized/desired csv files (see resources folder for created csv files). At which point we intialized a SQL database (crowdfunding), based upon our ERD schema, to which were added several appropriate tables which were populated with the created csv files.

Project Notes - 
+When determining the lengths of the SQL fields, we determined the maximum value for the fields in question and then added roughly 25% to account for additional, larger entries.
+Initially we attempted to us a VS extension of postgres, however ultimately decided to utilize pdAdmin to create/manipulate the SQL databases due to our familiarity with the pgAdmin platform. 

