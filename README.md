# Problem Statement

<em>TV program content ratings have been a topic of debate since the establishment of the FCC. Animated series in particular have been a recurring topic for discussion due to the subject matter falling on the line between fantasy and reality. Animated programs in particular tend to be geared toward younger audiences who can intake hundreds of hours of television by the time that their brain is 90% developed (typically seen by age 5). Due to the impressionable nature of children coupled with the abundance of program options children have access to it is as important as it ever has been to ensure that content served is age-appropriate.</em>

## Executive Summary

Several models were developed and tuned to find the proper combination of model/hyper parameters that would minimize Type II errors.

### Contents:
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#top">Introduction</a> 
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#scraping">Text Scraping</a> 
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#cleaning">Data Cleaning</a>
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#stops">Preliminary Model Development</a>
- <a href = "https://git.generalassemb.ly/chrisvolpacchio/project_3/blob/master/CV%20Sub-Reddit%20Classifier.ipynb#moremodels">Advanced Modeling</a>

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
Our final model detects the presence of TV–MA content in context approximately 97% of the time. The model is able to intake any number of text blocks of any length and almost perfectly identify the presence of unwanted content.

### Next Steps
* Use alternate sources for inforation surrounding program content such as network websites.
* Improve model *overall* accurracy to avoid withholding TV–Y content as well as any content not considered to be TV–MA.
* Increase our model's TV–MA detection–rate to 1.00 (100%).

https://azpbs.org/2017/11/early-childhood-brain-development-lifelong-impact/