# Kickstarting with Excel

## Overview of Project
Analayse the kickstart data in excel to familiarize myself with the excel tools. 

### Purpose
Louise is considering kickstart campagin for play Fever. Use the kickstarter dataset to help her in making essential business decision regarding the launch of the campgain to maximize its success.  


## Analysis and Challenges
Dataset used for the analysis is the excerpt of the kickstart challenge. Essential columns like Launch Date and End Date that are in unix timestamps which needs to be converted to the roman date format. 


### Analysis of Outcomes Based on Launch Date
As per instruction provided a pivot table was created to capture the successful, failed and cancelled data. Pivot table were then filterd for the "Theater" category. 



### Analysis of Outcomes Based on Goals
For analysis based on Goals, a column was created that subcatagorizes the data into twelve ranges based on the pledged amount. To complete this task COUNTIFS function was used,this will reduce probability of error on further analaysis. Different sheet with name "Outcome Based on Goal" was created to get the count of the Successful, Failed and Cancelled for each bins of play data.  




### Challenges and Difficulties Encountered
Quite less number of the resources available for excel for Mac version in comparision to the windows. 



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
As per the graph shown usually Campagin on the month Apr to the July has higher number  of the successful campagin. 

- What can you conclude about the Outcomes based on Goals?
Looking at the graph it shows significant increase in the successrate after the pledged amount of more than 20,000. Staying below that will increase the success percentage. 

- What are some limitations of this dataset?
Data available for all number fluctuates quite alot. 

- What are some other possible tables and/or graphs that we could create?
Comparision by the geographical region
