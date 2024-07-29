# Rotten Tomatoes Top 300 Movies Analysis

Welcome to my analysis of Rotten Tomatoes' top 300 movies of all time. This project was in collaboration with Mert Tarim, as we collected information on every movie's reception and general statistics. I used our data collection and manipulation to analyze the interplay of audience and critic reviews of these movies and sought insight into which variables might hint at a movie's success. 

## Introduction

As the movie industry makes a comeback from post-pandemic struggles in theaters, public interest in movies has increased. I also have recently been more interested in watching and analyzing movies, so I wanted to identify characteristics of successful movies using Rotten Tomatoes' general information on movies. This analysis explores how critics and audience see the top mvies and what can indicate their success.

## Methodology

The data was collected from the Rotten Tomatoe top 300 movies list and within each movie's individual pages. The information covered included movie title, rank, directors, speechwriters, revenue, ratings, and even more technical details. The analysis includes:

- Critic vs Audience Scores
- Trends over time, revenue, language

## Results

### Critics vs Audience

![Fig. 1 -- Revenue vs Audience Score](./figures/revenue_audience.png)

![Fig. 2 -- Revenue vs Critics Score](./figures/revenue_critics.png)

![Fig. 3 -- Audience vs Critics Score](./figures/audience_critics.png)

![Fig. 4 -- Audience vs Critics Scores Across Genres](./figures/diff_mean_genre.png)

- **Revenue and Audience Score**: There seems to be a positive relationship between a movie's revenue and audience score, and this makes sense, as better performing movies are a result of audience members appreciting them.
- **Revenue and Critics Score**: The relationship between revenue and critics score is not quite obvious. This indicates that not only may critics score differ from the audience, but also that their opinions don't correlate with a movie's financial success.
- **Audience Score vs Critics Score**: This plot confirms that critics and audience members don't necessarily have the same exact opinions on movies. 
- **Difference in Mean Ratings Across Genres**: We see that across different genres, critics appreciate different types of movies more than the audience. Interestingly, musicals and horror films were overwhelmingly higher rated by critics. It's also not too surprising that critics favored these movies more across all genres as the list was compromised by the top 300 movies in the critics perspective.

### Other Trends

![Fig. 5 -- Rank vs Revenue](./figures/rank_revenue.png)

![Fig. 6 -- Rank vs Runtime](./figures/rank_runtime.png)

![Fig. 7 -- Release Data vs Rank](./figures/date_rank.png)

![Fig. 8 -- Runtime Distribution Across Genres](./figures/runtime_distribution_genre.png)

- **one**
- **two**
- **three**
- **four**

## Discussion

The analysis reveals that bread prices at Waitrose are influenced by several factors, including the type of bread, production costs, and seasonal demand. Sourdough bread, being a premium product, commands the highest price, while staple items like white bread maintain a more stable and lower price point.

## Conclusion

This study provides valuable insights into the pricing trends of bread at Waitrose. Understanding these trends can help consumers make informed decisions and potentially lead to savings on their grocery bills. Future studies could expand on this analysis by comparing prices with other supermarkets to give consumers a broader perspective.

## Acknowledgements

I would like to thank my teammate Mert Tarim for being an awesome teammate.

## Generative AI Acknowledgement

This assignment was completed with the assistance of ChatGPT.

More specifically, I usedd it in the following ways:

- When I was trying to read from the SQL webpages I have created and trying to merge those pages in a single dataframe, I had some problems with the syntax. I have used ChatGPT to correct the syntax of my code for reading from the database.