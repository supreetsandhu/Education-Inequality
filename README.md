# Education-Inequality

## Description
This project will look at differenet socioeconomic factors and locations of different schools. We will be using two different datasets to anaylsis how the peformance of different schools and how students at the school peform and how that relates to various socioeconomic factors. 

## Data
There are two data sources for this project. The first is EdGap_data.xlxs which was obtained from the Github repository for DATA 3320 in the education folder (https://github.com/brian-fischer/DATA-3320/tree/main/education). This excel document contains information about schools, SAT Scores, marriage status and the income statu. The other is a CSV that was obtained from this dropbox: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0.
The data in this CSV file contains information about different schools, location of those schools and their peformance in school such as if they recieved offers for different schools. One data set is from the EdGap data set from EdGap.org. This data set includes data about ACT or SAT scores for schools and several socioeconomic characteristics, it is also from the year 2016. The other data set is information such as location and other factors about the school from the National Center for Education Statistic.

## Data Preparation
The data was prepared by combinding the data sets and removing data that was needed. The file that preps the data is called DATA_3320_Education_Inequality_Data_Preparation_.ipynb . The data was also cleaned by changing the column names to better suit the data. The data also had missing values, so to replace those missing values we used a train test split for the average ACT scores to ensure that the data was suitable to work with. Also, the data in the two data sets had different varaible types so we casted the data to be the same type. The data was cleaned and exported into a single excel file which is called: clean_education_inequality_data_prep (1).csv 
