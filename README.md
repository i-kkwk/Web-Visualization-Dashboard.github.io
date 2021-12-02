# Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what I've learned about HTML and CSS to create a dashboard showing off the analysis I've done.

![Images/landingResize.png](landingResize.png)


## Latitude - Latitude Analysis Dashboard with Attitude

For this project I'll be creating a visualization dashboard website using visualizations I've created in a past project. Specifically, I'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, I'll create individual pages for each plot and a means by which I can navigate between them. These pages will contain the visualizations and their corresponding explanations. I'll also have a landing page, a page where I can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements


The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.


### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; I can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](landingResize.png)

Small screen:

![Landing page small screen](landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](comparison-lg.png)

Small screen:

![comparison page small screen](comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](data-lg.png)


Small screen:

![data page small screen](data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](visualize-lg.png)

Small screen:

![visualize page small screen](visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](nav-lg.png)

Small screen:
![nav menu small screen](nav-sm.png)



## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
