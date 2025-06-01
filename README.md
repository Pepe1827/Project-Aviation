# Aircraft Analysis

![example](images/airplane1.jpg)

Author : Jose Ortega

## Overview

In this project, I will use data cleaning, analysis and visualizations in order to generate insights for a business stakeholder.

## Business Problem

My company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in buying and operating aircrafts for commercial and private use, but do not know anything about the potential risks of aircraft. My task is to analyse the data and come up with three business recommendations.

## The Data

The data used in this project is from the NTSB (National Transportation and Safety Board), that contains information from 1962 and later about civil aviation accidents and selected incidents within tha United States, its territories and possessions, and international waters. Some of the important variables in the dataset are : Aircraft damage, category, make, model, number of engines, engine type, injury severity and total injuries.

The original dataset can be found here __[link text](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)__

## Methods

In this project we use descriptive analysis, first we understand/inspect the dataset given, then we clean and prepare the data (basically we get rid of colummns that we are not going to use and we also deal with the missing values), once the data is cleaned I will analyze the data , interpret the results and communicate the findings.


## Results
### Visual 1
![example](images/Visualization_1.png)
Visual number 1 is "Total Fatal Injuries by Make" , this first chart tell us which aircraft makes have been involved in the highest number of fatal incidents, but this does not necessarily mean they are the most dangerous (Boeing and Cessna for example) , these reflects that these manufacturers have a much larger number of aircraft in operation meaning they are the most popular makes in those years.

### Visual 2
![example](images/Visualization_2.png)
Visual number 2 is "Average Fatalities Per Crash by Number of Engines", we can see in this visualization that fatalities per crash tend to increase with the number of engines.

### Visual 3
![example](images/Visualization_3.png)
Visual number 3 is "Fatal Injury Rate and Total Fatal Injuries by Engine Type", this will give us a good insight about which engine type are safest one.

### Visual 4
![example](images/Visualization_4.png)
Visual number 4 is  "Fatality Rate by Aircraft Model (Top15), this visualization is useful to understand which aircraft model are the safetest using fatality rate as a measurement.



## Conclusions

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) and our [presentation]

For any additional questions, please contact Jose Ortega at [joseorteorbe@gmail.com](mailto:joseorteorbe@gmail.com) 


## Repository Structure

- The visualizations in the notebook use best practices for visualization that you should try to emulate. For example, they have clear axes, descriptive titles, and appropriate number formatting
- The `dsc-phase1-project-template.ipynb` is intended to be the _final version_ of your project. The first notebook you create will not look like this. You are encouraged to start with a very disorderly notebook and clean it as you go
