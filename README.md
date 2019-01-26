# Web Visualization Dashboard of Weather at Different Latitudes


![Images/landingResize.png](Images/landingResize.png)

## Latitude - Latitude Analysis Dashboard with Attitude

A visualization dashboard website plotting [weather data](Resources/cities.csv).

 Website includes individual pages for each plot and a way to navigate between them. These pages contain the visualizations and their corresponding explanations. On the landing page, we can see a comparison of all of the plots, and there is another page where we can view the data used to build these plots. 

### Website Requirements

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A Comparisons page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A data page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML.

The website has, at the top of every page, a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). 

 The final deployed app: https://locketylerj.github.io/
