# Amazon_Vine_Analysis

## Overview
The purpose of this project is to understand what constitutes big data and the common operation with the data set.  The initial ETL portion of the project was performed using AWS, PostgreSQL, and PySpark in Google Colab as specified. The data analysis part was performed using PySpark and Google Colab. The subject I choose is Musical Instruments, assuming these products have fewer customers base and the data set size will be smaller, so easier to load, read and write.


Here is the overview of the data frame:

![This is an image](https://github.com/Sirius0531/Amazon_Vine_Analysis/blob/main/resources/full%20table.PNG)

Amazon reviews written by members of the paid Amazon Vine program we're going to analyze.

![This is an image](https://github.com/Sirius0531/Amazon_Vine_Analysis/blob/main/resources/vine.PNG)

Regular (non-view review)

![This is an image](https://github.com/Sirius0531/Amazon_Vine_Analysis/blob/main/resources/regular.PNG)
 
 Filter the dataset by below criteria to make sure the review is valid:

**Count of Total Votes equal or greater than 20.
Percent of Helpful Votes to Total Votes equal or greater than 50%.**

![This is an image](https://github.com/Sirius0531/Amazon_Vine_Analysis/blob/main/resources/helpful%20rate.PNG)

![This is an image](https://github.com/Sirius0531/Amazon_Vine_Analysis/blob/main/resources/total%20vote.PNG)

The goal is to determine whether there is bias in the positive reviews of Vine members in the dataset and whether paid Vine reviews affect the percentage of 5-start reviews.
![This is an image](https://github.com/Sirius0531/Amazon_Vine_Analysis/blob/main/resources/vine%20vs%20regular.PNG)

We have total of **60 vine reviews** and **14,477 regular customer reviews**.
As the result, vine reviews and regular customer reviews have very close 5 start rate (56.6% & 56.7%). In the catogory of musical instrument, the result describes there are not much of bias for reviews in the Vine program.
