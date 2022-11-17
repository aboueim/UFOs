# UFO Sightings Project

## Overview of Project

In this project, I aimed to build a webpage that allows users to search and filter out UFO sightings stored in an HTML table. In doing so, I wrote javascript and html codes to design and actualize the webpage. Specifically, as the backbone of the webpage, the html code enforced a desired layout and visualizations such as a navigator, heading, a short article, and a table. Besides, the webpage is designed in a way that the table is filled with UFO sighting data which can be filtered given the date and time of sightings, their location (i.e., country, state, city) and shape. This became possible with the help of the javascript code which allowed reading UFO sighting data, loading it to the HTML table, and enabling filtering via calling jvacscript functions. In the following, I provided more details on the filtering process on the webpage and the associated results.

## Results

Once opening the webpage, a user can see a table at the bottom of the page where a large set of UFO sightings are stored based on their date and time of occurence, location, shape and comments written about them. On the left side of the table, there are five filtering options are located that allow users to search sightings given their date, city, state, country, and shape. Below shows a screenshot of the table and filter options.

![This is an image](/Table_Filters.png)

A user can search for UFO sightings using one or a group of filter search options. Below I provided screenshots of how using each filter input relusts in differential search results.

1. Filtering by a Date (1/1/2010):

![This is an image](/By_Date.png)

2. Filtering by a City (el cajon):

![This is an image](/By_City.png)

3. Filtering by a State (or):

![This is an image](/By_State.png)

4. Filtering by a Country (ca):

![This is an image](/By_Country.png)

5. Filtering by Shape (triangle):

![This is an image](/By_Shape.png)

5. Combine filtering (date: 1/1/2010; city: el cajon, shape: triangle):

![This is an image](/Combined.png)

As can be seen through the screenshots, all filtering options work properly!


## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

### Drawback:

A major drawback of the new design is the restriction posed by the filters to search only when the exact text is used. In fact, in case a user is unsure of the correct spelling of words or if the stored data is not in a standard format (for example, abbreviations used for state names), searching the desired value would be difficult.

### Solutions

  1. One solution to this issue would be freeing this restriction and showing results even if the search input is partially represents the intended value.
  2. Another solution would be presenting search results in drop-down lists where users can manually go through closely related results and find the desired one.
