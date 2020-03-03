# DS_6306 Project 1

This is the github repository for project group Brian Gaither, Andrew Laresen and Andrew Mejia. 

The purpose of this project is to answer the following questions of interest and present those findings to Budweiser.

1.   How many breweries are present in each state?

2.   Merge beer data with the breweries data. Print the first 6 observations and the last six observations to check the merged file.  (RMD only, this does not need to be included in the presentation or the deck.)

3.   Address the missing values in each column.

4.   Compute the median alcohol content and international bitterness unit for each state. Plot a bar chart to compare.

5.   Which state has the maximum alcoholic (ABV) beer? Which state has the most bitter (IBU) beer?

6.   Comment on the summary statistics and distribution of the ABV variable.

7.   Is there an apparent relationship between the bitterness of the beer and its alcoholic content? Draw a scatter plot.  Make your best judgment of a relationship and EXPLAIN your answer.

8.  Budweiser would also like to investigate the difference with respect to IBU and ABV between IPAs (India Pale Ales) and other types of Ale (any beer with “Ale” in its name other than IPA).  You decide to use KNN classification to investigate this relationship.  Provide statistical evidence one way or the other. You can of course assume your audience is comfortable with percentages … KNN is very easy to understand conceptually.

In addition, while you have decided to use KNN to investigate this relationship (KNN is required) you may also feel free to supplement your response to this question with any other methods or techniques you have learned.  Creativity and alternative solutions are always encouraged.  

9. A two way ANOVA was conducted to look at the comparisons of IBU and ABV accross the different regions in the US. Specifically, whether ABV depends on IBU and whether volume size of beer listed depnend on ABV and IBU. 


This repository is organized with a Raw Data Folder. Its Contents are the 3 raw files used in the analysis of the project. 

1.  Beers.csv
2.  Breweries.csv
3.  States

Data Set decriptions

Beers.csv 
1.  Name -- This is the beer name observation 
2.  Beer_ID -- This is the beer unique id observation 
3.  ABV-- This is the beer Percentage Alchol by Volume score in decimal format 
4.  IBU -- This is the beer International Bitterness Unit score in discrete numeric format
5.  Brewery_ID -- This is the beer unique brewery ID of where the beer is brewed 
6.  Style -- This is the style of beer 
7.  Ounces -- This is the volume of the beer 12 or 16 ounce containers 

Breweries.csv 
1.  Brew_ID -- This is the beer unique brewery ID and matches to the Brewery_ID in the Beers.csv file. 
2.  Name -- This is the brewery name 
3.  City -- This is the city of where the brewery is located 
4.  State -- This is the state of where the brewery is located, in the two letter abbreviation format. 

states.csv 
1.  state -- This is the state abbreviation, in the two letter abbreviation format, and matches to the State in the      Breweries.csv file.  
2.  latitude -- This is latitude of state
3.  longitude -- This is longitude of state
5.  name -- This is the long format of the state name. 


The Project_1.Rmd file is the R markdown file that contains the R code used for the anlysis of the project. 

The Project_1.html file is the HTML output of the R markdown file code base. 

The Project_1.PPTX file is the presentation of the exploratory data analysis as well as the unique anlysis proposed by the project team. 
