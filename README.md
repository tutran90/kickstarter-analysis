# Kickstarting with Excel
## Overview of Project/Purpose
Performing an analysis on **"Outcomes based on Launch Date"** for Theaters and **"Outcomes based in Goals"** for Plays in the US.
## Analysis and Challenges 
In order to find the **"Outcomes based on Launch Date for Theaters"**, the main data set on the worksheet labeled ["Kickstarter"](https://github.com/tutran90/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx%202.zip) was filtered to only show Theaters in the Parent Category. A new column was also created to show only the years the projects were launched. Next, a table was created using the "pivot table" feature on Excel. Years and outcomes were filtered into the rows, columns, and values. Lastly, a chart was [created]. To analyze the trends for **Outcomes based on Goals** for plays, a new sheet was created labeled **"Outcomes based on Goals"**. A new table was created to organize the data according to goal amount and the outcomes for each along with the percentage. A chart was then [created](https://github.com/tutran90/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png) to show the trends for plays. 
### **Challenges**
Challenges that occured during this project include:
1. Selecting rows of data that were note adjacent to each other to create the chart that only showed "Percentage of Outcomes". I first attempted tackling this dataset by selcting the **select data** option, however I was still not able to select the data that I needed. After searching for how to select nonadjacent rows on Google I was able to select the rows I needed (selecting "Commmand" then hovering over the columns I needed.
2. Manipulating the pivot table to be visually appealing and less overwhelming. After placing certain groups into the values, rows, etc., this created different subcategories to form. A lot of trial an error occured in order to create a table that was depicting a clearer picture. 
### **Analyzing Results**
**What are two conclusions you can draw about the "Outcomes based on Launch Date"?**

- Theater projects launched in the months of May and June had the most success. 
- The majority of the the theater projects had a success rate of >= 50% and less than 1% of cancelled projects. 

**What can you conclude about the "Outcomes based on Goals"?**

- There were no plays that were cancelled. 
- Plays with goals of <$1000 were more successful in reaching their goals (76% success rate), while plays with goals between $25000-29999 had the most failures (80% failed rate).

**What are some limitations of this dataset?**

- This particular dataset is looking at projects entered in "Kickstarter", which is only one source. Having more than one source will allow one the ability to analyze the industry better before making a decision on starting a project. For example, Kickstarter is only showing projects that were posted on their site. There might be other sites/plateforms that collect the same data but the information may be the complete opposite. It's similar to when going to a new restaurant, if you only look at Google reviews, it may be biased, since some memberships can allow one to omit the 1 star rating. It's always smart to compare different sources especially when making a finacial investment. 

**What are some other possible tables and/or graphs that we could create?**

- Creating a bar graph showing the "Outcomes based on Launch Date" for different countries ex. US, CA, and GB. There may be different seasons where things may be more successful in other countries than in the US. 
- Creating a bar graph showing the "Outcomes based on Goals" but showing the different categories, i.e food, technology, plays, etc. This could show which one is category is more popular, and help one decide on future investment decisions. 
