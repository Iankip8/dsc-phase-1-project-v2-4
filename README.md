# Film Production Recommendations for Microsoft's New Movie Studio


## Project Overview

For this project, you will use exploratory data analysis to generate insights for a business stakeholder.

## Business Understanding

### Stakeholders 
    -Microsoft
    -Potentially investors or partners interested in the success of Microsoft's new movie studio venture

### key business questions
1.Does the total number of films produced relate to the total gross income?

2.How is rating related to movie duration?

3.Is there a relationship between the popularity of movies and the number of votes they receive on a movie rating platform?

4.What are the trends observed in the average popularity of films across different release years?

5.What are the top 10 most popular movie genres, and how do their popularity ratings compare?


## Data Understanding and Analysis

### Data Sources
    -Box Office Mojo
    -Rotten Tomatoes
    -TheMovieDB

### Data Description
    1.Box Office Mojo    
The dataset from Box Office Mojo contains information about various movies, including their titles, studios, domestic gross revenue, foreign gross revenue, and the release year. This data provides insights into the financial performance of movies at the box office, both domestically and internationally. Each row represents a different movie, with details such as the studio responsible for its production, the amount of revenue generated domestically and internationally, and the year of release. Analyzing this dataset can offer valuable insights into the success of movies across different studios and years, helping stakeholders in the film industry make informed decisions regarding future productions, investments, and business strategies.

    2.Rotten Tomatoes
The dataset includes information about several movies, such as their ID, synopsis, rating, genre, director, writer, theater release date, DVD release date, currency, box office earnings, runtime, and studio. Each row represents a different movie, with details such as the movie's synopsis, rating, genre, director, writer, release dates, financial performance, runtime, and the studio responsible for its production. This dataset provides valuable insights into various aspects of movies, including their content, critical reception, financial success, and production details. Analyzing this data can help stakeholders in the film industry understand trends, make informed decisions, and develop strategies for future movie productions.

    3.TheMovieDB
The dataset contains information about several movies, including their genre IDs, original language, original title, popularity, release date, title, vote average, and vote count. Each row represents a different movie, with details such as the movie's genre IDs, language, popularity score, release date, title, and voting statistics. The genre IDs indicate the genres associated with each movie, while the original language denotes the language in which the movie was originally produced. Other attributes such as popularity, release date, and voting statistics provide insights into the movie's reception and audience engagement. This dataset can be analyzed to understand trends in movie genres, popularity, and audience preferences over time.

## Visualizations

![scatterplot1](https://github.com/Iankip8/dsc-phase-1-project-v2-4/assets/160301660/fd242430-d66c-4b30-b411-a3442a66f513)


The plot reveals a correlation between the total pay received and the number of films produced by studios. This suggests that as the number of films produced increases, there is a corresponding rise in total pay.


![MovingRating1](https://github.com/Iankip8/dsc-phase-1-project-v2-4/assets/160301660/18e961dd-612b-4f9c-b2e5-694de44b77cb)


The box plot provides insights into the distribution of movie runtimes across different rating categories. It reveals the central tendency, variability, and presence of outliers within each rating category

![popovertime1](https://github.com/Iankip8/dsc-phase-1-project-v2-4/assets/160301660/07c82c6b-fafe-4d4a-8dd2-1eef0ec72f9b)


The plotted graph illustrates a fluctuating pattern, revealing the evolution of average popularity across various years of film releases. As the timeline progresses, the trend of average popularity demonstrates both peaks and troughs, suggesting dynamic shifts in audience interest over time. This visual representation provides insights into the changing landscape of popularity within the film industry across different release years.

![top10genre_popularity](https://github.com/Iankip8/dsc-phase-1-project-v2-4/assets/160301660/0e753f36-d096-484f-8ccb-ebd0f36d0293)


The plot illustrates the popularity of the top  movies across major genres. Each bar represents a genre, and its height indicates the popularity of the corresponding movies within that genre. The y-axis represents the popularity score, while the x-axis shows the major genres. This visualization allows the company to identify which genres are most popular among audiences, providing valuable insights for decision-making in film production and marketing strategies.


