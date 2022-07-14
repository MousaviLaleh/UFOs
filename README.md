# UFOs
Using JavaScript visual functionality to build a dynamic webpage and manipulate the data by adding filters.

## Overview of Project
The purpose of this project was to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time, in addition to the date. We will add table filters for the city, state, country, and shape.

### Resources
Data Environment :&nbsp; [JavaScript](https://www.w3schools.com/js/default.asp),&nbsp; [JavaScript D3 Library](https://d3js.org/),&nbsp; [HTML](https://www.w3schools.com/html/default.asp),&nbsp; [Bootstrap v5.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
<br/>
Data Source :&nbsp; [UFO Data](data.js)
<br/>

## Analysis
In order to display the data on the webpage :
- Import the data into a JavaScript table Object.
- Loop through each object and append a row and cells for each value.
- Create a variable to keep track of all the filters as an object in the js code.
- Create a function to filter the table.
- Create a filter area in the webpage, using Bootstrap form component.
- Style the webpage using Bootstrap and CSS stylings.
- Tie the js code to the html page.
<br/>

Initial look of the webpage : 
<br/>

![01.png](/images/01.png)

Filters help user to have a faster and neat search in the table.
<br/>

![02.png](/images/02.png)
<br/>

![03.png](/images/03.png)
<br/>



## Summary
One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis, or the "shape" field; those who are unfamiliar with UFO sightings may not know that "light" is considered a shape for UFOs.<br/>
Another drawback is that Javascript language is case sensitive. This can impact the user experience because all of the searchable data is lowercase. For example, if a user were to enter "CA" to identify the UFO sightings in California, the filter search results are zero. Whereas, if they were to enter "ca" in lowercase, there are plenty of results.<br/>
Including two buttons to confirm the filter and clear the filters is also needed. The buttons would be located below the last filter.

<br/>
