# Who's there: UFO sightings

## Overview

Dana, a data journalist, got an assignment to write about UFO sightings. She would like to create an webpage that includes a dynamic table providing information on all UFO sightings in the US.

### Resources

- Data Source: data.js
- VS Code
- JavaSript
- HTML
- Bootstrap 

### Purpose

The purpose of this project is to use JavaScript, HTML, and CSS to create a custom webpage that presents UFO sightings and allows users to filter the data by Date, City, State, Country, and Shape.

## Results

- An HTML script specified how to display the data on a webpage. A container in the HTML file was created for the user to input their search criteria to filter the data accordingly. Filtering can be done on Date, City, State, Country, and Shape.

- Two functions were defined using JavaScript:
    - **updateFilters()** updates the filters based on user input;
    - **filterTable()** loops through the dataset and stores data based on filters in the table.
    
- The HTML script is able, by calling the JavaScripts function, to display filtered table. Below is the webpage without any filters:

![Without_Filter](https://github.com/Nusratnimme/UFOs/blob/main/Resources/Without_Filter.png)

- User can filter the table on one or more criteria. For example, below image shows the table filtered by the **shape** (light) only:

![Filter_shape](https://github.com/Nusratnimme/UFOs/blob/main/Resources/Filter_shape_light.png)

- And below image shows the table filtered on **state** (ca) and **shape** (light):

![Filter_state_shape](https://github.com/Nusratnimme/UFOs/blob/main/Resources/Filter_State_Shape.png)

- Some Bootstrap elements and css stytling were added to enhance the appearance of the web page.

![UFO_webpage](https://github.com/Nusratnimme/UFOs/blob/main/Resources/UFO_webpage.png)`


## Summary

### Drawback
- A major drawback of the webpage in terms of user-friendliness is that the filters are neither dropdown nor do they suggest values based on characters typed in. For example, users need to know in advance a city where UFO sighting has been reported. Typing in just any city may return an empty table.

- The Date filter could also be a calendar for error-free inputs.

### Recommendations
Apart from addressing the drawbacks above, the webpage could be improved by:
- Allowing selection of a range of date in the Date filter, e.g., UFO sightings between June and August in 2010.
- Allowing multiple inputs in City, State, Country, and Shape, e.g., UFO sightings in North and South Carolina together.
- Allowing sorting based on any column by clicking on the column title.
- Adding option to export the data according to current filtering.
- Presenting the data in a map in addition to a table.
