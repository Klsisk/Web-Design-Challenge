# Web Design : Web Visualization Dashboard (Latitude)

# (https://klsisk.github.io/Web-Design-Challenge/)

## Background
Create a Visualization Dashboard Website of Weather in 500+ World Cities Relative to the Equator at Different Latitudes Using HTML5, CSS3 and Bootstrap 4

### Objectives
In building this dashboard, create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements
The website must consist of 7 pages total, including:
- A Landing Page containing:
  - An explanation of the project.
  - Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
  
![image](https://user-images.githubusercontent.com/69765842/103469043-d5287e80-4d2d-11eb-8ec6-66882c516749.png)

-Four visualization pages, each with:
  - A descriptive title and heading tag.
  - The plot/visualization itself for the selected comparison.
  - A paragraph describing the plot and its significance.
  
![image](https://user-images.githubusercontent.com/69765842/103469046-de195000-4d2d-11eb-9c3c-74c3a88322e3.png)

- A "Comparisons" page that:
  - Contains all of the visualizations on the same page so we can easily visually compare them.
  - Uses a Bootstrap grid for the visualizations.
  - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
  
![image](https://user-images.githubusercontent.com/69765842/103469054-f4bfa700-4d2d-11eb-9c77-3c695d0be600.png)

- A "Data" page that:
  - Displays a responsive table containing the data used in the visualizations.
    - The table must be a bootstrap table component. 
    - The data must come from exporting the .csv file as HTML, or converting it to HTML. 
    
![image](https://user-images.githubusercontent.com/69765842/103469056-06a14a00-4d2e-11eb-8972-b6f2b6f0b06c.png)
    
The website must, at the top of every page, have a navigation menu that:
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
- Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
- Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).
