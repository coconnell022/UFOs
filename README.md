# UFOs

## Overview of the analysis

The purpose of this analysis is creating a webpage that showcases UFO sightings around the world using JavaScript. The data is imported in an array and analyzed to create visualizations and summary tables using an HTML file, Javascript, and Bootstrap customizations. The data set contains information on UFO sightings around the world that includes their states, countries, dates, duration, shapes, and comments. The main objective is to create a website that not only displays the data in a table but applies multiple filters for date, city, state, country and shape. This in-depth analysis allows user to filter for multiple criteria at the same time to make it easier to find specific sightings.

    Resources
     - Data Sources: data.js
     - Software: JavaScript, HTML, Bootstrap, CSS, and VS Code

## Results

![alt text](https://github.com/coconnell022/UFOs/blob/main/Images%20for%20readme/Webpage_1.png?raw=true)
![alt text](https://github.com/coconnell022/UFOs/blob/main/Images%20for%20readme/Webpage_2.png?raw=true)

As shown in the images above, the completed website contains the article title, article summary, a table with hundreds of UFO sightings, and filters to be applied to the table. Before applying any filters, it can easily be seen that there are several columns that are organizing the data set. These columns are date, city, state, country, shape, duration, and comments. 

![alt text](https://github.com/coconnell022/UFOs/blob/main/Images%20for%20readme/Filtered_results.png?raw=true)

The image above shows a demonstration of how to apply filters to the dataset. As shown, to the left side of the table, there are several white text boxes that allow for the user to input specific filters when searching for UFO sightings. It should be noted that not every filter text box needs to be added to filter the data. For example, if someone wanted to find UFO sightings in California, all they simply need to do is type "ca" into the "Enter Country" filter text box and press enter. If a user wants to be more specific, like in the example below, they can type the exact city, date, shape, state, and/or country that they are looking for. It is also important to note that as a user adds filters, that all text needs to remain lowercase and spelled correctly otherwise they may encounter an error. If a user wishes to reset the table and remove any filters they can refresh the page or press the "UFO Sightings" button in the top left corner of the webpage. 

## Summary

One drawback of this webpage and design would be the need for lowercase and exact text to be typed into the filter text boxes by users. It might be more beneficial to add a dropdown box rather than a simple text box to allow the user to pick the specific filter they are searching for within the data set. This would ensure that no error is occurring and that all users’ filters are accurately displaying the data they are searching for. 

One recommendation for further development would be to add more data driven visualizations to the website. Since there are hundreds of data points that include specific region, it would be interesting to provide a filtered enabled heat map on the webpage. This heat map would then show the user obvious hotspots across the world for UFO sightings and provide them with additional insight into data trends. 

Another recommendation for a further analysis would be to provide additional links to the source data for further inquiry. A limitation of the design shows that many comments within the data table appear to be slightly cut off on the webpage. It might be helpful to the user to see the full comment by providing a link to the source that generated the data, either directly next to the table or within a hyperlink. 

        Caroline O'Connell
        December 13th, 2020
