# Kickstarting with Excel
Performing analysis on Kickstarter campaigns using Excel.

## Overview of Project

### Purpose

The goal of this project is to advise a client, Louise (a potential theater director), for the best time of year to launch a Kickstarter campaign to fund her upcoming play, Fever. This exercise was an introduction to the Excel's ability to use Pivot Tables, Pivot Charts, Conditional Fomatting, and a number of other functions to perform statistical analysis and generate graphical representations of data.

## Analysis and Challenges

Analysis for this project began by getting to know the dataset provided for Kickstarter campaigns launched from 2009 to 2017. Our client would like to answer two questions:

1. Is there an optimal time of year to start a theatrical Kickstarter campaigns?
2. How do the funding goals for a play effect the success of the Kickstarter campaign?

### Analysis of Outcomes Based on Launch Date

The data provided contains the information we need, but not in the format to easily create graphical representations for quick reference. To begin answering the clients questions, I created a "Years" column by extracting it from the "Date Created Conversion" data given in the orignal set (this was initially provided as Unix timestamps). Using the years, a Pivot table and Pivot chart were generated to see the theater campaign outcomes based on their launch dates. The table filters the "theater" Parent category and removes the "live" outcomes to reflect the clients interests. The chart below shows the graphical representation of the data with "successful" in blue, "failed" in orange, and "canceled" in yellow.

![Outcomes Based on Launch Date](https://github.com/jp3tty/Module-1-Challenge/blob/main/Theater_Outcome_vs_Launch.png)


### Analysis of Outcomes Based on Goals

To provide the client with information on how the outcomes were influenced by their funding goals, I created the chart below by comparing a given "Outcome" percentage against a campaign goal. To keep the chart from appearing too busy, the entire datasets was filtered to consider only plays, due to the clients interests, and the funding goals were reduced to 12 monetary ranges (valued in US dollars). This analysis can be seen in the chart below.

![Outcomes Based on Goal](https://github.com/jp3tty/Module-1-Challenge/blob/main/Outcomes%20Based%20on%20Goal.png)

Successful in blue, failed are in orange, and canceled in grey.

### Challenges and Difficulties Encountered

A stand-out difficulty occured when working with the Pivot table for "Outcomes Based on Goals." After working through the Module and manipulating the data in a variety of ways, Excel's data cache had issues referencing the proper values for the data I wanted to work with. The results was a chart that did not match what was expected in the challenge. After a fair amount of troubleshooting, a solution was discovered by preforming a "refresh" directly to the Pivot table. 

## Results
