# Comparing Theater Play Outcomes

## Analyse the Theater Outcomes Based on Launch date and Funding Goals.

### Overview of Project
This project is to compare theatre's play outcomes relate to launch dates and different levels of funding goals. By seeting up the variables to observe lationship between outcomes with launch date and funding goals


## Analysis and Challenges
Using PivotTable and line chart was created to visualize theater data

### Analysis of Outcomes Based on Launch Date
Create on a pivot table using filtered data to displaysuccessful, failed, and cenceled outcomes per month filered by Parent Category and Year.
![This is an image](https://github.com/Izzyycl/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals
Calculate Number Successful, Failed and Canceled using COUNTIFS function by filtering Goal amount Subcatagory and play sections. Visualize a line chart using the percentage of Successful, Failed and Canceled outcomes. 
![This is an image](https://github.com/Izzyycl/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered
The only difficulty is the amount of canceled donations. As there are zero cancelations, so I use IFERROR function to get the value of zero in the "percentage canceled" column.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    1.  Launch date has great impact on successful outcomes and slight impact on failed outcome, launching theater from April to June can achieve a successful outcomes. However for canceled outcomes, there's almost no impact. 

    2.  Number of Successful outcomes was higher than failed and canceled outcomes.

- What can you conclude about the Outcomes based on Goals?

    Funding goals has a positive relation with percentage failed and a negative relation with percentage successful, but a opposite changes form 7 to 11.

- What are some limitations of this dataset?

    Year range and countries can be the limitations. As the date is not most updated and different countories have different conditions.

- What are some other possible tables and/or graphs that we could create?

    Use country as variable to create a bar chart related to theater outcomes
