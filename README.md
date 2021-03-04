# Web-Design-Challenge

Project Setup
Create a repository on GitHub – Web-Design-Challenge
Cloned repository to my computer
Added folders and files to the repository on my computer
Pushed the changes in my computer repository to GitHub
Deployed to GitHub Pages
Website Creation
The website is composed of 7 pages
All Pages Contain a Navigation Bar (navbar)
The name of the site is on the left side of the navbar and links to the Landing page
On the right side of the navbar is a dropdown menu named “Plots” that contains 4 links to the 4 visualization pages
On the right side of the navbar are 2 links to the “Comparisons” page and the “Data” page
The navbar is responsive (using media queries)
The navbar has similar behavior to the screenshots provided when reduced to a smaller screen
Landing Page - Web-Design-Challenge/index
Contains an explanation of the project
Links to each visualization page 
Contains a sidebar with preview images of each plot and the images link to the respective visualizations
Visualization Pages - Web-Design-Challenge/max_temp, /humidity, /cloudiness and /wind_speed
All contain a descriptive title and heading tag
All contain the appropriate plot/visualization for comparison
All contain a descriptive paragraph of the plot and its significance
All contain below the plot/visualization and descriptive paragraph preview images of each plot and the images link to the respective visualizations
Comparison Page - Web-Design-Challenge/comparison 
Contains all of the visualization so that they can be easily compared
Uses a Bootstrap grid that is 2 visualizations across on large and medium screens and 1 across on small screens
Data Page - Web-Design-Challenge/data
Displays a responsive table containing the data used in the visualizations
The table is a bootstrap table component
The data comes from exporting the cities.csv located in the Resources folder as HTML
Used the Pandas method “to_html” in the csv_to_html.ipynb to convert the data to html an copied the output to the data.html file
The website was deployed to GitHub Pages
Comments and Observations
This was probably the most challenging homework assignment to date.  However, I do expect to say the same thing next week about the scraping assignment.  Challenging items included, the navbar dropdown  and the landing page layout.  on the navbar.  I used w3Schools.com to assist me with the dropdown but the explanation on w3schools did not include the activation coding required at the end of the HTML body.  Fred assisted me with this (and I am very grateful).  
The layout on the landing pages to get the visualizations on the right side of the screen was also challenging.  I initially attempted to set this up using an “inline styling” but could not get this to work.  I then used the media queries grid to set it up which was successful, but I could not fully figure out how to get the styling as I desired – “Visualizations” subheader on the same line as the “Summary: Latitude vs. X” header and the paragraphs to wrap around the chart on the right side of the screen.  



