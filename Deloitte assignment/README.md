# Data-Visualization
https://github.com/Algo-RHYTHM/Deloitte_Assignment

Working: The X and Y axis labels can be changed by the corresponding lables given in X and Y axis of the graph and on change of the labels it filters and shows the corresponding values.
Tool tips are provided which shows the respective appropriate values provided in the CSV file given. On mouse hover it shows x,y values firm attributes, Clusters and Categories provided
Labels are displayed to differentiate between colors and for representation of particular category.


## Background

Utilizing information from the CSV given, create charts, graphs and interactive visualizations to help understand findings

## Objectives

### Level 1: D3 Dabbler

Create a scatter plot between the data variables such as `Auto_Current_Competitiveness vs. Auto_Future_Competitiveness` or `Consumer_Current_Competitiveness vs. Consumer_Future_Competitiveness`


* Using D3 techniques, create a scatter plot that represents each state with circle elements. You'll code this graphic in the `app.js` file. Make sure to pull in the data from `data.csv` by using the `d3.csv` function. 
    * Create and situate your axes and labels to the left and bottom of the chart



Utilize D3 to help interact with the data

#### 1. More Data, More Dynamics

Place additional labels in the scatter plot and give them click events so that users can decide which data to display. Animate the transitions for circles' locations as well as the range of the axes.

#### 2. Incorporate d3-tip

While the ticks on the axes allow one to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected
