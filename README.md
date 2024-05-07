# Education Inequality
DATA 3320 Project 2: Education Inequality

## Author:
Lauren Louie
https://www.linkedin.com/in/lauren-a-louie/

## Requirements:
Using Python through Google Colab to complete this project.

## License:
Anyone may use these resources in this repository and are allowed to use my findings and analysis for personal or professional projects.

## Description
The purpose of this project is to addresses inequality of educational opportunity in high schools in the United States. We will focus on average student performance on the ACT or SAT exams that students take as part of the college application process.

## Data
The project uses two data sets EdGap_data.xlsx and ccd_sch_029_1617_w_1a_11212017.csv. The primary data set is the EdGap data set from EdGap.org from 2016. It includes information about average ACT or SAT scores for schools and socioeconomic characteristics of the school district. The secondary data set is basic information about each school from the National Center for Education Statistics.

EdGap data:

This consists of all socioeconomic data such as household income, unemployment, adult educational attainment, and family structure taken from the Census Bureau’s American Community Survey. The EdGap.org report that includes ACT and SAT scores is from each state’s department of education or some other public data release. The nature of the other public data release is not known while the quality of the census data is assumed to be high. EdGap.org does not show that they processed the data in any way. This data was brought by the EdGap.org team, so there is possibility for human error. Due to the public nature of the data, we could consult the original data sources to check the quality of the data if we had any questions.

School information data:

The school information data is taken from the National Center for Education Statistics. It consists of basic identifying information about schools and can be assumed to be of high quality. Compared to the EdGap.org data, the school information data is public, so we can consult original data sources to check the quality of the data if we had any questions. The data set EdGap_data.xlsx can be accessed in this Github repository

The data set ccd_sch_029_1617_w_1a_11212017.csv is too large for Github and can be accessed from the google drive link:
https://drive.usercontent.google.com/u/0/uc?id=1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP&export=download

## Data Preparation:
The following actions were done to properly prepare the data for further analysis:
- Loaded each of the three data sets (EdGap, school_info, and census_df)
- Converted data types and dropped NaN values in the NCESSCH column of the school_info data set
- Renamed columns to make it more readable for the author and audience
- Selected relevant subsets of the data to only highlight the variables that would be beneficial for analyzing
- Joined dataframes together
- Underwent quality control to ensure we were only dealing with the necessary amount of data
- Created a relevant derived variable as a new column
- Identified missing values
- Split the data between training/testing
- Normalized the training/testing data
- Used data imputation method to replace missing values in the columns


