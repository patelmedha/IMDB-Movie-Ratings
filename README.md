# Movies-IMBD

## Data
The data used is sourced from IMDB.

![](https://www.themoviedb.org/assets/2/v4/logos/v2/blue_long_2-9665a76b1ae401a510ec1e0ca40ddcb3b0cfe45f1d51b77a308fea0845885648.svg)

- IMDB Provides Several Files with varied information for Movies, TV Shows, Made for TV Movies, etc.
    - Overview/Data Dictionary: https://www.imdb.com/interfaces/
    - Downloads page: https://datasets.imdbws.com/

## Exploratory Data Analysis

1. How many movies had at least some valid financial information (values > 0 for budget OR revenue)?(Please exclude any movies with 0's for budget AND revenue from the remaining visualizations.)
- There are 642 movies with valid financial information.
    ![Number of Movies with Valid Financial Information](Images/valid_financial_movies.png)
    
2. How many movies are there in each of the certification categories (G/PG/PG-13/R)?
- Total number of movies per certification category is:
    R          466
    PG-13      182
    NR          71
    PG          62
    G           24
    NC-17        6
    Unrated      1
    
    ![Movies per Certification Category (2000-2001)](Images/movies00_01_per_category.png)
    
3. What is the average revenue per certification category?
-The average revenue per certification category is:
certification
G          73352976.0
NC-17             0.0
NR          2295880.0
PG         62480126.0
PG-13      71465436.0
R          15290259.0
Unrated           0.0

   ![Movies Average Budget by Certification (2000-2001)](Images/avg_budget_certification_movies00_01.png)

    
    
