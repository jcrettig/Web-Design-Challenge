# Web-Design-Challenge

## Project Setup

1) Create a repository on GitHub – Web-Design-Challenge

2) Cloned repository to my computer

3) Added folders and files to the repository on my computer

4) Pushed the changes in my computer repository to GitHub

5) Deployed to GitHub Pages

## Website Creation

1)  The website is composed of 7 pages

2)  All Pages Contain a Navigation Bar (navbar)

2a)  The name of the site is on the left side of the navbar and links to the Landing page

2b)  On the right side of the navbar is a dropdown menu named “Plots” that contains 4 links to the 4 visualization pages

2c)  On the right side of the navbar are 2 links to the “Comparisons” page and the “Data” page

2d)  The navbar is responsive (using media queries)

2e)  The navbar has similar behavior to the screenshots provided when reduced to a smaller screen

3)  Landing Page - Web-Design-Challenge/index

3a)  Contains an explanation of the project

3b)  Links to each visualization page 

3c)  Contains a sidebar with preview images of each plot and the images link to the respective visualizations

4)  Visualization Pages - Web-Design-Challenge/max_temp, /humidity, /cloudiness and /wind_speed

4a)  All contain a descriptive title and heading tag

4b)  All contain the appropriate plot/visualization for comparison

4c)  All contain a descriptive paragraph of the plot and its significance

4d)  All contain below the plot/visualization and descriptive paragraph preview images of each plot and the images link to the respective visualizations

5)  Comparison Page - Web-Design-Challenge/comparison 

5a)  Contains all of the visualization so that they can be easily compared

5b)  Uses a Bootstrap grid that is 2 visualizations across on large and medium screens and 1 across on small screens

6)  Data Page - Web-Design-Challenge/data

6a)  Displays a responsive table containing the data used in the visualizations

6b)  The table is a bootstrap table component

6c)  The data comes from exporting the cities.csv located in the Resources folder as HTML

6ci)Used the Pandas method “to_html” in the csv_to_html.ipynb to convert the data to html an copied the output to the data.html file

7)  The website was deployed to GitHub Pages

## Comments and Observations

This was probably the most challenging homework assignment to date.  However, I do expect to say the same thing next week about the scraping assignment.  Challenging items included, the navbar dropdown  and the landing page layout.  on the navbar.  I used w3Schools.com to assist me with the dropdown but the explanation on w3schools did not include the activation coding required at the end of the HTML body.  Fred assisted me with this (and I am very grateful).  

The layout on the landing pages to get the visualizations on the right side of the screen was also challenging.  I initially attempted to set this up using an “inline styling” but could not get this to work.  I then used the media queries grid to set it up which was successful, but I could not fully figure out how to get the styling as I desired – “Visualizations” subheader on the same line as the “Summary: Latitude vs. X” header and the paragraphs to wrap around the chart on the right side of the screen.  



