# Conceptual Overview for Developers

  
**Why can MyFavoriteAlbums be useful for developers?**

  

MyFavoriteAlbums can be useful for developers wanting to create their own data visualization, using the original as an example and to be modeled after.

  

MyFavoriteAlbums can:

-   Visualize a dataset of albums across a range of years
    
-   Rank and rate albums from artists and bands using filters and toggles that users can adjust
    
-   Group data by artist or year to support aggregation
    
-   Use a CSV file for data
    
-   Use RStudio to manipulate CSV file for UI interface  
      
    

# UI Framework

  

MyFavoriteAlbums was built using Shiny Web App, a framework for creating interactive web software directly from the R programming language.

  

The UI is created from multiple source files coded in R. Each source file is used to create different tabs corresponding to a different conceptual query or illustration of the data.

  

-   Home tab
	- Acts as an introduction page to share brief info about the scope of total numerical data utilized and also welcome the users
    

-   Number one Albums tab
	- A representation of personal number one albums over a range of years where the data is aggregated for the user to experiment with
    

-   Top Albums by Year tab
	- A filtered subset of data with a ranking system to structure data in favorite to least favorite of a given year
    

-   Artists Album tab
	- A grouped data model where artist and band can be filtered with breakdowns where specific statistics such as average rating and album count
    

-   Favorite Artist tab
	- A filtered aggregation model where artists are included conditionally if they meet defined thresholds such as a minimum number of albums
    

-   Artist Comparison tab
	- A graphical representation of albums where two albums are plotted on a year over rating graph illustrating data comparison across time
    

-   Vinyl tab
	- Conditional representation of data where items meeting rating criteria, but not belonging to a “vinyl-owned” category are displayed, illustrating categorical filtering.
    

  

# Limitations

  

MyFavoriteAlbums cannot:

-   Stream any selected music for listening purposes
    
-   Update automatically
    
-   Illustrate global music ranking data
    

  

# Tools and Technologies Required

  

-   RStudio- IDE for developing R code.
    
-   CSV (comma-separated values) file - a plain text file that stores tabular data in a structured format
    
-   Github - a web-based platform used for version control and collaborative software development
    
-   Shiny Apps (shinyapps.io)- Web application to publish and visualize code from R language
    
-   dpylr - Data library and package for data manipulation
    
-   ggplot2 - Data library and package for data visualizations
    
-   shiny - Data library and package to develop interactive web apps with R
    

  

# How does it work together

-   CSV file can be downloaded on GitHub
    
-   CSV file can be downloaded to Rstudio
    
-   On Rstudio, dpylr, ggplot2, and the shiny package can be downloaded on the console
    
-   With the libraries installed, R studio can run the UI interface on Shiny Apps
