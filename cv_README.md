-----> input animation stats

"90% of a child's brain is developed by age 5."
https://azpbs.org/2017/11/early-childhood-brain-development-lifelong-impact/

Help distinguish between TV-Y (Arthur) and TV-MA (Attack On Titan!) for parents who are trying to limit theeir children's exposure to violence. The waters of TV ratings have been a topic of debate since the establishment of the FCC. Animated series in particular have been a popular topic for discussion as they are highly impressionable on children. Television still remains to be one of the most popular mediums for youth entertainment {inserts streaming stats} {Maybe to do with Netflix "Children's" streaming preferences}.

One deals with more complex topics like high–pressure interpersonal conflict and death.

One - posts
one - comments
one - combined

--> confusion matrix

------------------> we will specify why we chose to use what type of model that we did. (i.e. ensemble and because why
#do lemmatizers make sense here?
    #death, dead, deadly, etc.?
    
    
TV-MA
Mature Audience Only
This program is specifically designed to be viewed by adults and therefore may be unsuitable for children under 17.


# Problem Statement

<em>TV program content ratings have been a topic of debate since the establishment of the FCC. Animated series in particular have been a recurring topic for discussion due to the subject matter falling on the line between fantasy and reality. Animated programs in particular tend to be geared toward younger audiences who can intake hundreds of hours of television by the time that their brain is 90% developed (typically seen by age 5). Due to the impressionable nature of children coupled with the abundance of program options children have access to it is as important as it ever has been to ensure that content served is age-appropriate.</em>

## Executive Summary

Through thorough analysis of the SAT & ACT data as well as independent research, I have concluded that the most effective way to increase participation rate for the SAT is to lobby local governments for its mandate and funding.

### Contents:
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#top">Introduction</a> 
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#scraping">Text Scraping</a> 
[2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|sat2017|The states that have representatives who have participated in the exams.|
|**sat2017_participation_rate**|*float*|sat2017|The percentage of eligible state representatives completing the SAT in 2017.|
|**sat2017_reading_writing**|*int*|sat2017|The corresponding state's average score on the reading/writing section of the 2017 SAT|
|**sat2017_math**|*int*|sat2017|The corresponding state's average score on the mathematics section of the 2017 SAT.| 
|**sat2017_total**|*int*|sat2017|The corresponding state's average score on the combined reading/writing and mathematics sections of the 2017 SAT.|
|**act2017_participation_rate**|*float*|act2017|The percentage of eligible state representatives completing the ACT in 2017.|
|**act2017_english**|*float*|act2017|The corresponding state's average score on the english section of the 2017 ACT|
|**act2017_math**|*float*|act2017|The corresponding state's average score on the mathematics section of the 2017 ACT|
|**act2017_reading**|*float*|act2017|The corresponding state's average score on the reading section of the 2017 ACT|
|**act2017_science**|*float*|act2017|The corresponding state's average score on the science section of the 2017 ACT|
|**act2017_composite**|*float*|act2017|The corresponding state's average score on the combined english, math, reading and science sections of the 2017 ACT|
|**act2018_composite**|*float*|act2018|The corresponding state's average score on the combined english, math, reading and science sections of the 2018 ACT|
|**act2018_participation_rate**|*float*|act2018|The percentage of eligible state representatives completing the ACT in 2018.|
|**sat2018_participation_rate**|*float*|sat2018|The percentage of eligible state representatives completing the SAT in 2018.|
|**sat2018_reading_writing**|*int*|sat2018|The corresponding state's average score on the reading/writing section of the 2018 SAT|
|**sat2018_math**|*int*|sat2018|The corresponding state's average score on the mathematics section of the 2018 SAT.| 
|**sat2018_total**|*int*|sat2018|The corresponding state's average score on the combined reading/writing and mathematics sections of the 2018 SAT.|


# Conclusion

### Recommendations
SAT put in more resources into some states than it did for others; whether that be money given or partnership with state legislature through lobbying to make the exam mandatory. We 
can see some effects of those efforts in not only the SAT PR increases but in the ACT PR decreases as well. Scores
are correlated with taking another exam meaning if one student does well on one exam in same year they may take other
as well. This is showing that prep for an SAT course spread out by CB itsself could be useful as those who take both
exams are likely very interested in 'superscoring' and obtaining the best grade possible. If this is in fact the case 
having official prep resources, whether that be books or courses, by CB could influence those students to do well as well. on the other hand, there is a fairly strong negative correlatioin with test results on SAT and participation in the next year meaning that those who dont do very well are going to want to take it again. This further proves our previous point of students really wanting to max out their exams. As a business it may be more lucrative to have students be taking exam multiple times and maybe it makes more ssense to invest more resources into exam availability and presence over the actual prep itself. I reccommend to follow down same path of partnering with states to have exam be mandatory but not before modeling out revenue from taking exams and how long it would take to see profit based on deal that is determined with funds allocated (i.e. Illinois 3yr 14.3 mill mandatory agreement). This seemed to work well in terms of increasing participation but the amount of participants over rate multiplied by what their tests are bringing in is what will help optimize the CB business.

### Next Steps
* Use alternate sources for inforation surrounding program content such as network websites.
* .