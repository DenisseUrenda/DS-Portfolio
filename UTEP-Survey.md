# The survey

The University of Texas at El Paso (UTEP) has been collecting data on food and housing security of UTEP students since 2019 and continuous to this day. The data has been collected through a survey containing the questions presented in the table.

|Variable             |Meaning                                                             |Notes                                                                         |
|:--------------------|:-------------------------------------------------------------------|:-----------------------------------------------------------------------------|
|Enroll               |Enrollment type at UTEP                                             |1-‘Full-time’;  2-‘Part-time’                                                 |
|Employ               |Are you employed?                                                   |1-‘Full-time’; 2-‘Part-time’; 3-‘No’                                          |
|Working              |Job on/off campus                                                   |1-‘On campus’; 2-‘Off campus’; 3-‘Both’                                       | 
|Hrs                  |Weekly hours worked                                                 |1-’19 hours or less’; 2-‘More than 19 hours’                                  |
|Ethnicity            |What is your ethnicity?                                             |1-‘Hispanic’; 2-‘American Indian/Alaska native’; 3-‘Asian’; 4-‘African American’; 5-‘Native Hawaiian’; 5-‘White/Caucasian’; 6-‘Other’; 7-‘Prefer not to say’ |                                                                                      |Income               |2022 household income                                               |1-‘Less than $10,000’; 2-‘$10,000 to $19,999’; 3-‘$20,000 to $29,999; 4-‘$30,000 to $39,999’; 5-‘$40,000 to $49,999’; 6-‘$50,000 to $59,999’; 7-‘$60,000 to $69,999’; 8-‘$70,000 to $79,999’; 9-‘$80,000 to $89,999’; 10-‘$90,000 to $99,999’; 11-‘$100,000 or more’|
|Classification       |Academic level                                                      |1-‘Freshman’; 2-‘Sophomore’; 3-‘Junior’; 4-‘Senior’; 5-‘Graduate (Masters)’; 6-‘Doctoral’; 7-‘Special: Professional (Certificate Program)’|
|College              |Which college are you a student of?                                 |1-‘Business’; 2-‘Education’; 3-‘Engineering’; 4-‘Liberal Arts’; 5-‘Health Sciences’; 6-‘Nursing’; 7-‘Science’; 8-‘Pharmacy’; 9-‘Other’ |
|Commute              |Way of transportation to school                                     |1-‘Car (alone)’; 2-‘Car (someone drives to campus and picks you up)’; 3-‘Carpool’; 4-‘Bus/Public transportation’; 5-‘Bike’; 6-‘Trolley’; 7-‘Walk’; 8-‘Uber/Lyft’; 9-‘Other’; 10-‘Not applicable’|
|Alone                |Do you live alone?                                                  |1-‘Yes’; 2-‘No’                                                               |
|Dependents           |Number of dependents                                                |1-‘None’; 2-‘1’; 3-‘2’; 4-‘3’                                                 |
|HoH                  |Head of household                                                   |1-‘Yes'; 2-‘No’                                                               |
|Live                 |Current housing situation                                           |1-‘On campus’; 2-‘Off campus with family’; 3-‘Off campus not with family’; 4-‘Other’; 5-‘Off campus with parents’; 6-‘Off campus with partner’; 7-‘Off campus with partner and kids’                                                                 |
|FedAid               |Federal Student Aid in the past 12 months                           |1-‘Grants’; 2-‘Work-study’; 3-‘Loans’; 4-‘Scholarship’; 5-‘Emergency Loan’; 6-‘UTEP’s COVID CARES Act Fund’; 7-‘Other’; 8-‘None’                                                                                                                      |
|PA                   |Permanent address in the past 12 months                             |1-‘Yes'; 2-‘No'                                                               |
|FreqNightElse        |Frequency spending nights elsewhere due to lack of PA               |1-‘Often’, 2-‘Sometimes’; 3-‘Rarely’                                          |
|UTEPHomeless         |Do you know any students experiencing homelessness?                 |1-‘Yes’; 2-‘No’                                                               |
|Year                 |Year of collecting the data                                         |1-‘2019’; 2-‘2020’; 3-‘2021’; 4-‘2022’                                        |
|HH3                  |The food did’t last and there were no more money left for more food |1-‘True’; 0-‘False’                                                           |
|HH4                  |Couldn’t afford balanced meals                                      |1-‘True’; 0-‘False’                                                           |
|AD1                  |Cut size or skip meals because of lack of money                     |1-‘True’; 0-‘False’                                                           |
|AD1a                 |How often did AD1 happen?                                           |1-‘Almost every month/Some months’; 0-‘Only 1 or 2 months’                    |
|AD2                  |Eat less because of lack of money                                   |1-‘True’; 0-‘False’                                                           |
|AD3                  |Hungry but didn’t eat because of lack of money                      |1-‘True’; 0-’False’                                                           |
|Index                |Food security stats/score                                           |0,1,2,3,4,5,6                                                                 |
|Gender               |Gender you identify with                                            |1-‘Female’; 2-‘Male’; 3-‘Transgender’; 4-‘Gender variant’; 5-‘Other’; 6-‘Prefer not to say’                                                                                                                                                               |
|USDAcat              |Calculated Food Security levels                                     |If Index is 0 or 1 then USDAcat-‘Marginal/High FS’; If Index is between 2 and 4 then USDAcat-‘Low FS’; If Index is 5 or 6 then USDAcat-‘Very Low FS’                                                                                                            |
|YR_2019:YR_2022      |Specific year; 4 separated columns                                  |1-‘No’; 2-‘Yes’                                                               |
|Ethn_Hisp:Ethn_Other |Specific ethnicity; 7 separated columns                             |1-‘No’; 2-‘Yes’                                                               |
|Coll_BSN:Coll_NA     |Specific college; 10 separated columns                              |1-‘No’; 2-‘Yes'                                                               |

