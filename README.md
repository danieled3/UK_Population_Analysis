# UK Population: The main Trends

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspects](#technical-aspects)
  * [Results](#results)
  * [To Do](#to-do)
  * [File List](#file-list)
  * [Credits](#credits)


  
## Overview <a name="overview" />
This is a simple data analysis project where I studied the statistics of the UK population in the period from 1981 to 2017 (https://www.nomisweb.co.uk/api/v01/dataset/NM_31_1.jsonstat.json). I analyzed how the population progressed by regions and age groups and I tried to explain this phenomenon through data. Moreover, a simple ppt presentation is provided to summarize the key insights. 

## Motivation <a name="motivation" />
It was a good way to familiarize myself with data wrangling and data visualization in R.

## Technical Aspects <a name="technical-aspects" />
The main issues of this project were:
1. Organizing raw data in a "tidy version"
2. Finding interpretable charts to visualize results

## Results <a name="results" />
The main results, that you can also find in UK_Population_Study.ppt, are the following:
1. Uk population is constantly growing (growth rate of 500k people/year in the last 5 years).
2. The total population growth is mainly due to the growth of the British population.
<img src="https://user-images.githubusercontent.com/29163695/121808797-7e1ec200-cc5a-11eb-94b7-36f82c999790.png" height="400" align="center">

3. UK population is slowly leaving Scotland (it may have a lower bith rate or higher emigration rate)
4. England population, on the contrary, is increasing 
<img src="https://user-images.githubusercontent.com/29163695/121808980-48c6a400-cc5b-11eb-84d2-c3e61877d58a.png" height="400" align="center">

5. Population is aging because people older than 50 are strongly growing in recent years ( because of either high emigration of young people or low birth rate)
<img src="https://user-images.githubusercontent.com/29163695/121811058-66980700-cc63-11eb-8865-7fdad80f82db.png" height="400" align="center">

6. Wales has the largest percentage of over 50 year old people
<img src="https://user-images.githubusercontent.com/29163695/121809055-98a56b00-cc5b-11eb-8de1-b40b7269b79d.png" height="400" align="center">

## To Do <a name="to-do" />
* Integrate data with immigration/emigration rate and birth rate to understand the reason why population is increasing/decreasing

## File List <a name="file-list" />
* **UK_Population_Study.ipynb** Completed and commented data exploration analisys made thorught R Markdown in RStudio
* **UK_Population_Study.pdf** Extraction in pdf of the previous analysis and of code output
* **UK_Population_Presentation.ppt** Presentations of main insights

## Credits <a name="credits" />
[Official Labour Market Statistics](https://www.nomisweb.co.uk/) - Thanks for the open data about the UK population
