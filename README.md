# PyCity Schools Challenge

## Overview of Project
We were hired by the cheif data scientist, Maria, from a city school district to aid during the analysis on student funding and students' standardized test scores. We specifically worked with the students' math and reading scores and the schools involed in this district. During the analysis, we agregated the data to show trends in school perfomance. 

### Purpose
The purpose of this project is to help the school board make better, more informed decisions, regarding school budgets and priorities for budget allotments.

## Results
We found interesting results, which will be explained below.

How is the district summary affected?
Many things were taken into account for this analysis, inlcuding school names, types, total number of students per school, as well as students' information like their names, gender, grades and math and reading scores. After completing the analysis, we found that removing parts of the data significantly altered how well schools perfomed compared to each other. 
Before, the average math score was 79, average readin score was 81.9, the passing math percentage was 75%, the reading passing percentage was 86% and the overall passing percentage 65%.
<img width="468" alt="Old district summary" src="https://user-images.githubusercontent.com/88563922/137651457-21436339-0fc0-47fa-8d21-1272f527864f.PNG">


How is the school summary affected?
Replacing the ninth graders’ math and reading scores had a very important imapct on Thomas High School’s (THS) performance when compared to the rest of the schools. As you can see, THS had previous low scores: 66.91% math passing percentage, 69.66% reading passing percentage and a 65.07% overall passing percantage. 
<img width="502" alt="Old Complete DF" src="https://user-images.githubusercontent.com/88563922/137651462-2c0cca6a-56d7-42c6-b620-c3055169bdd8.PNG">


After removing the 9th graders' scores, these amounts changed drastically. As a result, THS's overll perfomance highly improved. New scores were as follows: 93.18% math passing percentage, 97.01% reading passing percentage and a 90.63% overall passing percantage. 
<img width="503" alt="THS Complete DF" src="https://user-images.githubusercontent.com/88563922/137651477-5d551c8a-6386-49c5-9304-b9f1f8aed98b.PNG">


Replacing the ninth-grade scores affect the following parameters:

Math and reading scores by grade
Before we took out the 9th grade reading scores, we could see every school which included grades from the 9th to the 12th grade. After the complete analysis, the dataframe included only 10th to 12th, where the Thomas High School under 9th grade showed nan instead of the previous 83.7 grade. The same can be seen on the math scores, the difference being that the old dataframe included the 9th grade, 83.6.

READING SCORES 
<img width="155" alt="Old Reading Scores by grade" src="https://user-images.githubusercontent.com/88563922/137651497-fe4bdbed-5a9b-4c60-8a91-dfe56f3ec42a.PNG">

<img width="152" alt="THS Reading Scores" src="https://user-images.githubusercontent.com/88563922/137651502-b1307628-3ae4-4d22-a656-5fcd71abb9a9.PNG">

MATH SCORES
<img width="154" alt="Old Math scores by grade" src="https://user-images.githubusercontent.com/88563922/137651543-9c67c01a-b69d-4e76-acd4-71ded0116ab6.PNG">

<img width="157" alt="THS Math Scores" src="https://user-images.githubusercontent.com/88563922/137651548-ebfe3807-f1fd-4d72-8ede-a9edd4250150.PNG">


Scores by school spending
Removing the 9th grade scores out of the Thomas High School did not affect this parameter. As you can see below, dataframes show the same information.
<img width="417" alt="Old Spending per Student" src="https://user-images.githubusercontent.com/88563922/137651560-c05bc4bd-899f-44ec-8b96-a7fee0ade57b.PNG">

<img width="538" alt="THS Spending Ranges (per student)" src="https://user-images.githubusercontent.com/88563922/137651576-44cfe6dd-26b2-497d-8faa-c759ff48159d.PNG">


Scores by school size
Removing the 9th grade scores out of the Thomas High School did not affect this parameter. As you can see below, dataframes show the same information.

<img width="377" alt="Old School Size" src="https://user-images.githubusercontent.com/88563922/137651581-cf284dbb-f36f-42ce-8796-ae4ae6d43b4b.PNG">

<img width="515" alt="THS School Size" src="https://user-images.githubusercontent.com/88563922/137651592-a620bde4-8f98-47fd-8336-a7f0db86fdad.PNG">


Scores by school type
Removing the 9th grade scores out of the Thomas High School did not affect this parameter. As you can see below, dataframes show the same information.

<img width="378" alt="Old School Type" src="https://user-images.githubusercontent.com/88563922/137651604-78b409a1-74c8-4f68-9b01-c93503e6d4aa.PNG">

<img width="481" alt="THS School Type" src="https://user-images.githubusercontent.com/88563922/137651610-745080c8-d259-4d52-ae72-d6bdb389cb4c.PNG">
