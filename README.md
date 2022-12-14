# Retail-Analytics-Project
## Introduction:
Retail analytics is the practice of monitoring company information, including inventory levels, consumer behavior, sales figures, and more, in order to make more strategic, educated decisions. This involves offering information to comprehend and improve the retail business's operational procedures, sales patterns, consumer behavior, and overall performance. Due to the high standards that consumers have for retail today, businesses must satisfy these growing demands with tailored omnichannel offers, effective procedures, and prompt adaptations to emerging trends—all of which call for retail analytics. On Statista's Amazon quarterly revenue, this is clearly visible. The fourth quarter of the year always sees Amazon's highest quarterly revenue, suggesting that consumers spend more money in this period than in the others. This is obvious given that Black Friday and Christmas both fall within the fourth quarter, which also sees a huge increase in global consumption. Potential sales would be lost if a store had too few items before Christmas. However, if a store has too many items, too much storage will be needed, and since storage costs money, the business will once again lose money. Therefore, RDA can be applied to try and improve product production so that there is always an ideal amount available.
## Problem Statement
Predict the department-wide Weekly sales for each store for the following year to enable us Provide recommended actions based on the insights drawn, with prioritization placed on largest business impact

## Data Exploration
The DataSet was got from kaggle here [https://www.kaggle.com/datasets/manjeetsingh/retaildataset?select=stores+data-set.csv]

We have historical sales information for 45 stores spread across several geographies, each of which has a number of departments. The business also holds a number of annual promotional discount events. The Super Bowl, Labor Day, Thanksgiving, and Christmas are the four biggest holidays that these markdowns coincide with. In comparison to non-holiday weeks, the evaluation of the weeks that include certain holidays is weighted five times more heavily.
The Dataset consist of three csv files
1. Store Dataset: This contains Anonymized information about the 45 stores, indicating the type and size of store
2. Feature Dataset: Contains additional data related to the store, department, and regional activity for the given dates.
3. Sales Dataset: This contains Historical sales data, which covers to 2010-02-05 to 2012-11-01.

## Visual Exploration of the Data Datewise
![image](https://user-images.githubusercontent.com/85242198/204774693-5dc30e15-00ad-41b5-9802-40e6528c9be6.png)

This is a time series analysis of some of the features. The first row is for Temperature over time, The temperature fluctuates throughout the year, reaching its peak somewhere around July and its lowest point somewhere in January. The actual temperature doesn't appear to have any impact on the weekly sales. The second row is that of the fuel price, Between January 2011 and July 2011, the cost of fuel significantly increased. After that, the cost of fuel is fluctuating up and down. The Consumer Price Index (CPI), which has been gradually rising since the time series' beginning, is shown in the figure's third row. The unemployment rate, which has been steadily declining since the time series' inception, is seen in the following row. The relationship between the CPI and unemployment rate makes perfect sense because when individuals have more jobs, they have more money to spend, which causes the CPI to rise because higher demand means higher prices. The boolean data indicating whether or not it is a holiday week is shown in the figure's fifth row. Weekly sales information is included in the last row. As is evident, a holiday week does not necessarily result in higher weekly sales numbers. Weekly sales information is included in the last row. As one can see, if the week is a holiday week, the weekly sales data is not necessarily larger. Weekly sales reach their highest levels in November and December. Black Friday may be to blame for the peak in November, while Christmas may be for the peak in December. Weekly sales are lowest in January.

## Visual Exploration of the Data StoreWise
![image](https://user-images.githubusercontent.com/85242198/204777929-8ad4b44b-5ac5-4f95-9481-70a3742dac55.png)
The left plot displays the number of stores that are offered for each kind. The most typical stores are those of type "A," whilst the least typical stores are those of type "C." A box plot of the weekly sales by store type is displayed in the middle plot. The median weekly sales are highest for store type "A," while they are lowest for store type "C." If one looks at the right plot, which displays a box plot of store sizes according to store type, this makes perfect sense. One can observe that store type "A" is the biggest, followed by store type "B" and store type "C," which are the smallest. Therefore, the size of the store and the volume of weekly sales are directly related.

## Visual Exploration DepartmentWise
![image](https://user-images.githubusercontent.com/85242198/204779922-b7e3ebed-0fe0-42a0-87d9-ffc0f74557dc.png)

Here, we can observe that departments 1 through 15 as well as 90 and 95 have demonstrated increased weekly sales.
Departments 38, 40, and 72 have displayed higher weekly sales as well.

## Visual Exploration of the Effects of Markdown
![image](https://user-images.githubusercontent.com/85242198/204780503-63357e29-6ea3-48c3-b734-44e1d2c05291.png)






