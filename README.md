# UFOs

## Overview

The purpose of this analysis is to provide Dana's webpage/table with a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria. The following tasks are to be completed: 

1. Remove the list element which creates the button, and create five list elements for filtering the index.html file.
2. Modify the event listener to detect changes to each filter in the app.js file.
3. Change the updateFilters() function to save the element, value, and id of the filter to be changed.
4. loop the filterTable() function through all of the filters and keep any data matching the filter values.
5. Ensure the webpage filters the table correctly based on user input.

## Results

***Deliverable 1: Filter UFO sightings on multiple criteria***
Using JavaScript and HTML, the code was modified in the index.html file to create more table filters. In addition to the date filter, filters for the city, state, country, and shape were added. Someone might use the new webpage to search for UFO sightings by changing the following criteria in the following filter elements:
- Date
- City
- State
- Country
- Shape

Figure 1:

![Webpage](https://raw.githubusercontent.com/krismbah/UFOs/main/deliverable1.png)

The following is a search focused on the "State" of California (ca):

Figure 1:

![California](https://raw.githubusercontent.com/krismbah/UFOs/main/deliverable2.png)


## Summary

To summarize, one major drawback of this new design is that the user isn't given a dropdown menu of criteria to choose from within each filter. The criteria they may choose maynot be existing. For futher development of the webpage, the following recommendations are suggested:

1. Change the filter elements to dropdown menus.
2. Include a greater dataset spanning more than two weeks of one year.
