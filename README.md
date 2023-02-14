# UFOs

## Overview of project

This project utilized data with various characteristics involving UFO sightings to create a filterable table where earthly visitors can search specific data and see only the results that match their search request across various search criteria. The table 

## Results

Performing a search is fairly simple, visitors to the site can review the available filterable categories and enter the item they wish to see results for. When the user completes entering their data, the script loops through the whole dataset and returns a new table using the rows that correspond with the user's input. Refreshing the screen or removing the entered criteria updates the table to include all of the initial data.

Multiple search filters can be used at the same time and will performa union and not a join of the  data, so results will become more narrow as additional filter search fields are utilized. See screenshot below with use of two filters:

![Filter Screenshot](https://github.com/UnBearAble1/UFOs/blob/main/Starter_Code/web/static/images/filter%20screenshot.png)

One challenge with the table is that there are few guidelines, and while it seems intuitive for how to use the table, without explicit instructions users may become frustrated and not use the tool.

## Summary

One drawback of the current design is that the filter entries must match the table data by case and users. Users of the table may not realize this and enter an uppercase letter for some of the data and receive no results.

This issue can be addressed by adding a function to force all characters to be lower case after they are entered

A second recommendation would be to add a message if there are no returned search results to let the user know that their search criteria did not return any results and to refine their search or in addition, this message could tell the end user that all entries need to be entered in lower case. In the current iteration, the table simply disappears which could cause a user to believe the table is simply broken if they believe they entered the search criteria appropriately.

A final recommendation is to add another search criteria for the shape category. 