Extra questions have heen also supplied in a separate dataset with the following variable/questions.

|Variable             |Meaning                                                                                                 |Notes                                                                                                             |
|:--------------------|:-------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------|
|PermAdd              |Permanent address in the past 12 months                                                                 |1-'Yes'; 2-'No'                                                                                                   |
|GovAss               |Govermental or organization assistance                                                                  |List separated by space with all different types of assistance a student got                                      |
|AvailRes             |Available resources at UTEP based on the students' knowledge                                            |List separated by space with all different types of resources a student knows                                     |
|MoreAvailRes         |Which of the previous resources should be offered more?                                                 |List separated by space with all different types of resources a student thinks should be offered more             |
|DiffLvlFA            |Level of difficulty to receive food assistence at UTEP                                                  |1-'Very difficult'; 2-'Moderately difficult'; 3-'A little difficult'; 4-'Not difficult at all'; 5-'I am not sure' |
|ChallFA              |Main challenges with getting food assitence at UTEP                                                     |List separated by space with all different types of challenges                                                    |
|EmergFood            |Where did you get emergency food from?                                                                  |List separated by space with all different types of locations they received emergency food                        |
|DiffConcentrate      |How ofthen did you have difficulties concentrating at school because of food, rent or other neccesities |1-'Almost every day', 2-'About once a week'; 3-'About once a month'; 4-'Never'                                    |
|DelayComplDegree     |Did you had to delay the completion of your degree because of money for food, rent etc?                 |1-'Yes, by 2 sememsters or more'; 2-'Yes, by 1 semester'; 3-'No'                                                  |
|TimeDelayComplDegree |How ofthen do you think about delaying completion of degree because of lack of money for food etc?      |1-'Often'; 2'Sometimes';3-'Never'                                                                                 |
|RateMentalHealth     |Rate your mental health (mood and ability to think)                                                     |1-'Excellent';2-'Very Good'; 3-'Good';4-'Fair'; 5-'Poor'                                                          |
|AttendProtest        |How often did you attend a protest or rally in the last 12 months?                                      |1-'Never';2-'Once';3-'A few times'; 4-'Several times'; 5-'A lot'                                                  |
|AttendLocalComm      |How often did you attend a a meeting about an issue in your community or school in the last 12 months?  |1-'Never';2-'Once';3-'A few times'; 4-'Several times'; 5-'A lot'                                                  |
|PoliticMess          |How often did you wrote or posted political messages online in the last 12 months?                      |1-'Never';2-'Once';3-'A few times'; 4-'Several times'; 5-'A lot'                                                  |
|CompValues           |How often did you bought or avoided a product because of the company's values in the last 12 months?    |1-'Never';2-'Once';3-'A few times'; 4-'Several times'; 5-'A lot'                                                  |

In this analysis I will explore the data to answer three questions pertaining to the ongoing study for the year 2022.

- How is use of goverment federal aid/assistance associated with food security as measured by the USDA index or categories?
- Does food security have a relationshio with the items pertaining to concentration on schoold and degree process/completion?
- Are there gender or ethnicity differences in the items pertaining to concentration on school and degree progress?



## Knowing our students

Variables such as Gender, Income, and Ethnicity are shown in the following image. Due to the small ocurrences of categories such as *Transgender*, *Gene variant*, and *Prefer not to say*, these categories were collapsed into the *Other* category. For Ethnicity, since most of the students consider themselves as *Hispanics*, the other ethnicities were collapsed with the *Other* category.

![](/Image/FinalProject-DB-2.png)

As observed in the images, most of the studends are female (548 of 816), the vast majority is hispanic (734 of 816) and more than 80% of the students have an annual household income less than $50,000 which is considered as a low income according to [USNews](https://money.usnews.com/money/personal-finance/family-finance/articles/where-do-i-fall-in-the-american-economic-class-system) while less than 2% of students has upper income ( greater than $100,000).

## Job and Academic Information

In the following image, variables related to job and academic information is displayed. Variable such as Enroll, Employ, Work, Hrs, Classification, and College are shown. For the College variable, students were allowed to select more than one college.

![](/Image/FinalProject-DB-1.png)

86% of the UTEP studends are full-time students, about 70% are employed, about 30% have an on-campus job, and almost 40% has a full-time job.

Around the 80% are undergraduate students, most of them being senior students. Most of the students in the survey belongs to the pharmacy college.

## Personal Situation
![](/Image/FinalProject-DB-3.png)
