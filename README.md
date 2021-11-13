# UFO-s

## Overview of Analysis
The purpose of this analysis was to create additional table features to the webpage designed to display UFO sightings and allow users to filter for multiple criteria at the same time.  Additional filters that were added were that for "City", "State", "Country", and "Shape".  Instead of using a button to filter the data, only a change in input text was used to automatically filter the data and refresh the page to include only filtered data.

## Results
Additional filters were added to the page for "City", "State", "Country", and "Shape" to allow more user friendly features.  Upon loading the webpage all of the data from the original data.js file will appear in a table on the right hand side of the page.  There will be placholders in each of the filter fields.
![image](https://user-images.githubusercontent.com/88444529/141656529-7e4b436e-ad45-48c8-8a9d-d2fc673324a8.png)
To filter by a field a user must simply input text into the field in appropriate format.  To enter in a date, it should in the form of m/d/yyyy if there are zeros preceding the digit, e.g. January would need to be written as "1/" rather than "01".  The same principle is applied to the day.  
![image](https://user-images.githubusercontent.com/88444529/141656632-be8d9156-3f1f-4f22-9be1-bdc26bff2ff8.png)
Adding additional filters to your search is done the same way.  The user will input a state with its two letter abbreviation and the same for country, it is case sensitive and only lower case letters should be used.  The city can be filtered by entering in case sensitive input as well.
![image](https://user-images.githubusercontent.com/88444529/141656665-9ddb2a5f-7249-4815-ac18-92a0a93f543c.png)
Finally, the shape can be filtered by user input by using case sensitive input the same way that state and country are.  
![image](https://user-images.githubusercontent.com/88444529/141656704-579cba26-e2f4-460c-b73b-586fb156db24.png)

## Summary
The webpage presented here using javascript, html, bootstrap, and css styling makes a very clean and aesthetically appealing webpage.  There is a good introductory paragraph and the display of table on the webpage fits well.  One drawback to the webpage is the case sensitivity and restrictiveness of the user input.  It has to be exactly as the user types it in to filter the results appropriately.  A recommendation for further development could be drop down menu's on the filter to allow ease of filtering without worrying about user input being exactly the same as what is in the data.  Another recommendation for further development would be to add in url's for articles about each of the sightings so that the user can have more information at their disposal.
