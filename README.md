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


# Conclusion

### Recommendations
Our final model detects the presence of TV–MA content in context approximately 97% of the time. The model is able to intake any number of text blocks of any length and almost perfectly identify the presence of unwanted content.

### Next Steps
* Use alternate sources for inforation surrounding program content such as network websites.
* Improve model *overall* accurracy to avoid withholding TV–Y content as well as any content not considered to be TV–MA.
* Increase our model's TV–MA detection–rate to 1.00 (100%).

https://azpbs.org/2017/11/early-childhood-brain-development-lifelong-impact/