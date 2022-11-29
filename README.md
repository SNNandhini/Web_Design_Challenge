# Web_Design_Challenge
Web Visualization Dashboard!

This challenge is to use HTML and CSS to create a dashboard featuring the Latitude vs. X analysis of weather. 

The website is created by using the following visualizations that were created as part of the Python-APIs Challenge:
- Latitude Vs. Max Temp
- Latitude Vs. Humidity
- Latitude Vs. Cloudiness
- Latitude Vs. Wind Speed
  
This dashboard has individual pages for each of the above plots and a way to navigate between them. These pages contain the visualizations and their descriptions. There is also a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

The web application deployed as part of this challenge can be viewed on https://snnandhini.github.io/Web_Design_Challenge/

The 7 pages built for the challenge are explained below.

## Landing Page
-   This page contains an explanation of the project, links to each visualization and a sidebar containing preview images of each plot. 
-   Clicking an image takes the user to the selected visualization. 
 
The picture of the landing page on large/ medium sized screens and small/ very small screens are as follows: 

![image](https://user-images.githubusercontent.com/111614210/204406313-89d90017-0e2a-4fa4-88f0-4d7d77844fca.png)

## Visualization Pages
-   Each of the four visualization pages contain a title, a plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed) and a paragraph describing the plot and its significance. 

The picture of visualization page for Maximum Temperature on large/ medium sized screens and small/ very small screens are as follows: 
![image](https://user-images.githubusercontent.com/111614210/204408359-a7242f65-b99d-4805-afb3-aa08ce02538b.png)

The other visualization pages are similar to the above page.

## Comparisons Page
-   This page contains all of the visualizations on the same page so they can easily be compared with each other. 
-   A Bootstrap grid is used for the visualizations. 

The picture of Comparison page on large/ medium sized screens and small/ very small screens are as follows: 
![image](https://user-images.githubusercontent.com/111614210/204593383-a0df7c5d-874b-44c5-a774-fb7e41d53830.png)

## Data Page
-   This page displays a responsive table containing the data used in the visualizations. 
-   The table is a Bootstrap component. 
-   The data comes from the cities.csv file generated in the Python APIs Challenge. For this, the pandas' to_html method is used to generate the html table. 


## Navigation Bar
-   The website has a navigation bar at the top of every page. 
-   The name of the site is present on the left of the navigation bar, allowing users to return to the landing page from any page.
-   A dropdown menu is present on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.
-   There are two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
-   The navigation bar is responsive (using media queries).




