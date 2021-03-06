# Web-Design-Challenge
Web design challenge
Created the Weather webpage that follows the following below conditions:
### Website Requirements
For reference, see the ["Screenshots" section] below.
The website must consist of 7 pages total, including:
* A [landing page](index.html in main folder) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages], each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

  Cloudiness visualization page

  Humidity visualization page

  Max Temperature Visualization page

  Wind Speed Visualization page


* A ["Comparisons" page] that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page] that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint]
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)
The website must, at the top of every page, have a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section] (notice the background color change).
Finally, the website must be deployed to GitHub pages: The main file is set as the index.html

The Bonus Website

The bonus website was created using the previous homework (Hawaii weather data) exported data sets for Hawaii weather and the trip data.  The website followed the same pattern as above but with a slightly different layout and colors. 

It shows the different graphs with the explanation of each one and everything can link back to the homepage as needed. See ReadMe in Bonus folder for additional information pertaining to that website.
