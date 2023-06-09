# Education Inequality: Predicting ACT Scores

## Description
This project will look at differenet socioeconomic factors and locations of different schools. We will be using an education data set to create a model that predict ACT scores from socioeconomic factors. There was a r squared analysis that was done that showed that the followiang three factors are the best at predicting the ACT score: percent of school on reduced lunch, rate of unemploymnet, and rate of percent college. The results showed that we were able to create a model that was realtively close in predicting average ACT scores compared to actual ACT scores. There was an additional step that was taken to analyze if there was a correlation between a state's political party afflilation to the  factors that we used for our model or the average act. There was no conclusion that was drawn from political party affliation.

## Data
There are two data sources for this project. The first is EdGap_data.xlxs which was obtained from the Github repository for DATA 3320 in the education folder (https://github.com/brian-fischer/DATA-3320/tree/main/education). This excel document contains information about schools, SAT Scores, marriage status and the income statu. The other is a CSV that was obtained from this dropbox: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0.
The data in this CSV file contains information about different schools, location of those schools and their peformance in school such as if they recieved offers for different schools. One data set is from the EdGap data set from EdGap.org. This data set includes data about ACT or SAT scores for schools and several socioeconomic characteristics, it is also from the year 2016. The other data set is information such as location and other factors about the school from the National Center for Education Statistic. The state political party data was created by Hope Crosier and Supreet Sandhu, we pulled data from the New York Times USA 2016 Election results article. (https://www.nytimes.com/elections/2016/results/president)

## Data Preparation
The data was prepared by combinding the data sets and removing data that was needed. The file that preps the data is called DATA_3320_Education_Inequality_Data_Preparation_.ipynb . The data was also cleaned by changing the column names to better suit the data. The data also had missing values, so to replace those missing values we used a train test split for the average ACT scores to ensure that the data was suitable to work with. Also, the data in the two data sets had different varaible types so we casted the data to be the same type. The data was cleaned and exported into a single excel file which is called: clean_education_inequality_data_prep (1).csv 

## Data Analysis
The data was utilized to create a prediction model for ACT scores from the socioeconomic factors. We examined the socioeconomic factors and there z scores, to create a model that best predicts the ACT  score. Our analysis determined that three factors that were percent college, rate of unemployment, and percent lunch were the best factors to use in order to predict the ACT score. We looked at the R squared values to determine if there was a correlation with the model that we created. We got an R squared value around 0.632 which shows there is a somewhat decent correlation with our model and the average act score. We also included another dataset that looked at the political party affliation of the state in 2016 election to determine if there was a correlation between political party and the average act.

## Author
The author of this notebook was Supreet Sandhu.
A link to her linkedIn: https://www.linkedin.com/in/supreet-sandhu/

## License
Members of the public are able to use and view the content of this project. They are able to use this notebook for their own work and education with citation given to the Author of this notebook.

