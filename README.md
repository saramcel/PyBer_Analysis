# PyBer Analysis

Overview of the analysis: Explain the purpose of the new analysis.
Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)

Analysis (14 points)
The written analysis has the following:

# Overview

## Purpose 
The purpose of the new analysis is to present the key metrics of ride-sharing company PyBer (fares, rides, and drivers) grouped by population density of the 120 cities it serves. The CEO, V. Isualize, will use this information to improve disparities among city types. 

## Background
The CEO of PyBer, a ridesharing company, has requested information broken down by city type (e.g. Urban, Suburban, and Rural). The ways that customers use the ride sharing service in each type of city are expected to differ, and these differences will affect how PyBer approaches these markets. In the Modules, we discovered that Rural cities have a few drivers, there are fewer trips, and fares are higher than Suburban and Urban cities. Urban cities had the most drivers, most frequent trips, and the lowest fares. Suburban cities were between Rural and Urban in each of these metrics, typically with metrics closer to Urban cities. 

# Results

## Summary Statistics
The summary statistics show that most rides occur in Urban settings, where there are also more drivers. The revenue, shown here as total fares, is also mostly made in the Urban cities. 

The fare per ride, however, is lowest in the Urban cities, slightly higher in the Suburban cities, and higher in Rural cities. It also follows that the average fare per driver is much higher in Rural cities than in Suburban or Urban cities (where drivers make less than half as much as Rural drivers). 

![DataFrame with Summary Statistics, All Data](https://github.com/saramcel/PyBer_Analysis/blob/312f44987052ddd962d98e2fbee3ab9a8bd685c8/analysis/PyBer_Summary_DataFrame.png)

## Fares by City Type over Time

The line graph dives deeper into the period between January 1st, 2019, to April 28th, 2019. The sum of the weekly fare is displaye on the y-axis, and the months are marked on the x-axis. The Urban fares are generally higher than the Suburban fares, which are higher than the Rural fares. By the end of April, Suburban fares are rising as Urban and Rural fares stagnate. Urban fares have an unstable pattern in March. For all city types, the fares start pretty low in the first week of January, and there is a small jump in fares in the last week of February. 

![Line Graph of Fares by City Type, Spring 2019](https://github.com/saramcel/PyBer_Analysis/blob/3fa5d61729d428c3cdd0ed7459bedd786f319c86/analysis/PyBer_fare_summary.png)

# Summary

Considering the different ways in which clients are using PyBer in each type of city, this analysis team has three business recommendations for the CEO.

1. Examine why the numbers around New Year's Eve are so low. The first week of January fare numbers are low among all city types, especially Urban and Sububan. Customers who go out on New Years Eve are not choosing PyBer to get home on New Year's Day. Answer the following questions:
   - Are fewer drivers working on New Year's Eve?
   - What would incentivize more drivers to drive on New Year's Eve in Urban and Suburban cities?
   
2. Analyse how raising fares in Urban cities would affect ridership. It is possible that ride frequency is connected with the fare. The fares in Urban areas reach their peak in March, but after each week of high fares, there is an immediate decrease the following week. 
   - Are Urban customers avoiding PyBer after they pay high fares?
   - Would Urban customers be willing to pay more per ride, and at what point does the price lead to avoiding PyBer?

3. Analyse the demand for PyBer in Rural cities. Rural customers are willing to pay more per ride, but we need more information about whether more drivers would actually increase revenue, because the number of rides are so low. Answer the following questions:
   - Are there fewer rides provided because the rides are longer? 
   - Is there demand for additional drivers in Rural cities?
