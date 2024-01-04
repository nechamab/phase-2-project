![header_image](images/header_image.png)

# Overview

We are consultants hired to produce three or more actionable reccomendations which will guide your company in their new venture: opening a movie studio to produce films.


# Business Understanding

From our understanding, your entry into this industry is primarily motivated by revenue rather than an urge to create art, so our analysis defines success as the ratio of Revenue / Budget for a 
film or segment of the industry. We assume you are looking to accumulate revenue rather than win awards or garner high ratings for your efforts. As such, we sought to answer questions such
as: what types moies tend to be most profitable based on movie genre, runtime, and release month. Are there certain actors, directors, or writers who are commonly attached to successful projects?
Do production budgets significantly affect profits, or does it make more sense to focus on revenues?


# Data Understanding and Analysis

This project utilizes python for exploratory data analysis and python along with SQL for interacting with the data in the databases. These are publicly available databases and datasets hosted on IMDB.com, Box Office Mojo, The Movie Database, The Numbers, and Rotten Tomatoes. Box Office Mojo and The Numbers datasets are .csv files, while the IMDB data is stored is a SQL-friendly database.
The majority of our useful data encompasses the years 2010 to 2018, or 2010 to 2021 in some cases. These data sets and databases contain wide-ranging information on movie finances, audience review
scores, production details including relevant directors and actors, and more. By combining data from different sources we were able to extract information which led us to the following conclusions:

![Genres](images/output_10_0.png)

![worldwide_gross](images/gross_budget_profit_month.png)
![worldwide_gross](images/gross_budget_profit_month_fam.png)

![dir_writer_actor](images/directors_writers_actors.png)

![movie_runtimes_hist](images/dist_runtimes.png)
![movie_runtimes_scatter](images/scatter_runtimes.png)

# Conclusion

In conclusion, we reccomend that:
    - You focus your early efforts on making a film or films in the Family genre. We also see highly profitable films in other genres such as Thriller, Crime, and Fantasy, but Family films
        appear to be the most profitable overall.

    - You tailor your release date to fit your film's desired market positioning: holiday season (Nov and December) sees increased demand from moviegoers but also increased competition from 
        other movie studios for moviegoer attention.

    - You pursue one or more of the actors, writers, or directors whose work is correlated with above-average success in the Family genre. Specifically, Brandon Camp is a writer/director/actor
        whose films return above-average gross revenue to budget ratios.

    - Runtime for your first movie should be around 1hr 40min

    - Your production budget should be approximately $65m