# Web-Design-Challenge
 
## Background

Previous efforts were undertaken to use Citipy to generate a random list of city weather data into a data frame to identify weather trends.  Further comparisons were made between the Northern and Southern Hemispheres.  Plots were generated for temperature, humidity, cloudiness, and windiness for both aforementioned hemispheres and a global summary.  The outputs were stored in this repository.

## This Repository

The purpose of this repository is to expand upon previous efforts by developing a website portraying the results of the previous API work.  This site includes the following pages:

  1. Homepage (index.html):
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Includes a description of the project.
	- Global plot frames for temperature, humidity, cloudiness, and windiness.
	- Each plot has a link that takes the user to the corresponding plot page (e.g., TempPlot-to-temp.html, etc.)
	- Uses a Bootstrap grid for the visualizations.
	- Visualizations are in grids for medium and larger screens.
  2. Temperature (viz/temp.html)
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Includes a description of the plots and the previous conclusions made from the plots.
	- Plots for the global data, data from cities in the northern hemisphere, and data from the southern hemisphere.
	- Uses a Bootstrap grid for the visualizations.
	- Visualizations are in grids for medium and larger screens.
  3. Humidity (viz/humidity.html)
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Includes a description of the plots and the previous conclusions made from the plots.
	- Plots for the global data, data from cities in the northern hemisphere, and data from the southern hemisphere.
	- Uses a Bootstrap grid for the visualizations.
	- Visualizations are in grids for medium and larger screens.  
  3. Cloudiness (viz/clouds.html)
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Includes a description of the plots and the previous conclusions made from the plots.
	- Plots for the global data, data from cities in the northern hemisphere, and data from the southern hemisphere.  
  4. Windspeed (vis/wind.html)
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Includes a description of the plots and the previous conclusions made from the plots.
	- Plots for the global data, data from cities in the northern hemisphere, and data from the southern hemisphere.  
  6. Comparisons (comparison.html)
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Includes side-by-side comparisons of plots for each category of data including temperature, humidity, cloudiness, and windiness.
	- Plots for the global data, northern hemisphere data, and Southern Hemisphere data are displayed for each category.
  7. Data (data.html)
	- Navigator and search bar at the top of the page which includes links to the repo and other pages.
	- Climate Dashboard Header takes the user to the homepage.
	- Displays a data frame that was ultimately the output of using the API.  


### Workflow:

  1. html pages were created as templates and organized which included the navigation menu and bootstrap scripts.
  2. Navigation menu has links associated to each of the child pages.
  3. "Climate Dashboard" header always links to the parent page (index.html).
  4. Homepage was developed with a description and preview of global plots for all weather categories that link to the corresponding child page.
  5. A visualization template was developed to include the use of grids to display the plot data.
  6. Conclusions that were previously made regarding the plots is displayed on the page.
  7. Comparison page of each plots across all categories were created using the Bootstrap Grid template.
  8. Original data frame was copied from the original repository into the new repository as a csv (data/cities_df.csv).
  9. Pandas code was developed to export the csv file into html tables (data_to_html.ipynb)
  10. The html table code was copied and pasted into another html file so that the layout was consistent with the remaining pages (e.g., navigator, etc.)
  11. As mentioned, the goal was to stay as consistent as possible with the prior work, so the previous repository was used for the data, and links were acquired for displaying the plot images.