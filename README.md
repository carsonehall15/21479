
## Team Name and Members

Team Name: 21479_2

Team Members:
* [@CarsonHall](https://github.com/carsonehall15/21479)
* [@Jacob Hoover](https://github.com/Jakehoov1/SQLGroupProject2)
* [@Ryan Restino](https://github.com/rrestinoRyan-Restino-MIST4610-GroupProject2)
* [@Mason Sprinkle](https://github.com/masonSprinkle/21479)
* [@Owen Swonger]()


## The Dataset


* [DATA SET](https://www.kaggle.com/datasets/danielgrijalvas/movies)

Our data set contains 15 columns

    1. budget: the budget of a movie
    2. company: the production company
    3. country: country of origin
    4. director: the director
    5. genre: main genre of the movie.
    6. gross: revenue of the movie
    7. name: name of the movie
    8. rating: rating of the movie (R, PG, etc.)
    9. released: release date (YYYY-MM-DD)
    10. runtime: duration of the movie
    11. score: IMDb user rating
    12. votes: number of user votes
    13. star: main actor/actress
    14. writer: writer of the movie
    15. year: year of release

Our data set contains 6820 movies (rows), some having all of the attributes and some only containing a few of the attributes


## Question #1: In the top 20 countries (based on average scores of movies produced in that country), what is the most popular genre (based on score)?

This question is relevant to management at the company because it will help them to determine their target audience in each country based on the most popular genre that customers and critics like as well as how the movies are scoring. This way, management can prioritize these genres and maximize profits in these areas.


    Attributes we used for analysis in Map visulaization: 
    1. country
    2. SUM(budget)
    3. year

    Attributes we used for analysis in Avg Score visulaization:
    1. country
    2. AVG(score)


![App Screenshot](https://raw.githubusercontent.com/carsonehall15/21479/main/Screen%20Shot%202023-04-26%20at%2012.15.14%20PM.png)


## Explanation of Question #1
## Question #2: In the top 10 countries (based on average scores of movies produced in that country), what is the average budget over the entire timeline of data?

This question is relevant to management because it allows them to see what the average amount they are spending on movies that are scoring the best. This will give them an idea of how much money they should plan to spend in the future. This allows for management to have a better holistic view of their expenditures and better plan for future operations. 

    Attributes we used for analysis: 
    1. 

![App Screenshot](https://raw.githubusercontent.com/carsonehall15/21479/main/Screen%20Shot%202023-04-26%20at%2012.15.05%20PM.png)
## Explanation of Question #2. 
