# Introducing Tableau for Data Analysis

**By** Wenying Wu, 28/03/2022

## Why choose Tableau?

Continuing from [Data Visualization using Chartblocks](https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/Data%20Visualization%20using%20Chartblocks.md), I am exploring what a visualization tool can provide without requiring programming knowledge. I am seeking a more powerful visualization tool, and Tableau as a market leader worldwide is worth everyone exploring. Tableau offers products including Tableau prep for ELT process, Tableau Desktop, Tableau Server, Tableau Mobile & Tableau Online for visualization. Users can easily choose according to their needs. I will focus on the Tableau desktop in this blog.

Similar to Post 1, I am interested in whether there are changes in the consumption of different types of meat. Instead of only visualizing one area due to the limitation of simple online tools, Tableau allows me to visualize various areas in the [dataset](https://www.kaggle.com/vagifa/meatconsumption) I found last week at one time.


## Data Wrangling

Figure 1 shows the data preparation in Tableau Desktop. Tableau supports various file types and supports connections to almost every external server in the market.

<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image001.png">
</p>

<p align="center">Figure 1. Homepage of Tableau Desktop
</p>



Users can use Data Interpreter, create calculated fields, and edit data source filters to edit abnormal values. Moreover, users can use Tableau's separate data preparation tool, Tableau Prep, before the visualization step. The dataset does not contain missing values and duplicates, but I want to change the name of the type of meat to the name we commonly use. In this case, I created a calculated field to change "PIG" to "Pork" etc and add data source filters to make the dataset I used only include historical data and exclude World data.

<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image002.png">
</p>

<p align="center">Figure 2. Data cleaning in Tableau Desktop
</p>
 
 
<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image003.png">
</p>

<p align="center">Figure 3. Create Calculated Field in Tableau Desktop</p>
 
<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image004.png">
</p>
 
<p align="center">Figure 4. Edit Data Source Filters in Tableau Desktop</p>

## Data visualization

Tableau desktop's interface is simple, making it more suitable for most people to get started quickly. Figure 5 is an example of creating a line chart in Tableau Desktop. You can easily drag and drop columns to make a figure. 

<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image005.gif">
</p>
 
<p align="center">Figure 5. Plotting in Tableau Desktop
</p>

As shown in Figure 6, I can compare the trend and the amount of meat in different regions per capita. For example, **the USA** had the highest consumption of meat. It was followed by **Australia**, the second largest region of meat consumption. The USA had low consumption of lamb in all historical times and poultry is highest compared to other types of meat. 


<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image006.gif">
</p>
 
<p align="center">Figure 6. Consumption of Meat
</p>
 
Figure 7 shows **Uruguay** (URY) and **Argentina** (ARG) have the highest consumption of beef per capita. Beef is the most popular meat in these regions all the time. Interestingly, the consumption of poultry in ARG was increasing, the consumption of beef was slightly decreased by contrast. Rather than beef, poultry may be the highest consumption in ARG in the future.

<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image007.gif">
</p>

<p align="center">Figure 7. Consumption of Beef
</p>
 
Figure 8 shows **New Zealand** (NZL) and **Australia** (AUS) had the highest lamb consumption per capita. Looking at the trend, I found lamb is not as popular in NZL as before. It decreases over time, and the consumption of poultry is increasing.
 
<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image008.gif">
</p>
 
<p align="center">Figure 8. Consumption of Lamb
</p>
 
Figure 9 shows that **EU28** and **China** (CHN) had the highest pork consumption per capita. Pork is the most popular meat in these regions and some other Asia regions such as South Korea (KOR) and Vietnam (VNM).

<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image009.gif">
</p>
 
<p align="center">Figure 9. Consumption of Pork
</p>
 
Figure 10 shows Israel (ISR) has the highest consumption of poultry, probably because of its culture. Pork and lamb are very low at all times. Followed by **USA**, **Saudi Arabia** (SAU), **Malaysia** (MYS), poultry is the most popular meat in these regions all the time.

<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/Introducing%20Tableau%20for%20Data%20Analysis/image010.gif">
</p>

<p align="center">Figure 10. Consumption of Poultry
</p>

## Opportunities

Tableau provides an intuitive, interactive, visual-based exploration experience that allows business users to access data and analyze it without programming knowledge. The tableau interface is user-friendly. Tableau has strong abilities in data presentation and data exploration. It's tough to make ugly figures in Tableau. Data import and loading are wizard-style and 80% of Tableau's functions can be realized by dragging and dropping. Moreover, it is easy to change the dimensions of the analysis, the granularity of time, and produce various graphs quickly in Tableau. Neither Excel nor Python can be so intuitive and easy to visualize. From my perspective, I really enjoy the Interactive visual experience Tableau provides. In the question I want to visualize, I have no idea how to do it in python as quickly as in Tableau. 

## Challenges
Tableau Desktop is a tool focused on data visualization, the data cleaning functions are fundamental. It is challenging to deal with abnormal data without working together with Tableau Prep to clean data or use other ETL tools prior to the visualization. There are limitations and time-consuming data cleaning in Tableau desktop. Tableau does not support automatic update reports, and it still needs users' actions to update the data. Sames like Tableau is not a complete open tool. There are limitations on the custom format in Tableau, users cannot change all fields at one time, and there are no custom visual template settings like the competitor PowerBI. There is no data warehouse in Tableau, users can only connect to external servers. Moreover, considering there are free/open-sourced tools that can create great visualizations,  It is tough to justify the cost of Tableau is reasonable and worth.

## Conclusion
Overall, Tableau has a strong ability in data presentation and data exploration. Tableau is a good choice at the current stage if only to reduce work duplication, update charts and dashboards, focus more on visuals, and do not care about the expensive price. In my opinion, Tableau is not a better choice than PowerBI when the data is complex, and you have to create a lot of custom analysis metrics and reports and satisfy all kinds of whims.
 

