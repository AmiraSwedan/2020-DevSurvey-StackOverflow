# Analysis of 2020 StackOverflow Developers Survey 

## Packages 
In this notebook I have used the below python libraries
- pandas (0.19.2)
- numpy (1.15.0)
- matplotlib(2.2.2)
- seaborn(0.9.0)  

## Data:
The enclosed data set is the full, cleaned results of the 2020 Stack Overflow Developer Survey. The survey was fielded from February 5 to February 28, 2020. The median time spent on the survey for qualified responses was 16.6 minutes

## Objectives: 
In this notebook, I try to answer the below questions 
1) How earnings and weekly working hours contribute in the job statisfiction ? 
2) Is there any correlation between the level of satisfaction about the current job and the seek for getting a new job?
3) Does the annual salary average change according to the educational level and years of experience ?

## Approach
To Answer the above questions I relied on GRISP-DM process:
- Business Understanding: Three business related question have been formulated. 
- Data Understanding: I have used some functions in pandas package to show the structure of the data to get a better understanding on how the data can give a relevant answer to the questions, besides and for better understanding of the data, there is a data schema that shows what each column in the datasset refers to in the survey.
- Data Preparation: Before applying the statistical analysis that is needed to answer the above questions, there is a need to handle some issues in the data such as:
1) Creating groups: some variables such as (Years of experience) have been converted from numerical into categorical data to present some groups.
2) Handling missing values: I have dropped the missing values as many of them are missing in nature since the respondents were not elegible to answer the corresponding questions.
- Data Modelling and Visualization: I relied on some descriptives statistices to answer the business questions and I relied on bar plots and heatmaps to present the results.   
- Results Evaluation: As a final step, I ensured that the analysis results and findings can clearly answer the business-related questions and can be easily communicated with the stackholders.  

### Findings:
the project findings can be also accessed through my blog: https://datascience63059675.wordpress.com/ 

### Attachments: 
- survey_results_schema.csv: file contains a description for each variable in the dataset.
- survey_results_public.csv: the survey results full dataset.
- so_survey_2020.pdf: Survey questionnaire.
- Analyzing 2020 Developers Survey.ipynb: Ipython notebook includes the codes and the output. 

## Acknowledgment:
Massive, heartfelt thanks to all Stack Overflow contributors and lurking developers of the world who took part in the survey this year. We value your generous participation more than you know. <3
