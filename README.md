# Demand-and-Supply-Analysis
Demand and supply are very important concepts in the world of business.
It is important for any business organization to know the relationship between its market demand and supply.
This is important so that the business can maximize profits.

The demand for a product or service is the quantity of that product or service the customers are willing to purchase at any given price during a particular period.
On the other hand, supply for a product or service is the quantity the producers are willing to provide in the market at a particular price and a particular period.
# Project
For this analysis, I found an ideal dataset, which is based on the demand for cab rides at a given time and the availability at a given time.
You can out the dataset at: https://statso.io/demand-and-supply-case-study/
The dataset consists of 3 columns: Drivers Active Per Hour, Riders Active Per, Hour and Rides Completed.
# Descriptive analysis.
The dataset consists of 1099 rows of both Active drivers and riders per hour and 1045 Rides completed.
The number of active drivers per hour is mostly 55 drivers, riders 175, and the number of rides completed is mostly 107 rides.
The minimum number of active drivers per hour is 10 drivers while the maximum is 100 drivers.
The min number of active riders per hour is 50 while max are 300 riders.
The min number of rides completed is 2 while max is 273 rides.

# Data Cleaning
The 54 null values of Rides completed were dropped.
# Data Visualization
## Relationship between the number of drivers active per hour (Supply) and, riders active per hour (Demand).
The scatter plot graph shows the relationship between the number of drivers active per hour (Supply) and the number of rides active per hour Demand).
The data points form a straight line, indicating a positive linear relationship between the two variables.
A blue line of best fit is drawn through the data points to show the trend more clearly.
## Elasticity of demand for rides
The elasticity of demand is 0.82.
This signifies a moderately responsive relationship between the demand for rides and the number of active drivers per hour.
This means that a 1% increase in the number of active drivers per hour would lead to a 0.82% decrease in the demand for rides, while the opposite is also true.
The demand for rides is somewhat sensitive to changes in the number of active drivers per hour.
## Supply Ratio vs. Driver Activity
A scatter plot graph was plotted that shows the relationship between the supply ratio and driver activity.
The data points are scattered in a linear pattern with a slight positive correlation.
The data points are more densely clustered towards the lower left corner of the graph, indicating that there are more drivers active per hour than rides completed per driver per hour.
# Project Summary.
This a short simple project demonstrating how we can analyze demand and supply using Python pragramming language.
